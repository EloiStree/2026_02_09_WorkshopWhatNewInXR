
# Workshop: What’s New in XR

> Si le Steam Frame tombe dans mes mains avant l’atelier, le cours peut changer.

**Contexte :**
En XR, il y a beaucoup de recherche et développement. Ce qui semble aujourd’hui impossible peut, une fois résolu ou exploré, mener à des stages ou à de l’emploi.
Dans cette formation, nous allons prendre le temps de pratiquer des sujets difficiles en XR, qui vous rendront uniques sur le marché actuel.


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

**Défi : Meta Ray-Ban pour aveugle**
J’ai rencontré un malvoyant durant une conférence éducative utilisant les Meta Ray-Ban.
Le fait de pouvoir demander ce qu’il voit en face de lui était miraculeux.

Durant cette semaine, nous allons voir ce que l’on peut faire pour recréer l’application Reality Hacker
et voir comment préfiltrer l’image pour pouvoir l’envoyer à des services comme Roboflow.

**Matériel :**
* Un casque Quest 3 par personne  
* Une webcam par personne, afin d’éviter de devoir remettre le casque toutes les cinq minutes  


Pour cet atelier, je propose de pratiquer les sujets suivants :

* Comment accéder à la caméra du Quest 3 en tant que `TextureRenderer`
  * Enregistrer des photos sur le casque
* Comment appliquer au `TextureRenderer` un filtre Shader Graph ou un Compute Shader
* Pratiquer la conversion de ShaderToy vers Unity sur une webcam et sur le Quest 3
  * Parlons couleurs et lumière
* Challenge : Compute vs Job System, cherchons des blobs
  * Parlons frames et millisecondes
* Challenge : Créer en groupe Reality Hacker sur Unity3D pour le Quest 3 et téléphone Android
  * Parlons OpenAI API, OpenCV et Roboflow
  * Parlons transmission du `TextureRenderer` vers Flask en Python

Pour cet atelier, je propose de parler des sujets suivants :

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
