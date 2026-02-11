# 🔗 QR Code Generator

Une application web ultra-légère pour générer et télécharger des QR Codes instantanément.

## 🚀 Aperçu
Ce projet propose une interface moderne en **Dark Mode** permettant de transformer n'importe quel lien URL en image QR Code haute résolution.

## ✨ Fonctionnalités
- 📥 **Génération en temps réel** : Transformez vos liens instantanément.
- 💾 **Téléchargement PNG** : Exportez votre QR Code pour vos supports physiques ou numériques.
- 🎨 **Design Moderne** : Interface épurée avec un thème sombre (Slate & Emerald).
- 📱 **Responsive** : Compatible avec tous les types d'écrans.

## 🛠️ Stack Technique
*   **Frontend** : HTML5 / CSS3 (Flexbox & Shadows).
*   **Logique** : JavaScript Vanilla.
*   **Moteur QR** : [QRCode.js](https://davidshimjs.github.io) via le [CDN jsDelivr](https://www.jsdelivr.com).

## 📖 Comment l'utiliser ?

1.  **Copiez le code** dans un fichier nommé `index.html`.
2.  **Ouvrez-le** avec votre navigateur (Chrome, Firefox, Safari).
3.  **Collez votre lien** dans le champ de saisie.
4.  Cliquez sur **Générer** puis sur **Télécharger**.

---

### 🔧 Personnalisation du code
Pour modifier la taille du QR Code, changez les valeurs `width` et `height` dans le script :
```javascript
qr = new QRCode(qrContainer, {
    text: link,
    width: 250,  // Modifiez la largeur ici
    height: 250, // Modifiez la hauteur ici
    colorDark: "#000000",
    colorLight: "#ffffff"
});
