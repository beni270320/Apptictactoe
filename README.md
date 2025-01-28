# Tic Tac Toe
 
## Description
Un jeu de Tic Tac Toe (morpion) interactif développé en React. Ce projet met en avant la gestion d'état avec React, une logique métier simple et une interface utilisateur élégante.
 
---
 
## Fonctionnalités
- **Grille de jeu** : Une interface intuitive pour jouer en mode deux joueurs.
- **Affichage dynamique** : Indique le tour du joueur actuel et le gagnant de la partie.
- **Bouton Recommencer** : Permet de redémarrer une nouvelle partie à tout moment.
- **Logiciel robuste** : Empêche les joueurs de cliquer sur une case déjà remplie ou de jouer après la fin du jeu.
 
---
 
## Structure des fichiers
 
### **1. `App.jsx`**
- Le point d'entrée principal de l'application.
- Gère l'état global du jeu (tableau de la grille, joueur actuel, gagnant).
- Connecte les composants `Board` et `Square` pour l'affichage.
 
### **2. `components/Board.jsx`**
- Gère l'affichage de la grille de jeu.
- Coordonne les cases via le composant `Square`.
 
### **3. `components/Square.jsx`**
- Représente une case individuelle du plateau.
- Réagit aux interactions utilisateur.
 
### **4. `Store/calculateWinner.js`**
- Contient la logique pour déterminer si un joueur a gagné.
- Vérifie toutes les combinaisons gagnantes possibles.
 
### **5. `styles/App.css`**
- Fichier de styles qui définit l'apparence visuelle de l'application.
- Inclut des règles pour la grille, les cases, et les interactions utilisateur (hover, ombres, etc.).
 
---
 
## Installation
 
1. **Cloner le projet** :
   ```bash
   git clone https://github.com/votre-utilisateur/tic-tac-toe.git
   ```
 
2. **Naviguer dans le répertoire** :
   ```bash
   cd tic-tac-toe
   ```
 
3. **Installer les dépendances** :
   ```bash
   npm install
   ```
 
4. **Démarrer le projet** :
   ```bash
   npm start
   ```
   L'application sera accessible à l'adresse suivante : [http://localhost:5173/](http://localhost:5173/).
 
---
 
## Technologies utilisées
- **React** : Librairie pour créer des interfaces utilisateur dynamiques.
- **CSS** : Pour le design et la mise en page.
- **JavaScript (ES6)** : Pour la logique du jeu.
 
---
 
## Aperçu visuel
 
### **Interface utilisateur :**
1. Une grille de 3x3 pour jouer au Tic Tac Toe.
2. Affichage clair du joueur en cours ou du gagnant.
3. Un bouton pour recommencer une partie.
 
---
 
## Contribution
 
1. Forkez le projet.
2. Créez une branche pour vos modifications :
   ```bash
   git checkout -b feature-nouvelle-feature
   ```
3. Faites vos changements et effectuez un commit :
   ```bash
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```
4. Poussez votre branche :
   ```bash
   git push origin feature-nouvelle-feature
   ```
5. Ouvrez une pull request.
 
---
 
## Licence
Ce projet est sous licence [MIT](LICENSE).
 
---
 
## Remerciements
Merci pour votre intérêt dans ce projet ! Si vous avez des suggestions ou des retours, n'hésitez pas à ouvrir une issue ou à me contacter.