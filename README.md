# CoinsKite Chat App

### This Chat App is Made Using React Native , Firebase With GiftedChat

### Installing

> Clone This Repo To Your PC 

> Run npm install

> TODO

> Run The App

## TODO 

* Follow The Installation at https://github.com/react-native-community/google-signin

* Get WebClientID ( Login Page )

```javascript
GoogleSignin.configure({
   scopes: ["https://www.googleapis.com/auth/userinfo.profile"],
   webClientId: '******', // TODO : Get WebClient ID From Firebase By Enabling Google SIGN In
   offlineAccess: true, // if you want to access Google API on behalf of the user FROM YOUR SERVER
   forceCodeForRefreshToken: true, // [Android] related to `serverAuthCode`, read the docs link below *.
 });
```

* Firebase Configuration's ( Fire.js )

```javascript
firebase.initializeApp({
   apiKey: "***",
   authDomain: "***",
   databaseURL: "***",
   projectId: "***",
   storageBucket: "***",
   messagingSenderId: "***",
   appId: "***",
   measurementId: "***"
 });
```

## Built With

* React Native
* react-native-firebase
* react-native-gifted-chat
* react-native-community/google-signin

## Sample Preview

<img src="https://user-images.githubusercontent.com/61349423/94794860-1ab97080-03fa-11eb-8e87-eba1c55b8a4b.jpg" width="282" height="501">

## Problems ?

* Contact Me At [Instagram - @coinskite](https://www.instagram.com/coinskite/)

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

## Hire Us 

* [Website](https://coinskite.com/)
* [Instagram](https://www.instagram.com/coinskite/)

