Movies list from tmdb api
api_key= 1499c7216a6e9e589326c94f29f7cfc2

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyC_HRcUCfpa6X2OActFKQ4IGuTp7Bh4yCk",
  authDomain: "movieslist-5fd94.firebaseapp.com",
  projectId: "movieslist-5fd94",
  storageBucket: "movieslist-5fd94.appspot.com",
  messagingSenderId: "830503972560",
  appId: "1:830503972560:web:04e6202b7ad58bb5d238d5",
  measurementId: "G-S3T5XNTYB2"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);