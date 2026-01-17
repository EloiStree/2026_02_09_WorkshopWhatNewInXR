En construction:
- Note de project de Juillet:
  - https://github.com/EloiStree/2026_02_09_WorkshopWhatNewInXR/blob/main/Note/2026_01_17_Refactoring/ReadMe.md


---------


# Workshop: What’s New in XR

> Si le Steam Frame tombe dans mes mains avant l’atelier, le cours peut changer.   

**Atelier : Recoder Reality Hacker sur Quest 3**
[<img width="1336" height="741" alt="image" src="https://github.com/user-attachments/assets/578c18e1-6b93-440c-ab1e-739c1e6f1526" />](https://youtu.be/JnZOoryLwAI)  
*[Reality Hacker](https://reality-hacker-vr.en.softonic.com/android), archive vidéo : [https://youtu.be/JnZOoryLwAI](https://youtu.be/JnZOoryLwAI)*  

[<img width="1216" height="682" alt="image" src="https://github.com/user-attachments/assets/8339a31e-983e-4a12-97b3-c485da97c07b" />](https://youtu.be/1WNZ1vsFwXY?t=169)  
*Li-Fi : couleur et luminosité : [https://youtu.be/1WNZ1vsFwXY?t=169](https://youtu.be/1WNZ1vsFwXY?t=169)*  

[<img width="977" height="572" alt="image" src="https://github.com/user-attachments/assets/d0ff952c-8598-4df3-b618-54bcd3ede689" />](https://youtu.be/mWer5XsM5sE?t=2065)  
*Webcam et reflet de lumière : [https://youtu.be/mWer5XsM5sE?t=2065](https://youtu.be/mWer5XsM5sE?t=2065)*  


**Caméra de Meta :**

🍻 L’année passée, nous avons eu accès aux caméras du Quest 3.    
Meta a donc organisé des hackathons AI Sensai à travers le monde.    

L’idée : apprendre à utiliser la reconnaissance d’image des lunettes Meta en pratiquant sur le Quest 3.     
Préparer l’avenir AR des smart glasses.   

Une forte incitation à utiliser Roboflow et OpenCV durant ces hackathons.    
Ce que j’ai appris en jouant avec les caméras, c’est que l’on est confronté à un nouveau problème :   
La couleur 😅🎨

* Les webcams ne perçoivent pas le monde comme nous le voyons.   
* La lumière ambiante change le contexte.    
* Les lumières colorées de l’environnement détruisent la reconnaissance d’objets.   

**Compétences utiles pour un hackathon Sensai :**

* Savoir faire tourner une IA avec Sentis sur Unity3D
* Savoir exporter une image pour être traitée en ligne (avec Flask, REST, etc.)
* Savoir utiliser Roboflow 

**Matériel :**
* Un casque Quest 3 par personne    
* Une webcam par personne, afin d’éviter de devoir remettre le casque toutes les cinq minutes    


**Pour cet atelier, je propose de pratiquer les sujets suivants:** 
* Day 1: Comment accéder à la caméra du Quest 3 en tant que `TextureRenderer`
  * Enregistrer des photos sur le casque
* Day 2: Comment appliquer au `TextureRenderer` un filtre Shader Graph ou un Compute Shader
* Day 3:Pratiquer la conversion de ShaderToy vers Unity
  * Parlons couleurs et lumière
* Day 4: Challenge : Compute vs Job System, cherchons des blobs
  * Parlons frames et millisecondes
* Day 5: Challenge : Créer sur un GitHub a 12, un Reality Hacker pour le Quest 3 et téléphone Android
  

**Pour cet atelier, je propose de parler des sujets suivants:**
* Le traitement de l’image en utilisant des compute shaders sur les caméras du Quest afin de filtrer les couleurs
* OpenCV de l’Asset Store sur l’image du Quest
* Roboflow et l’API OpenAI pour l’image
* [https://www.kandaovr.com/qoocam-ego](https://www.kandaovr.com/qoocam-ego) pour la vision 180° stéréo
* Une brève démonstration de Godot XR sur le Quest 3
* Une brève discussion sur Sentis, LM Studio et Whisper
* Steam Frame en approche

---

# Deuxième semaine

La deuxième semaine est organisée par Vincent Leroy.   
Il vous prépare un exercice Unity3D propre à son expertise.   

---

## Liste des challenges "impossibles"

Il y a de nombreux sujets, et j’aimerais en parler ou partager mes connaissances dans le but de faire de la recherche et du développement.
Chacun de ces sujets peut mener à un stage, un contrat freelance ou un emploi.
N’hésitons pas à en discuter durant l’atelier.

**Challenge 1, senior :** Filtrer avec des shaders tous les pixels brûlés (lampes) et positionner les casques par rapport à ces points.
**Job :** XR Intelligence et toutes les boîtes d’applications XR sur le terrain.

**Challenge 2, senior :** Utiliser la détection de contours pour détecter les bâtiments et positionner le casque sur la place de Charleroi.
**Job :** Permettre de charger des niveaux dans le monde réel.

**Challenge 3 :** Apprendre à utiliser Roboflow avec Sentis de Unity3D directement dans le casque (l’entraîner à détecter un objet en amont).
**Job :** Toutes les sociétés qui utilisent la caméra du Quest pour fournir du contexte aux utilisateurs et entreprises d’IA sur l’image.

**Challenge 4 :** Créer une application pour aveugles via OpenAI et/ou Roboflow sur le Quest 3
(bonus : utiliser la combinaison bHaptics pour un retour sur ce qui se trouve en face de l’utilisateur).
**Job :** Contacter La Lumière pour un stage, ainsi que l’Institut pour les malvoyants de Mons.

**Challenge 5 :** Créer une application stéréo 180° à partir du contenu du Qoocam-Ego.
**Job :** Contacter Poolpio et ses concurrents pour un stage dans les applications de visualisation 360 et stéréo.

**Challenge 6 :** Explorer l’export des créations de Hyperspace du Quest 3 et leur utilisation
(si impossible, essayer d’utiliser du Gaussian Splatting dans Unity3D).
**Job :** Je n’ai pas de contact, mais c’est une compétence rare. Tu peux presque lancer une startup sur l’utilisation de Hyperspace pour les Airbnb et autres projets immobiliers.

**Challenge 7 :** Utiliser deux tags OpenCV pour auto-trianguler une scène Unity dans le monde réel (sans utiliser Vuforia).
**Job :** Construction et bâtiment utilisant les HoloLens-like, Magic Leap et Quest 3.

**Challenge 8 :** Créer une application de prise de mesures via les manettes du Quest 3 et de partage de photos ou vidéos d’un bâtiment.
**Job :** Inspection de chantier et rapport de statut communal.

---

## Entreprises belges à contacter suite au workshop

* [https://le-click.be](https://le-click.be)
* [https://previewlabs.com](https://previewlabs.com)
* [https://poolpio.com](https://poolpio.com)

## Événements à ne pas manquer pour partager le compte rendu et trouver un emploi

* [https://stereopsia.com](https://stereopsia.com)
* [https://www.gamescom.global/en](https://www.gamescom.global/en)
* [https://laval-virtual.com](https://laval-virtual.com)
* Les hackathons de [https://sensaihack.com](https://sensaihack.com)










-----------------


Use Hugging Face en Unity:  
- https://youtu.be/QIa6frPMcSQ?t=223  
