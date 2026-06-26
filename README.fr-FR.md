# LBK Lootbags Magnet Mod ![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/RyuuCreator/LBK-Lootbags-Magnet-Mod/total?label=t%C3%A9l%C3%A9charger&color=%23950000)
**Version: 3.0.0.2** 

---

## 📌 Description

Lootbags Magnet Mod est un mod pour **7 Days to Die** qui permet de téléporter automatiquement les lootbags à proximité via un bloc spécifique.  
Lorsque ce bloc est activé, il scanne la zone immédiatement puis toutes les 5 minutes, et déplace les lootbags trouvés dans son rayon d’action, tout en déclenchant un **effet sonore customisé**.  
> **Note :** Une fois qu'un lootbag a été aspiré, il ne sera pas aspiré à nouveau tant que le bloc n'a pas été désactivé puis réactivé.

---

## ⚡ Fonctionnalités

- ✅ **Activation/Désactivation** via le bloc dédié (toggle ON/OFF).  
- 🎯 **Téléportation** des lootbags détectés dans le rayon d'action.  
- 🔧 **Personnalisation du rayon d’action** via la propriété `MagnetRadius` dans blocks.xml.  
- 🔊 **Effet sonore** lors de l'activation du magnet.

---

## 🛠️ Installation

### Étapes :

1. **Télécharger le mod**  
   - Récupérez la dernière version via [la Releases](https://github.com/RyuuCreator/LBK-Lootbags-Magnet-Mod/releases).

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

---

## 🎮 Utilisation

1. **Activer/Désactiver le Bags Magnet**
   - Utilisez le bloc spécifique pour **activer ou désactiver** la fonction de téléportation des lootbags.
   - Lors de l’activation, le **scan démarre et se relance toutes les 5 minutes**. Si un lootbag est à portée, un son se joue puis il est téléporté.
   - Une fois qu’un lootbag a été téléporté, le bloc ne le re-téléportera plus tant que le bloc n’aura pas été désactivé puis réactivé.

2. **Ramasser le Bags Magnet**
   - Lorsque le joueur frappe le bloc, celui-ci est détruit en un coup et **le ramasse**.
     
---

## 🚫 Droits d’auteur et conditions d’utilisation

Ce mod est **propriété exclusive** de **RyuuCreator**. Ce mod est destiné à la communauté **LBK Les Brakass**.

Toute modification, redistribution ou utilisation à des fins commerciales **sans autorisation explicite** est **strictement interdite**.

- **Interdiction de modification** : Ce mod ne peut être modifié, altéré ou utilisé dans un projet dérivé sans accord préalable.  
- **Interdiction de redistribution** : Il est interdit de partager ou distribuer ce mod sur d’autres plateformes sans autorisation.  
- **Interdiction d’usage commercial** : Ce mod ne peut être vendu, utilisé dans des produits commerciaux ou monétisé d’aucune manière.  

Toute violation de ces termes peut entraîner des **sanctions légales** conformément aux lois sur la propriété intellectuelle.

---

## 🔧 Paramètres modifiables

Les utilisateurs **peuvent ajuster** les paramètres suivants pour personnaliser leur expérience sans modifier le code du mod :  
- **Rayon d’action** (`MagnetRadius`) : Peut être modifié dans le fichier XML du bloc (`blocks.xml`) pour ajuster la portée du bags magnet.

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
