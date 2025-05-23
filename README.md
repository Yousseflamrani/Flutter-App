## 📱 Game Haven - Blog d'articles interactif

Game Haven est une application Flutter permettant de publier, lire, modifier et supprimer des articles. L'application est sécurisée grâce à l'intégration de Firebase Authentication, Firestore et Firebase Storage. Elle inclut une interface simple et intuitive pour offrir une expérience utilisateur fluide.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🚀Fonctionnalités principales
# 🔑 Authentification
Connexion et inscription avec Firebase Authentication.
Règles de sécurité mises en place pour restreindre les actions non autorisées.
Gestion des erreurs d’authentification (blocage temporaire après 3 tentatives).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📰 Création d'articles
Les utilisateurs authentifiés peuvent créer de nouveaux articles.
Upload d'images directement depuis la galerie.
Ajout de métadonnées pour sécuriser l’accès (UID de l’auteur).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🔍 Lecture des articles
Affichage des articles sous forme de cartes avec image, titre et auteur.
Aperçu rapide avec une interface de type galerie.
Navigation intuitive pour ouvrir les détails d’un article.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## ✏️ Modification d’articles
Les auteurs peuvent modifier uniquement leurs articles.
Interface intuitive avec formulaire de mise à jour.
Règles Firebase garantissant la sécurité côté serveur.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## ❌ Suppression d’articles
Les utilisateurs peuvent supprimer leurs articles depuis la page de détails.
Confirmation avant la suppression pour éviter les erreurs.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔒 Sécurité
Seul l'auteur d'un article peut le modifier ou le supprimer (géré via les règles Firebase Storage et Firestore).
Le mot de passe est haché pour garantir une sécurité optimale. 
Un blocage temporaire du compte est appliqué après 3 tentatives de connexion échouées.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📱 Navigation de l'application
🌐 Page publique
Accueil avec un message personnalisé (exemple : Bonjour, Youssef 👋).
Affichage des articles publiés sous forme de grille.
Barre de navigation en bas avec :
Nouvel article.
Connexion/Déconnexion.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📝 Création d'article
Formulaire pour saisir le titre et le contenu.
Bouton pour sélectionner une image depuis la galerie.
Prévisualisation de l'image avant publication.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🖋️ Détails d’un article
Affichage des détails de l'article : image, titre, auteur et contenu.
Actions disponibles pour l’auteur :
Modifier l’article (via un popup).
Supprimer l’article.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Technologies utilisées
Framework principal
Flutter (UI)
Backend et stockage
Firebase Authentication
Firebase Firestore
Firebase Storage
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 💻 Installation locale
Pré-requis :

Flutter SDK

Firebase CLI 

Étapes :

Cloner le projet :


git clone https://github.com/tombruaire/projet-web-flutter.git
cd projet-web-flutter

Installer les dépendances :


flutter pub get
Configurer Firebase :

Ajoutez le fichier google-services.json (pour Android) dans le dossier android/app.
Lancer l’application :


flutter run

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📷 Captures d’écran supplémentaires
Page de connexion

<img src="https://github.com/user-attachments/assets/4a4567bf-7f3d-4fab-bf51-ac502d1b433b" alt="Page de connexion" width="50">

Page d'enregistrement

<img src="https://github.com/user-attachments/assets/f09716c8-6ac6-4dc5-9e4a-081a98845d6f" alt="Page d'enregistrement" width="50">

Page publique avec liste des articles

<img src="https://github.com/user-attachments/assets/c56badf8-5b16-4a98-9edd-ad54737fd849" alt="Page publique avec liste des articles" width="50">

Page de modification

<img src="https://github.com/user-attachments/assets/902079d0-699c-458b-9dba-867692e49d1a" alt="Page de modification" width="50">

Page de création d'article

<img src="https://github.com/user-attachments/assets/b36e61f1-5de3-490a-96f3-5b81e25f6211" alt="Page de création d'article" width="50">

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

N'hésitez pas à contribuer ou à signaler des problèmes.Merci


# Flutter-App
