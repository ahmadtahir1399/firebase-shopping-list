<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,55:1c1d20,100:0c63e7&height=170&section=header&text=Shopping%20List&fontSize=48&fontColor=fcfaf8&fontAlignY=38&desc=Real-time%20sync%20with%20Firebase&descAlignY=60&descSize=16" width="100%" alt="Shopping List" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

## ✨ About

A shopping list that syncs in real time across devices through the **Firebase Realtime Database**. Add an item on your phone and it appears on your laptop right away. It's built with plain JavaScript and the Firebase v9 modular SDK loaded from the CDN, so there's no build step.

## 🔋 Features

- ➕ Add items (empty input is rejected)
- ⚡ Live updates with Firebase `onValue` listeners
- 🗑️ Delete items with a confirmation popup
- 📭 "No items" state when the list is empty

## 🛠️ Tech stack

HTML5 · CSS3 · JavaScript (ES modules) · Firebase Realtime Database (v9 SDK)

## 🚀 Getting started

```bash
git clone https://github.com/ahmadtahir1399/firebase-shopping-list.git
cd firebase-shopping-list
```

To use your own database, create a Firebase project with a Realtime Database and replace `databaseURL` in `index.js`. Then serve the folder, since ES modules need a server:

```bash
npx serve .
```

## 👤 Author

**Muhammad Ahmad Tahir** · [Portfolio](https://ahmadverse.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/ahmad-ai-enginner/) · [GitHub](https://github.com/ahmadtahir1399)
