

[![Netlify deploy](https://api.netlify.com/api/v1/badges/c6f44d34-0570-4ca0-9d3d-cabdaa2b3afb/deploy-status)](https://chat-hub.rohan.ml)

# Chat-Hub

Chat-Hub is a free open source chat room built with React Js with Firebase as the backend.

### Live Demo:

Website Link 👉 [Click Me](https://chat-hub.rohan.ml)

### Screenshots :

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/j0isihn4ve2ecz41njyv.jpg)
---

### Installation :

1. Run this on local machine ? 

    Clone this repository 
    ```
     git clone https://github.com/amrohan/Chat-Hub
    ```

2. Install all packages :

    `npm install or yarn install` 

3. Runs the app in the development mode.

    `npm start`

    Open `http://localhost:3000` to view it in the browser.

4. Create a firebase web app and a firebase store database, then paste the firebase config token into [`firebase-chat/src/App.js`](src/App.js#L12)

    ```jsx

    firebase.initializeApp({  
    apiKey: "process.env.TOKEN_SECRET",  
    authDomain: "process.env.TOKEN_SECRET",  
    projectId: "process.env.TOKEN_SECRET",  
    storageBucket:"process.env.TOKEN_SECRET",  
    messagingSenderId:"process.env.TOKEN_SECRET",  
    appId:"process.env.TOKEN_SECRET",  
    measurementId: "process.env.TOKEN_SECRET"
    })
    } 
    ```

5. Deploy it on any of your favourite website hosting services.
    1. [Netlify](https://netlify.com)
    2. [Vercel](https://vercel.com)
    3. [Cloudflare Pages](https://pages.cloudflare.com/) 
    4. [Firebase hosting](https://firebase.google.com/) 
    5. [Render](https://render.com/)
    ---

Enjoy everything is working now ✨

