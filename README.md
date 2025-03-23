# Netflix-Clone

This is a Netflix clone website built using **React.js**, **Firebase**, and **The Movie Database (TMDB) API**. The website allows users to browse movies, view detailed information, and sign up or log in using Firebase authentication.

## Features

- **User Authentication**: Users can sign up and log in using Firebase Authentication.
- **Movie Browsing**: Browse popular movies, top-rated movies, and upcoming releases.
- **Movie Details**: View detailed information about movies, including ratings, release date, and overview.
- **Responsive Design**: The website is designed to be fully responsive, so it works on both desktop and mobile devices.

## Technologies Used

- **React.js**: JavaScript library for building the user interface.
- **Firebase**: Provides authentication (sign-up/sign-in functionality).
- **TMDB API**: Provides movie data, such as movie details, ratings, and images.

## Setup and Installation

### 1. Clone the repository
```bash
git clone https://github.com/vikas2309/Netflix-Clone.git
cd netflix-clone
```
### 2. Install dependencies
Ensure that you have Node.js installed. Then, run the following command to install the required dependencies:
```
npm install
```
### 3. Firebase Configuration
Create a Firebase project at Firebase Console if you don't already have one.

Go to the Firebase Console and create a new project.

Enable Firebase Authentication (Email/Password) under the Authentication section.

In the Firebase Console, get your Firebase configuration credentials and add them to your firebase.js file:
```
// firebase.js

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```
### 4. TMDB API Key
Create an account at The Movie Database (TMDB).

Go to the API section and generate an API key.

Add the API key to your project where API calls are made.

### 5. Start the project
Once everything is configured, run the following command to start the application locally:

```
npm start
```
Open http://localhost:3000 in your browser to see the app in action.
