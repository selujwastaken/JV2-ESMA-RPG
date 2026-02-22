Voici une version **simple**, **sans emoji**, et **copiable-collable**, reformulée en Markdown.

---

# Description du jeu

Vous devez défendre votre village contre une attaque de slimes.  
Vous êtes le seul à disposer d’un RPG et de pièges.  
Utilisez vos compétences de combattant pour protéger votre village ainsi que le roi.

---

# Difficultés rencontrées

- Le code de la roquette Spike a été difficile à mettre en place.  
- La gestion de la TNT a également posé des problèmes techniques.

---

# Inputs

### Déplacements
- Déplacement principal : clic droit maintenu  
- Déplacement secondaire : ZQSD ou WASD  

### Caméra et menus
- Tourner la vue de 90° : `<` et `>`  
- Menu secondaire : TAB, ÉCHAP  

### Interactions et actions
- Interaction avec les objets : F  
- Tir / Shoot : clic gauche  

### Gestion des roquettes
- Roquette suivante : E  
- Roquette précédente : Q ou A  

# Autres informations

## TNT Barrels

- Les TNT explosent et infligent des dégâts autour d’elles.  
- Si plusieurs TNT sont proches, elles explosent en chaîne.  
- Plus les TNT sont proches les unes des autres, plus elles explosent rapidement.

---

## Bear Trap

- Lorsque le SKM de l’IA marche dessus, le piège s’active.  
- Le piège bloque l’IA pendant un certain nombre de secondes.

---

## Shop

- Certains objets ne peuvent être achetés qu’une seule fois.  
- Une fois achetés, le bouton "Buy" disparaît.

---

## Player House

- Vous pouvez passer la nuit lorsque tous les monstres ont été éliminés.  
- Si vous possédez des coffres, ils s’ouvrent automatiquement avant de passer la nuit.

---

## Shader

Un shader modifie la couleur des objets, ennemis, NPC et du joueur lorsqu’un mesh les cache.

- Joueur : blanc  
- Objets : orange  
- NPC : bleu  
- Ennemis : rouge

---

## Les fins

Il existe trois fins possibles :

1. Le roi est mort  
2. Le joueur est mort  
3. Le village est sauvé

---

## UI

- Des flèches indiquent la position des ennemis non visibles à l’écran. Elles apparaissent toujours sur les bords.  
- Les contrôles affichés dans les informations sont dynamiques : ils changent automatiquement si le joueur modifie ses touches à tout moment.
