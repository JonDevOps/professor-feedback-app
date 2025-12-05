Thisapp is no longer being maintained. To ssee the finished repo along with a video explaining the process lookup https://github.com/jondevops/formApp




# professor-feedback-app
Create a Project: Go to the Firebase Console. Click Add project. Name it (e.g., professor-feedback-app).

Register the App: Click the Web icon (</>). Give it a nickname. Check the box for "Also set up Firebase Hosting." Click Register.

Grab the Config: You will see a firebaseConfig object. Copy this. We will need it shortly.




// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
const firebaseConfig = {
  apiKey: "AIzaSyApqEn-3J7iU6X5aOD2r2GwQAj8-lzExRE",
  authDomain: "professor-feedback-app.firebaseapp.com",
  projectId: "professor-feedback-app",
  storageBucket: "professor-feedback-app.firebasestorage.app",
  messagingSenderId: "917485594286",
  appId: "1:917485594286:web:23f6a682842bce4347ef3f"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);



