
# Netflix Clone
🌟 **Netflix Clone Project** 🌟

Welcome to the Netflix Clone project! This is a full-featured clone of Netflix built with React, Firebase, and Firebase Authentication. It provides a seamless video streaming interface with user authentication and real-time database integration.

## 🖼 Screenshots
Here are a few screenshots showcasing the app's user interface:

**🖼Home Page**  
![Preview](netflix-preview.png?raw=true)

**🖼Browse Movies Page**  
![Preview](netflix-drillmovie-preview.png?raw=true)

**🖼Sign In Page**  
![Preview](netflix-signin-preview.png?raw=true)

**🖼Sign Up Page**  
![Preview](netflix-signup-preview.png?raw=true)

**🖼Select Account Page**  
![Preview](netflix-accounts-preview.png?raw=true)



## 🚀 Tech Stack

### Frontend  
🟢 **React** - A JavaScript library for building user interfaces.

### Backend  
🔴 **Firebase** - Backend-as-a-Service for authentication, real-time database, and hosting.

### Routing  
🔵 **React Router** - For seamless client-side navigation.

### Styling  
🟣 **Styled Components** - For writing modern CSS inside JavaScript.

---

## 📦 Setup Instructions

### Clone the repository
```bash
git clone https://github.com/Deepak-Vasoya/Netflix-Clone-React-Firebase
cd netflix-clone
```

### Install dependencies
```bash
npm install
```

### Run the app
To run the app locally, use the following command:
Using NPM:
```bash
npm start
```
This will open the app in your browser at [http://localhost:3000](http://localhost:3000).

---

## 🔧 Firebase Setup

### Create a Firebase Project

1. Go to the **Firebase Console**.
2. Create a new project.
3. Enable **Email/Password Authentication** under **Authentication > Sign-in method**.

### Set up Firestore Database

1. In the Firebase Console, navigate to **Firestore Database**.
2. Create a new Firestore database in **Test Mode** for development.

### Get Your Firebase Config

From **Project Settings > General**, copy your Firebase configuration and paste it in your project file **src\lib\firebase.prod.js** and update the following code:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};

---

## 🧪 Running Tests

To run the tests, first ensure you've installed all the necessary dependencies:
Using NPM:

```bash
npm install
```

Then, you can run the tests with:
Using NPM:
```bash
npm test
```

The test results will be displayed in the terminal.
---


---

## 👨‍💻 Contributing

I welcome contributions! If you’d like to contribute, follow these steps:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them.
- Push your branch and create a pull request.

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

---

## 📚 Resources

**React**  
📘 React Docs: [https://reactjs.org/docs](https://reactjs.org/docs)

**Firebase**  
📘 Firebase Docs: [https://firebase.google.com/docs](https://firebase.google.com/docs)

---

## Folder Structure

```
├── app.js
├── global-styles.js
├── index.js
├── logo.svg
├── seed.js
├── components
│   ├── index.js
│   ├── accordion
│   │   ├── index.js
│   │   └── styles
│   │       └── accordion.js
│   ├── card
│   │   ├── index.js
│   │   └── styles
│   │       └── card.js
│   ├── feature
│   │   ├── index.js
│   │   └── styles
│   │       └── feature.js
│   ├── footer
│   │   ├── index.js
│   │   └── styles
│   │       └── footer.js
│   ├── form
│   │   ├── index.js
│   │   └── styles
│   │       └── form.js
│   ├── header
│   │   ├── index.js
│   │   └── styles
│   │       └── header.js
│   ├── jumbotron
│   │   ├── index.js
│   │   └── styles
│   │       └── jumbotron.js
│   ├── loading
│   │   ├── index.js
│   │   └── styles
│   │       └── loading.js
│   ├── opt-form
│   │   ├── index.js
│   │   └── styles
│   │       └── opt-form.js
│   ├── player
│   │   ├── index.js
│   │   └── styles
│   │       └── player.js
│   ├── profiles
│   │   ├── index.js
│   │   └── styles
│   │       └── profiles.js
├── constants
│   └── routes.js
├── containers
│   ├── browse.js
│   ├── faqs.js
│   ├── footer.js
│   ├── header.js
│   ├── jumbotron.js
│   ├── profiles.js
├── context
│   └── firebase.js
├── fixtures
│   ├── faqs.json
│   └── jumbo.json
├── helpers
│   └── routes.js
├── hooks
│   ├── index.js
│   ├── use-auth-listener.js
│   └── use-content.js
├── lib
│   └── firebase.prod.js
├── pages
│   ├── browse.js
│   ├── home.js
│   ├── index.js
│   ├── signin.js
│   └── signup.js
├── utils
│   ├── index.js
│   └── selection-filter.js
├── __tests__
│   ├── components
│   │   ├── accordion.test.js
│   │   ├── card.test.js
│   │   ├── feature.test.js
│   │   ├── footer.test.js
│   │   ├── form.test.js
│   │   ├── header.test.js
│   │   ├── jumbotron.test.js
│   │   ├── loading.test.js
│   │   ├── opt-form.test.js
│   │   ├── player.test.js
│   │   ├── profiles.test.js
│   │   └── __snapshots__
│   │       ├── accordion.test.js.snap
│   │       ├── card.test.js.snap
│   │       ├── feature.test.js.snap
│   │       ├── footer.test.js.snap
│   │       ├── form.test.js.snap
│   │       ├── header.test.js.snap
│   │       ├── jumbotron.test.js.snap
│   │       ├── loading.test.js.snap
│   │       ├── opt-form.test.js.snap
│   │       ├── player.test.js.snap
│   │       ├── profiles.test.js.snap
│   ├── containers
│   │   └── profiles.test.js
│   ├── pages
│   │   ├── browse.test.js
│   │   ├── home.test.js
│   │   ├── signin.test.js
│   │   └── signup.test.js
│   └── utils
│       └── selection-filter.test.js
```
