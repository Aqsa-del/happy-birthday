
# 🎂 Happy Birthday Interactive Website

Ek special interactive birthday surprise website jo 4 animated screens par banti hai.  
Password se unlock hoti hai aur end par cake blow karne ka maza bhi hai ✨

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## 🌟 Live Demo
**Link**: `https://your-project-name.vercel.app`  
*Deploy ke baad apna Vercel link yahan daal dena*

## ✨ Features
- **🔒 Screen 1: Secret Password**  
 4-digit PIN se unlock hoti hai. Galat PIN par shake animation.
- **💌 Screen 2: Love Letter**  
  Custom letter + 3 memory photos ke saath. Name bhi add kar sakte ho.
- **🎂 Screen 3: Birthday Cake**  
  Candles par click karke blow karo ya button dabao.
- **🎉 Screen 4: Final Celebration**  
  Confetti + Blur to Clear "Happy Birthday" animation.
- **📱 100% Responsive**  
  Mobile, Tablet, Desktop sab par perfect chalti hai.
- **🎨 Easy Customization**  
  Bina code samjhe naam, photos, text, password change kar sakte ho.

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Fonts**: Google Fonts - Great Vibes, Cormorant Garamond, Poppins
- **Hosting**: Vercel
- **No Backend Required**

## ⚙️ Kaise Customize Karein?

`index.html` file open karo aur sabse neeche `CONFIG` section mein changes karo:

```javascript
const CONFIG = {
  password: "1234", // Apna password yahan
  recipientName: "Ayesha", // Jis ka birthday hai uska naam
  cardImage: "https://your-image-link.jpg", // Card wali photo
  memoryImages: [
    "https://photo1.jpg", // Memory 1
    "https://photo2.jpg", // Memory 2  
    "https://photo3.jpg"  // Memory 3
  ],
  letterText: {
    title: "Birthday",
    body: [
      "Line 1 of your letter",
      "Line 2 of your letter",
      "Line 3 of your letter"
    ]
  },
  signature: "— with love ❤️", // Signature
  wishSubtitle: "tap the candles to blow them out ♡",
  finalHeading: { line1: "Happy Birthday", line2: "to You!" }
};vvv
