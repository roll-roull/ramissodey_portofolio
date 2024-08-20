# Chercheur en formation | Vision par Ordinateur

## Competences informatique
- **Python** :             _Numpy, Pandas, Tensorflow, Pytorch, Scikit-learn, Skimage, Scipy, Napari, Pydicom, Cucim, Cupy._
- **R** :                  _Analyse et tests statistique, Shiny, Markdown, RHadoop, MapReduce._
- **Scilab** :             _Modelisation et calcul scientifique_.
- **SAS** :                _Analyse de donées._
- **SQL** :               _Base de données._
- **C, C++** :            _Conception orientée objet._
- **Autres logiciels** : **Matlab  GIT  GNUPLOT  GitHub  FreeFem++**
    
## Education
- **Doctorat, Computer vision** | Polytech Orléans - LVMH Recherche, France (_02/04/2024 - à ce jour_)						       		
- **Master Mathématiques Appliquées Statistique et Data Science, Ingénierie Mathématiques**	| Univeristé d'Orléans, France (_2021 - 2023_)	 			        		
- **Master 1 Mathématiques** | Université de Tours, France (_2020 - 2021_)
- - **Licence Fondamentale en Mathématiques** | Université de Lomé, Togo (_2020 - 2021_)

## Experiences professionnelles
**Ingénieur Computer Vision @ LVMH RECHERCHE | Imagerie 3D LC-OCT (_03/2023 - à ce jour_)**

- Développement d'outils d'analyses d'images 3D LC-OCT permettant l'étude des variations des microstructures de la peau liées au vieillissement sur le visage.
- Analyses statistiques des métriques extraites des images.  
- Participation aux acquisitions d'images à partir de l'appareil LC-OCT
  
**Stagiaire Data Scientist @ CNRS Orléans | Chimiométrie - Spectroscopie Raman - Imagerie hyperspectrale (_05/2021 - 08/2023_)**
- Mise à disposition d'un script Python permettant le traitemment de données spectroscopiques : Raman, Infrarouge...
- Comparaison des méthodes (Baseline substraction, Cosmic Ray removal, Normalization, k-means, curve fitting) programées sous Python avec un logiciel de traitement existant.
- Proposition d'autres méthodes (NMF, Auto-encoder).
  
**Enseignant de Mathématiques @ Lycée Eureka**
- Initier les élèves à l'étude de fonctions, dénombrement, statistiques, nombre complexes.
- Motiver les élèes; gérer bien la classe à l'apprentissage.
- Gérer les conflits entre les élèves. 

## Projets
### Démosaïquage (projet individuel)
Le démosaïquage consiste à recouvrer une image RGB à partir de sa mosaïque de Bayer, c'est-à-dire une image en niveau de gris (une seule couche) entrelaçant des niveaux de rouge, de vert et de bleu selon une certaine géométrie (la matrice de Bayer).
Dans ce projet, l'image mosaïquée a été construite à partir de l'image couleur. Ensuite un démosaïquage bilinéaire fut implémenté en remplaçant les valeurs inconnues par une moyenne des valeurs connues. Des améliorations ont été faites en prolongeant l'image par miror afin de traiter les bords. 
Cependant ces méthodes ne rendent pas meilleur le démosaïquage. 
Les méthodes les plus performantes reposeraient sur des réseaux de neurones mais ne sont pas implémentées dans le cadre de ce projet.

### DermMNIST Classification
Ce projet consistait à classifier (de manière supervisée) sous **Pytorch***, des images de la base de données **DermMNIST** échantillonée de la manière suivante : l'ensemble d'entrainement contient 7007 images, l'ensemble de validation 1003, et celui de test 2005 images. DermMNIST renferme au total 7 classes d'images et avec les classes qui sont déséquilibrées. 
Un premier modèle a été entrâiné from scratch sur DermMNIST. Ce modèle a du mal à prédire les images des classes minoritaires. L'ajout de la **la Batch Normalization** au premier modèle permet d'obtenir un gain de 0.02 sur la précision mais a toujours du mal à prédire les images des classes minoritaires. Grâce à une augmentation (UpSampling) des images, des prédictions ont été également obtenues dans ces classes de petite taille. 

## Compétitions
### Prédiction de l'adoption de la fibre optique au Togo | Zindi
- Causality: The new science of an old question - GSP Seminar, Fall 2021
- Guest Lecture: Dimensionality Reduction - Big Data and Machine Learning for Scientific Discovery (PHYS 5336), Spring 2021
- Guest Lecture: Fourier and Wavelet Transforms - Scientific Computing (PHYS 5315), Fall 2020
- A Brief Introduction to Optimization - GSP Seminar, Fall 2019
- Weeks of Welcome Poster Competition - UTD, Fall 2019
- A Brief Introduction to Networks - GSP Seminar, Spring 2019


