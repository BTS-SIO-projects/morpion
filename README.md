# 🎮 Morpion - Jeu en Java avec Swing

## 📌 Description
Morpion est un jeu développé en Java avec la bibliothèque Swing, réalisé par un groupe de 4 élèves en BTS SIO. Ce projet, codé sous Eclipse, propose un mode solo où le joueur affronte l'ordinateur, ainsi qu'un mode multijoueur (1v1).

## 🚀 Fonctionnalités principales
✅ Interface graphique intuitive avec Swing  
✅ Mode Joueur vs Joueur (1v1)  
✅ Mode Joueur vs Ordinateur (IA basique)  
✅ Gestion des tours de jeu  
✅ Détection automatique du gagnant ou d’une égalité  
✅ Redémarrage rapide d'une partie  

## 🛠️ Technologies utilisées
- **Langage** : Java (JDK 17+)  
- **IDE** : Eclipse  
- **Interface graphique** : Swing  

## 📂 Structure du projet
```
Morpion/  
│── src/  
│   ├── gui/        # Interfaces graphiques (Swing)  
│   ├── logic/      # Gestion du jeu (mouvements, IA, victoire)  
│   ├── models/     # Structures de données (grille, joueurs)  
│── lib/            # Bibliothèques externes (si nécessaire)  
│── README.txt      # Documentation  
│── Morpion.jar     # Version exécutable  
```

## 🔧 Installation et exécution

### 📥 1. Prérequis
- Java JDK 17+ installé  
- Eclipse IDE installé  

### 🛠️ 2. Installation
Cloner le projet depuis GitHub :  
```sh
git clone https://github.com/BTS-SIO-projects/Morpion.git
cd Morpion
```

Importer le projet dans Eclipse :

Ouvrir Eclipse
Aller dans File → Import → Existing Projects into Workspace
Sélectionner le dossier du projet et valider
▶️ 3. Exécution
Lancer la classe principale Main.java
Ou exécuter la version .jar avec :
```sh
java -jar Morpion.jar
```

🤖 Mode Joueur vs Ordinateur
L’IA suit une logique simple basée sur des choix aléatoires et des blocages de coups gagnants. Une future amélioration pourrait intégrer l’algorithme Minimax pour un défi plus relevé.

📅 Équipe de développement
👨‍💻 Développé par une équipe de 4 élèves BTS SIO dans le cadre d’un projet scolaire.

📄 Documentation
👉 📑 [Vidéo explicative]()

Dépôt GitHub : Lien vers le [repository](https://github.com/BTS-SIO-projects/morpion)
