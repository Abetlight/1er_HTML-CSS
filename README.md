# MIRA — Programme détaillé de la première année

Ce projet est un mini-site en HTML et CSS qui présente la première année (B1) de la formation en développement informatique de MIRA. Il permet de consulter les matières et les projets du programme, puis d’ouvrir un formulaire d’inscription de démonstration.

## Fichiers du projet

| Fichier | Rôle |
| --- | --- |
| `Programme_details.html` | Page principale avec les fondamentaux, le front-end, le back-end, les CMS, la sécurité et les objets connectés, ainsi que les cours transversaux. |
| `Inscription.html` | Formulaire avec le nom, le prénom, le choix du site (Furiani ou Ajaccio) et l’adresse e-mail. |
| `Style.css` | Feuille de style commune aux deux pages. Elle utilise Flexbox et des media queries pour adapter la mise en page à la largeur de l’écran. |

## Ouvrir le site

1. Place les deux fichiers HTML et `Style.css` dans le même dossier.
2. Place aussi les images référencées dans ce dossier pour obtenir l’affichage complet. Le code utilise `mira.png`, `front_image.png`, `access.png`, `1280.png` et `parcours.png`.
3. Ouvre `Programme_details.html` dans ton navigateur.
4. Clique sur **Formulaire** pour ouvrir la page d’inscription dans un nouvel onglet.

Le site s’ouvre directement dans le navigateur. La page d’inscription charge les icônes des réseaux sociaux via Font Awesome, ce qui nécessite une connexion Internet.

## Fonctionnement du formulaire

Le navigateur vérifie que le nom et le prénom sont renseignés et que l’adresse e-mail respecte le format attendu. Le formulaire sert à présenter l’interface et à tester la saisie. Il n’enregistre aucune inscription et n’envoie aucun e-mail.

