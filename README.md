# TP_Session_Authentification

Ce TP consiste à implémenter les fonctionnalités d'inscription, d'authentification et de changement de mot de passe tout en utilisant JSP et Hibernate.

Cet exercice a pour architecture:

ma.projet
1)classes(User,Client,Employe)
2)services(ClientService,EmployeService)
3)config(hibernate.cfg.xml)
4)util(HibernateUtil)
5)Test(Test --> plusieurs fichiers réparties, chaque entité a son fichier de test/ manipulation avec la base de données/ l'affichage composé des méthodes définies au niveau du couche service.
6)dao(IDao)
7)controllers(AuthentificationController.java,ClientController.java,DeconnexionController.java,PasswordController.java,UpdatePasswordController.java,VerificationController.java)

Pour base de données, veuillez créer la base de données : authentification


Concernant la couche présentation, voici une petite présentation (vidéo) des différentes interfaces de cette application:

https://github.com/LAGHRIDATHASNAE/TP_Session_Authentification/assets/148015530/5fffb063-8637-4452-9d12-30f17fe9f181

