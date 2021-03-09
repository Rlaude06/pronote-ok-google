# Note Raph
L'objectif de Note Raph ok-google est de connecter un compte pronote avec ok-google. A terme ce logiciel deviendra une suite qui aura pour objectifs d'améliorer pronote via différentes extensions :  
-Note Raph ok-google  
-Note Raph calendar (en cours de programation)  
Note Raph ok-google permet de récupérer tout ce que l'application pronote propose à la portée de votre voix.  
Par exemple, les devoirs, les moyennes, les notes l'emploi du temps etc...


# Pré-requis
Vous devez disposer :  
-de [Node js](https://nodejs.org/)  
-d'un ordinateur sous windows ou linux capable de tourner h24 (sinon tournez vous vers des options de vps (payantes))

### Installation node js
Sous windows : cliquer sur [ce lien](https://nodejs.org/) et installez le .exe qui termine par LTS   
Sous linux :
``` shell 
sudo apt update
```
``` shell 
sudo apt upgrade
```
``` shell 
sudo apt install node
```
``` shell 
sudo apt install npm
```

### Configuration de l'ordinateur
Je conseille d'utiliser un ordinateur portable qui ne sert plus à la maison et de le brancher sur secteur pour pouvoir le laisser tourner constament.
Pour cela il faut désactiver la mise en veille à la fermeture du capot (vous pouvez suivre : [ce tuto](https://forums.cnetfrance.fr/tutoriels-windows-10/665543-windows-10-comment-desactiver-la-mise-en-veille-a-la-fermeture-du-capot-d-un-pc-portable)).
Une fois fais pour simplifer la configuration je vous conseille d'installer [visual studio code](https://code.visualstudio.com/) (pas obligatoire simple conseil)
Après tout cela on peut passer à la configuration des script.

# Configuration des scripts
Si vous devez passer par un ent ou le site de votre collège pour vous authentifier vous êtes lur le bon code, sinon, si vous devez vous identifier directement via un site pronote, rendez vous sur [ce lien](https://github.com/Rlaude06/note-raph-ok-google/).
Téléchargez le fichier zip depuis le github et dézippez le dans le dossier Utilisateurs/(votre nom d'utilisateur windows) ou sur /home/(votre nom d'utilisateur) si vous êtes sur linux.  
Connectez vous à votre session pronote via un ent ou le site de votre collège et copié l'url (sans : "eleve.html?identifiant=......") qui devrait ressembler à celui-ci :  
https://????????.index-education.net/pronote/  

Allez dans le dossier Utilisateurs/(votre nom d'utilisateur)/note-raph-ok-google-cas et faites clic droit ouvrir avec Code (si vous avez installé Visual Studio Code). Sinon allez dans le dossier json et ouvrez le fichier pronote-account.json en faisant clic droit ouvrir avec > Bloc-Notes. Si vous avez choisis d'utiliser code allez dans le dossier json et cliquez sur pronote-account.json.  
Remplacez la valeur "url": "https://demo.index-education.net/pronote/" par "url": "le lien que vous avez copié (remssemblant à https://????????.index-education.net/pronote/  )" (faites attention à bien garder les guillemets.
Faites pareil en remplaçant "demonstration" par "votre nom d'utilisteur ent",   
"pronotevs" par "votre mot de passe" 
et "cas" par "votre cas" parmis la liste suivante :  
<details>
  <summary>CAS list</summary>
  
    - Académie d'Orleans-Tours (CAS : "ac-orleans-tours")
    - Académie de Besançon (CAS : "ac-besancon")
    - Académie de Bordeaux (CAS : "ac-bordeaux")
    - Académie de Bordeaux 2 (CAS : "ac-bordeaux2")
    - Académie de Caen (CAS : "ac-caen")
    - Académie de Clermont-Ferrand (CAS : "ac-clermont")
    - Académie de Dijon (CAS : "ac-dijon")
    - Académie de Grenoble (CAS : "ac-grenoble")
    - Académie de la Loire (CAS : "cybercolleges42")
    - Académie de Lille (CAS : "ac-lille")
    - Académie de Lille (CAS : "ac-lille2")
    - Académie de Limoges (CAS : "ac-limoges")
    - Académie de Lyon (CAS : "ac-lyon")
    - Académie de Marseille (CAS : "atrium-sud")
    - Académie de Montpellier (CAS : "ac-montpellier")
    - Académie de Nancy-Metz (CAS : "ac-nancy-metz")
    - Académie de Nantes (CAS : "ac-nantes")
    - Académie de Poitiers (CAS : "ac-poitiers")
    - Académie de Reims (CAS : "ac-reims")
    - Académie de Rouen (Arsene76) (CAS : "arsene76")
    - Académie de Rouen (CAS : "ac-rouen")
    - Académie de Strasbourg (CAS : "ac-strasbourg")
    - Académie de Toulouse (CAS : "ac-toulouse")
    - Académie du Val-d'Oise (CAS : "ac-valdoise")
    - ENT "Agora 06" (Nice) (CAS : "agora06")
    - ENT "Haute-Garonne" (CAS : "haute-garonne")
    - ENT "Hauts-de-France" (CAS : "hdf")
    - ENT "La Classe" (Lyon) (CAS : "laclasse")
    - ENT "Lycee Connecte" (Nouvelle-Aquitaine) (CAS : "lyceeconnecte")
    - ENT "Seine-et-Marne" (CAS : "seine-et-marne")
    - ENT "Somme" (CAS : somme)
    - ENT "Portail Famille" (Orleans Tours) (CAS : "portail-famille")
    - ENT "Toutatice" (Rennes) (CAS : "toutatice")
    - ENT "Île de France" (CAS : "iledefrance")
    - ENT "Mon collège Essonne" (CAS : "moncollege-essonne")
    - ENT "Paris Classe Numerique" (CAS : "parisclassenumerique")
    - ENT "Lycee Jean Renoir Munich" (CAS : "ljr-munich")
    - ENT "L'Eure en Normandie" (CAS : "eure-normandie")  
</details>
