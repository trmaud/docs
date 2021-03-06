## 2.4.3 (01/04/2021)
- Update des dependance (A relancer)
- Update de la library Pronote
- Correction de plusieurs erreur dans l'Api
- Mise a jours de nodeJS

## 2.4.2 (03/02/2021)
- ADD : CAS ENT "Mon collège Essonne" "www.moncollege-ent.essonne.fr"

## 2.4.1 (27/01/2021)
- ADD : Ajout d'option dans le décalage des EDT

## 2.4 (13/01/2021)
- ADD : Ajout de la commande "Journée à la maison" si 1 cours est marqué à distance aujourd'hui
- ADD : Ajout de la commande "Demain à la maison" si 1 cours est marqué à distance Demain
- ADD : Ajout d'une fonction qui cache les commandes qui ne sont pas utiles à l'utilisateur s'il est dans un autre mode que DEBUG
- ADD : Ajout du tag "timestamp" dans les events note qui contient le timestamp en millisecondes de la date de l'event
- ADD : Ajout du tag "timestamp" dans les events compétence qui contiennent le timestamp en millisecondes de la date de l'event
- ADD : Ajout de la commande "Prochains devoirs" contenant les infos des devoir mis en forme. (Peut-être mis en tant que parameter pour être send via discord ou autres)
- ADD : Ajout des event d'absence. Tag en cours de reflexion
- ADD : Plus de CAS
- UPDATE : Update du tag "date" pour le rendre dans un format lisible par un humain dans les events note ;) 
- UPDATE : Update du tag "date" pour le rendre dans un format lisible par un humain dans les events compétence ;) 
- UPDATE : Update du deamon
- UPDATE : Update de la doc pour correspondre a la BETA
- UPDATE : Update de la doc
- DEBUG : Fix Multiple error

## 2.3 (07/11/2020)
- ADD : Ajout de cron dedié au plugin
- ADD : CAS ENT "Atrium-Sud"
- ADD : CAS Cyber Colleges 42 "Académie de la Loire"
- UPDATE : Mise à jour de l'api et des dépendances associer 
- DEBUG : Correction de l'EDT en erreur
- DEBUG : Correction de l'erreur de Vie Scolaire
- DEBUG : Equipement parent choix de l'enfant
- DEBUG : Mise en conformité des objet avec la template du core
- DEBUG : Mise a jours du visuel du panel

## 2.2 (16/10/2020)
- Ajout du CAS : La Classe "Académie de Lyon"
- Ajout du CAS : ENT "Paris Classe Numerique"
- Ajout du CAS : ATEN "Académie de Bordeaux (idp-fim-ts.ac-bordeaux.fr)"
- Ajout de la commande : Premier cour aujourdhui
- Ajout de la commande : Dernier cour aujourdhui
- Ajout de la commande : Premier cour demain
- Ajout de la commande : Dernier cour demain
- Ajout de la commande : Premier Cour Aujourdhui Début
- Ajout de la commande : Dernier Cour Aujourdhui Début
- Ajout de la commande : Premier Cour Aujourdhui Fin
- Ajout de la commande : Dernier Cour Aujourdhui Fin
- Ajout de la commande : Premier Cour Demain Début
- Ajout de la commande : Dernier Cour Demain Début
- Ajout de la commande : Premier Cour Demain Fin
- Ajout de la commande : Dernier Cour Demain Fin
- Modification : Les devoirs recup seront entre -1 jour et +21 jours
- DEBUG : Debug Notes ecran Principal
- DEBUG : Correction des erreurs du panel ("Invalid argument supplied for foreach())
- DEBUG : Error `plugins/pronotlink/desktop/php/panel/panel_dashbord.php on line 49`
- DEBUG : CAS de Caen
- DEBUG : Notation max sur une note
- DEBUG : Correction  de plusieurs problèmes de refresh

### Ajout de l'onglet Action notes : 
- Exécution des actions à chaque note
- Ajout des scenarios préremplis  avec les tags suivants :  Date : #date#, Titre : #title#, Sujet : #subject#, Classe Min : #minClasse#, Classe Max : #maxClasse#, Classe Moyen : #moyenne#, Coef : #coef#, Notes : #note#, Notes Maximal : #max#, Equipement ID : #equip#
- Ajout d'un bouton pour tester les scénarios

### Ajout de l'onglet Action Competence : 
- Exécution des actions à chaque note
- Ajout des scenarios préremplis  avec les tags suivants : Date : #date#, Name: #name#, Subject: #subject#,  Long: #long#, Short: #short#, Coef : #coef#,  Equip : #equip#
- Ajout d'un bouton pour tester les scénarios


## 2.1 (08/09/2020)
- Ajout du CAS : Agora 06 “Académie de Nice”
- Correction de l’erreur de PROXY (Académie de lyon)
- Correction de l’expiration de session
- Correction d’erreur si la fonctionnalité n’est pas activée sur Pronote
- Correction de plusieurs erreurs de connexion
- Correction d’une boucle infinie
- Panel : Hide des boutons des notes et compétences si celles-ci sont vides
- Panel : Ajout de la catégorie vie Scolaire (Absence, Retard, Punition et autres)
- Panel (EDT) : Ajout d’une fonction pour décaler les heures.
- Panel (EDT) : Ajout de couleurs en fonction des informations du cours (Absence Prof, Absence Classe et retenue)
- Panel (EDT) : Ajout de texte avec des informations du cours

## 2.0 (05/09/2020)
- Mise a jours de l'Api pour Pronote 2020/2021
- Ajout du support multi enfants pour les parents
- Ajours du CAS : ENT "Haute-Garonne"
- Ajours du CAS : ENT "Collège Somme"
- Ajours du CAS : ATEN "Académie de Limoges"
- Ajours du CAS : ATEN "Académie de Nancy-Metz"
- Ajours du CAS : ATEN "Académie de Bordeaux"
- Ajours du CAS : Eclat-BCF "Académie de Dijon"
- Ajours du CAS : Toutatice "Académie de Rennes"


## *** (02/08/2020)
- Update Lien docs
- Update Repository

## 1.0 (BETA !!!!)
- Ajout de l'academie ENT "Collège Somme"
- Ajout de l'onglet "Actions Notes"
- Ajout de l'onglet "Actions Absence"
- Ajout de l'onglet "Actions Devoirs"
- Ajout de l'onglet "Actions EDT"
- Ajout de l'onglet "Actions Bulletins"
- Ajout de tags dans les scénarios executés grace à l'onglet "Actions Notes" ('title' (Intitulée devoir), 'subject' (Matière), 'maxnote' (Note maximum possible Default 20), 'note' (La note de l'élève))
- Ajout de tags dans les scénarios executés grace à l'onglet "Actions Absence" ('from' (Minute de debus), 'to' (Minutes de fin), 'solved' (Si c'est resolu), 'justified' (Si c'est justifié) 'reason' (La raison ;)))

## 0.5 (28/05/2020 à 22h00)
- Ajout de l'académie de Lille

## 0.5 (26/05/2020 à 18h11)
- Création du plugin 
