# [LBK] Lootbags Magnet Mod

**Version : 1.0.0.1** 

---

## 📌 Description

Lootbags Magnet Mod est un mod pour **7 Days to Die** permettant de téléporter automatiquement les lootbags à proximité via un bloc spécifique.  
Lorsque ce bloc est activé, il scanne la zone et déplace les lootbags trouvés dans son rayon d’action, tout en déclenchant un **effet sonore customisé**.

---

## ⚡ Fonctionnalités

- ✅ **Activation/Désactivation** via le bloc dédié (toggle ON/OFF).  
- 🎯 **Téléportation** des lootbags détectés dans le rayon d'action.  
- 🔧 **Personnalisation du rayon d’action** via la propriété `MagnetRadius` dans blocks.xml.  
- 🔊 **Effet sonore** lors de l'activation du magnet.  
- 🔧 **Personnalisation du volume** via la propriété `runningvolumescale` dans le sounds.xml.  

---

## 🛠️ Installation

### Étapes :

1. **Télécharger le mod**  
   - Récupérez la dernière version via [le dépôt officiel](https://github.com/RyuuCreator/LBK-LootbagsMagnetMod).

2. **Copier les fichiers dans le dossier du jeu**  
   - `Steam\steamapps\common\7 Days To Die\Mods`

3. **Lancer le jeu**  
   - Le mod sera chargé automatiquement au démarrage.

---

## ⚙️ Configuration

### 📏 Ajuster le rayon d’action du magnet
Dans le fichier blocks.xml :
    ```
    <property name="MagnetRadius" value="50"/>
    ```

### 🔊 Configurer l’effet sonore
Dans le fichier sounds.xml :
    ``` 
    <runningvolumescale value="50"/>
    ```

---

## 🎮 Utilisation

1. **Activer/Désactiver le bags magnet**  
   - Utilisez le bloc spécifique pour **activer ou désactiver** la fonction de téléportation des lootbags.  
   - Lors de l’activation, le **scan démarre et se relance toute les 5min, le son se joue si un lootbags est à porté puis le téléporte**.

---

## 🚫 Droits d’auteur et conditions d’utilisation

Ce mod est **propriété exclusive** de **RyuuCreator**. 
Toute modification, redistribution ou utilisation à des fins commerciales **sans autorisation explicite** est **strictement interdite**.

- **Interdiction de modification** : Ce mod ne peut être modifié, altéré ou utilisé dans un projet dérivé sans accord préalable.  
- **Interdiction de redistribution** : Il est interdit de partager ou distribuer ce mod sur d’autres plateformes sans autorisation.  
- **Interdiction d’usage commercial** : Ce mod ne peut être vendu, utilisé dans des produits commerciaux ou monétisé d’aucune manière.  

Toute violation de ces termes peut entraîner des **sanctions légales** conformément aux lois sur la propriété intellectuelle.

---

## 🔧 Paramètres modifiables

Les utilisateurs **peuvent ajuster** les paramètres suivants pour personnaliser leur expérience sans modifier le code du mod :  
- **Rayon d’action** (`MagnetRadius`) : Peut être modifié dans le fichier XML du bloc (`blocks.xml`) pour ajuster la portée du bags magnet.  
- **Niveau du son** (`runningvolumescale`) : Peut être modifié dans le fichier XML du son (`sounds.xml`) pour adapter le volume selon les préférences du joueur.  

⚠️ **Aucune autre modification du mod n’est autorisée. Toute tentative de modification du code source ou redistribution du mod est interdite.**

---

## 💡 Remerciements

Merci à la communauté **Les Brakkass** pour le soutien et les retours constructifs.  
Si vous avez des idées ou suggestions, ouvrez une issue dans le dépôt officiel !

---

### ✨ Contact & Support
💬 Discord : [Lien vers le serveur](https://discord.gg/MYJz5tvzCf) <br/>
🛠️ GitHub : [Repo du projet](https://github.com/RyuuCreator/LBK-LootbagsMagnetMod)

---

### 🚀 Bon jeu et amusez-vous !
