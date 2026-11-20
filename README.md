# Géo Europe 🇫🇷🇪🇺

Un petit jeu web pour réviser la géographie de l'Europe : les **pays voisins de la France** et les **capitales**.

## Les jeux

Au menu, on choisit :

- **🗺️ Pays** : le nom d'un pays s'affiche ; il faut cliquer dessus sur la carte.
- **🏛️ Capitales**, avec deux types de questions :
  - **📍 Où est… ?** : une capitale s'affiche (« Où est Berlin ? ») ; il faut cliquer sur son pays.
  - **🔤 Quelle capitale ?** : un pays clignote sur la carte ; il faut choisir sa capitale parmi 4 réponses (avec des pièges : Genève, Milan, Barcelone, Rotterdam, Manchester…).

Et pour chacun, deux séries :

- **🇫🇷 Voisins** : les 8 pays limitrophes de la France (Belgique, Luxembourg, Allemagne, Suisse, Italie, Monaco, Andorre, Espagne).
- **🇪🇺 UE + Royaume-Uni** : les 27 pays de l'Union européenne et le Royaume-Uni (12 questions tirées au hasard par partie ; la France n'est pas demandée dans le jeu des pays).

## Règles

- Un **minuteur** tourne (3 niveaux : 30 s, 20 s ou 10 s).
- **3 essais** par question. Chaque erreur coûte **−25 pts**, et le jeu explique l'erreur (« Non, ça c'est l'Autriche », « Non, La Valette est la capitale de Malte »).
- Bonne réponse : **+100 pts** + bonus de rapidité.
- Après 3 erreurs ou à la fin du temps, la bonne réponse s'affiche sur la carte.
- Bouton **📖 Réviser** : la carte avec les pays ou les capitales à apprendre.
- Un record par jeu et par niveau (enregistré dans le navigateur).

Fonctionne sur ordinateur, tablette et téléphone (la série « Union européenne » est plus confortable sur un grand écran).

## Jouer

Site statique, sans dépendance : ouvrez `index.html` dans un navigateur, ou publiez le dépôt avec GitHub Pages
(Settings → Pages → Branch `main`, dossier `/ (root)`).

Carte : Natural Earth (domaine public), via `world-atlas`.
