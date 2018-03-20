# Mars Rover

#### _An app that returns photos from the Mars Rover API, 11.06.2017_

#### By _**Margaret Berry**_

## Description
_This application allows the user to select a date and Mars Rover camera and see photos from that date taken with that camera. Users can also save photos they like to a Firebase database._

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Project Goals
* Make an API call in an Angular CLI application.
* Use a web API with Firebase.

## Setup/Installation Requirements
_Run the following commands in Terminal:_

1. `$ git clone` [this repository](https://github.com/codemargaret/mars-rover.git)
2. `$ cd mars-rover`
3. `$ npm install`
4. `$ bower install`
5. _Firebase setup:_
  * _Go to [firebase](https://console.firebase.google.com) and login or create a free account._
  * _Create a project called 'mars-rover'._
  * _Click 'add firebase to your web app'._
  * `$ touch src/app/api-keys.ts`
  * _Add the following code and replace the x's with your information:_
    - `export const marsRoverKey = "xxxx";
    export const config = {
    apiKey: "xxxx",
    authDomain: "xxxx.firebaseapp.com",
    databaseURL: "https://xxxx.firebaseio.com",
    projectId: "xxxx",
    storageBucket: "",
    messagingSenderId: "xxxx" };`
  * _Visit the Firebase console, click 'mars-rover,' and click the database option from the navbar on the lefthand side of the menu._
  * _Click the blue navbar 'Realtime Database,' then 'Rules.' Set the value of .read and .write to 'true' and click 'publish.'_
6. `$ ng serve`
7. _Navigate to localhost:4200_

## Known Bugs
_There are no known bugs at this time._

## Support and contact details
_If you have issues, questions, ideas, or concerns, please contact [Margaret](codeberry1@gmail.com). Feel free to make a contribution to the code._

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Technologies Used
* _JavaScript_
* _TypeScript_
* _Node_
* _Bower_
* _Angular CLI_
* _Firebase_

### License
*This software is licensed under the MIT license.*

Copyright (c) 2017 **_Margaret Berry_**
