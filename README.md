---

# 🎲 Quiz Interactif Arduino

Bienvenue dans le projet **Quiz Interactif Arduino**, un jeu éducatif et divertissant combinant électronique, programmation et design ! Conçu pour 1 à 4 joueurs, ce jeu repose sur un plateau interactif équipé de manettes à boutons lumineux, d'un écran LCD pour afficher les scores, et d'enceintes pour une immersion sonore.

## 🛠️ Caractéristiques du Projet

- **Écran LCD I2C** : Affiche les scores, instructions et messages.
- **Boutons Poussoirs à LED** : Indiquent les options de réponse (nombre de LEDs allumées selon les choix disponibles).
- **Manettes Détachables** : Se branchent au plateau et détectent automatiquement le nombre de joueurs.
- **Plateau Physique** : Permet d’avancer les pions en fonction des bonnes réponses.
- **Enceintes** : Diffusent vocalement les questions et les sons d'ambiance.
- **Deux Modes de Questions** :
  - **Tour par tour** : Chaque joueur répond à son tour.
  - **Question flash** : Récompense le joueur le plus rapide.

---

## 📋 Règles du Jeu

1. **Mise en Place** :
   - Connectez les manettes au plateau. Le nombre de joueurs est automatiquement détecté.
   - Sélectionnez un scénario (thème ou génération).
2. **Déroulement** :
   - L’Arduino pose une question via les enceintes.
   - Les LEDs des boutons poussoirs s’allument pour représenter les options (2, 3 ou 4 choix).
   - Les joueurs répondent en appuyant sur le bouton correspondant à leur réponse.
3. **Avancement** :
   - Bonne réponse : le joueur avance son pion sur le plateau, et son score est mis à jour.
   - Mauvaise réponse : aucun point n'est attribué.
4. **Fin de Partie** :
   - Le premier joueur à atteindre la dernière case remporte la partie.

---

## 🔧 Matériel Nécessaire

- **Arduino UNO** ou équivalent.
- **Écran LCD I2C** (16x2 recommandé).
- **Boutons poussoirs avec LEDs intégrées** (au moins 4 par joueur).
- **Câbles et connecteurs** pour les manettes.
- **Enceintes** ou un module de sortie audio.
- **Plaque pour le plateau** et accessoires pour les pions.

---

## 🚀 Installation et Utilisation

1. **Cloner le Répertoire :**
   ```bash
Bientôt
   ```

2. **Téléverser le Code sur l’Arduino :**
   - Ouvrez le fichier `.ino` dans l'IDE Arduino.
   - Sélectionnez le bon port COM et le modèle de carte.
   - Cliquez sur "Téléverser".

3. **Assembler le Matériel :**
   - Suivez le schéma fourni dans le dossier `/schematics`.

4. **Jouer :**
   - Allumez l’Arduino et suivez les instructions affichées sur l’écran LCD.

---

## 📂 Structure du Projet

```
Bientôt
```

---

## 🖼️ Aperçus

### Schéma du Câblage
Bientôt

### Prototype Final
Bientôt

---

## 🤝 Contributeurs

- **Dorian , Augustin, Nathan** - Concepteur principal et développeur.
- **Équipe Lycée Tocqueville STI2D** - Partenaires du projet.

---

## 📜 Licence

Ce projet est sous licence [MIT](LICENSE). Vous êtes libre de le modifier et de l’utiliser, mais veuillez créditer les auteurs originaux.

---
