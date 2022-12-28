# FosterYouth
Final Project of Snap Academies 2022

<img src="https://github.com/sonyakim-dev/git-practice/blob/main/youbelong-title-small.png?raw=true" width="500"/>

Our team found that foster youth have incredible stories to share, but no platform that nurtures a sense of community. YouBelong is a Snap Mini platform that fosters an environment of authenticity, self-expression, and happiness. We used React Native for the front end and Firebase to store images and videos for the backend.

## Our Team

Developers - [Raina Wan](https://www.linkedin.com/in/raina-wan-profile/), [Soyeon Kim](https://www.linkedin.com/in/sonya-kim/)

Designers - [Daisy Gomez](https://www.linkedin.com/mwlite/in/daisy-gomez-84040b237), [Maria Garsa](https://www.linkedin.com/mwlite/in/maria-garsa-28b19b1a5)

Marketers - [Franky Calamateos](https://www.linkedin.com/mwlite/in/fcalamateos), [Tyler Cooper](https://www.linkedin.com/mwlite/in/tyler-cooper-711a71243)

## Run Project

1. In terminal, run the following command:
  ```
  git clone https://github.com/rainawan/FosterYouth.git
  ```
  ```
  cd FosterYouth
  ```
  ```
  yarn install
  ```
  ```
  expo start --tunnel
  ```
2. Add Firebase config file as `firebase.js` in root
  ```js
import { initializeApp } from "firebase/app";
import { getFirestore } from "firebase/firestore";

const firebaseConfig = {
  // config here
};

const app = initializeApp(firebaseConfig);
const db = getFirestore(app);

export default db;
  ```
4. Download Expo Go on your mobile device (https://expo.dev/client)
5. Scan the QR code in terminal, using your mobile device camera

## App Experience

~ | The Spot | Camera | Resources
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
**Samples** | <img src="https://github.com/sonyakim-dev/git-practice/blob/main/foster-youth-thespot-small.gif?raw=true" width="180"/> | <img src="https://github.com/sonyakim-dev/git-practice/blob/main/sonya-small.gif?raw=true" width="180"/> | <img src="https://github.com/rainawan/FosterYouth/blob/a66864239ee392d944f243df31e0ce579b3506a6/assets/snapchat/resources.gif?raw=true" width="180"/>

## Accessibility

~ | Sign Up/Sign In | Intro | Facility Authentication
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
**Samples** | <img src="https://github.com/sonyakim-dev/git-practice/blob/main/foster-youth-login.gif?raw=true" width="180"/> | <img src="https://github.com/rainawan/FosterYouth/blob/a66864239ee392d944f243df31e0ce579b3506a6/assets/snapchat/intro.gif?raw=true" width="180"/> | <img src="https://github.com/rainawan/FosterYouth/blob/9180e0bddc2d1ecf9d5cd018330064c55b7ad1ed/assets/snapchat/facility.gif?raw=true" width="180"/>

## Figma Design Process

[Drafting Prototype](https://www.figma.com/file/MdDWF9tGsIiUPTUQWCoFYG/Prototype-%7C-Snap-Academies?node-id=0%3A1)
[Final Prototype](https://www.figma.com/file/MdDWF9tGsIiUPTUQWCoFYG/Prototype-%7C-Snap-Academies?node-id=154%3A8735)

## Demo Video

[YouTube Video](https://youtu.be/xCRQtvLTHfc)

## Tools Used

1. React Native (https://reactnative.dev/)
2. Expo (https://expo.dev/)
3. Expo Camera (https://docs.expo.dev/versions/latest/sdk/camera/)
4. Expo AV (https://docs.expo.dev/versions/v46.0.0/sdk/av/)
5. Expo ImagePicker (https://docs.expo.dev/versions/latest/sdk/imagepicker/)
6. React Navigation (https://reactnavigation.org/)
7. Google Firebase Firestore (https://firebase.google.com/docs/firestore)
8. Google Firebase Storage (https://firebase.google.com/docs/storage)
9. Google Firebase Authentication (https://firebase.google.com/docs/auth)
