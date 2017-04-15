# cafe.des-blogueurs.org_skin
Design pour l'instance Mastodon Café des blogueurs
https://cafe.des-blogueurs.org 

## Présentation
Pour le moment, il n'existe pas de système dans Mastodon qui permette à un utilisateur de personnaliser son interface. Le design dépend de l'administrateur (souvent c'est celui par défaut). Cette solution n'est pas idéale mais permet d'attendre patiemment que la personnalisation existe un jour.

## Mode d'emploi avec Stylish
Cette utilisation est pratique car elle vous permet de personnaliser l'affichage de l'instance de votre choix grâce à une extension pour votre navigateur favori.

1. Télécharger ce dépôt.
2. Installer Stylish (l'extension existe pour Firefox, Chrome, Safari).
3. Positionnez-vous sur votre page Mastodon.
4. Cliquer sur l'icône de Stylish (elle se trouve en principe dans la barre d'outils) et choisir «Créer un nouveau style» (il y a plusieurs choix, prendre celui qui indique l'url de votre instance).
5. Dans la fenêtre qui appraît alors, copier-coller le contenu du fichier /public/application.css juste avant la dernière accolade.
6. Sur la seconde des barres horizontales noires de la fenêtre, donnez un nom à ce style.
7. Sur la première barre noire horizontale, cliquer sur le bouton Enregistrer.
8. Votre instance est désormais dotée de son nouvel aspect.

Si vous connaissez un peu les CSS vous pouvez modifier directement des règles dans la fenêtre de Stylish. Si vous connaissez Sass vous pouvez le faire plus proprement en travaillant à partir du répertoire /dev/ du dépôt après l'avoir téléchargé.

On peut désactiver un style personnalisé depuis les préférences de l'extension.

## Installation pour contribuer ou démarrer un nouveau design

Cloner ou forker ce dépôt, puis :

```bash
gem install sass 
gem install compass 
```

Enjoy.

## Licence

Licence MIT
Auteur : Kozlika & contributors

