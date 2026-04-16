// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyCNSzq8jMb8uk4hKjhotHB4b6QwJykbMyM",
  authDomain: "tambola-66a73.firebaseapp.com",
  databaseURL: "https://tambola-66a73-default-rtdb.firebaseio.com",
  projectId: "tambola-66a73",
  storageBucket: "tambola-66a73.firebasestorage.app",
  messagingSenderId: "516385519776",
  appId: "1:516385519776:web:bc1384b8d8be8ffb6a31c5",
  measurementId: "G-N6FEMDMT7N"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
