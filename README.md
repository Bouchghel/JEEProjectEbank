# Architecture Web Rendu Coté Client :
- Spring Coté backend
- Angular coté frontend

  L'objectif de cette activité pratique est de créer une application Web JEE basée sur Spring MVC et Spring Data JPA qui permet de gérer Les Comptes bancaires en faisant usage a des relations entre les tables

  Architecture de mon app : 

  ![J2EEClient1](https://github.com/Bouchghel/RepBackend/blob/main/images/c2.PNG)
  
  1 - Création des entités et des enums nécessaires :
  
  ![J2EEClient1](https://github.com/Bouchghel/RepBackend/blob/main/images/c1.PNG)
  
  2 - Création des interfaces JPA pour les différents entités : 
  
  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c5.PNG)

  3- Mappers :

  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c6.PNG)

  4- Exceptions :

  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c7.PNG)

  5- Couche service (Interface) :

  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c8.PNG)

     Implementation :
  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c9.PNG)

  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c10.PNG)

  6- Couche Web : RESTful Web services

  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c11.PNG)

  ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c12.PNG)
   
   7- la Méthode Main : 

   ![J2EEClient2](https://github.com/Bouchghel/RepBackend/blob/main/images/c3.PNG)
  
   8- Basculement vers mysql : 
  
  ![J2EEClient5](https://github.com/Bouchghel/RepBackend/blob/main/images/c4.PNG)
