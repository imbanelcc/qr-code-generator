# 🔗 QR Code Generator

Une application web ultra-légère pour générer et télécharger des QR Codes instantanément.

## 🚀 Accès Direct
Pas besoin d'installation ! Vous pouvez utiliser l'outil directement en ligne ici :  
👉 **[https://imbanelcc.github.io/qr-code-generator/](https://imbanelcc.github.io/qr-code-generator/)**

## ✨ Fonctionnalités
- 📥 **Génération en temps réel** : Transformez vos liens instantanément.
- 💾 **Téléchargement PNG** : Exportez votre QR Code pour vos supports physiques ou numériques.
- 🎨 **Design Moderne** : Interface épurée avec un thème sombre (Slate & Emerald).
- 📱 **Responsive** : Compatible avec tous les types d'écrans.

## 🛠️ Stack Technique
*   **Frontend** : HTML5 / CSS3 (Flexbox & Shadows).
*   **Logique** : JavaScript Vanilla.
*   **Moteur QR** : [QRCode.js](https://davidshimjs.github.io) via le [CDN jsDelivr](https://www.jsdelivr.com).

## 📖 Utilisation Locale

Si vous souhaitez l'héberger vous-même ou modifier le code :

1.  **Copiez le code** dans un fichier nommé `index.html`.
2.  **Ouvrez-le** avec votre navigateur (Chrome, Firefox, Edge).
3.  **Collez votre lien** dans le champ de saisie.
4.  Cliquez sur **Générer** puis sur **Télécharger**.

---

### 🔧 Personnalisation
Pour modifier la taille du QR Code, ajustez les paramètres dans la fonction `generateQR()` :
```javascript
qr = new QRCode(qrContainer, {
    text: link,
    width: 200,  // Modifier la largeur
    height: 200, // Modifier la hauteur
    colorDark: "#000000",
    colorLight: "#ffffff"
});
