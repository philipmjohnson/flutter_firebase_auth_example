# Flutter Firebase Auth Example

This is a simplified version of the example app provided with the [firebase\_ui\_auth](https://github.com/firebase/flutterfire/tree/master/packages/firebase_ui_auth) package.

This app only provides code to support email signin.

This code illustrates the basic design pattern for the Firebase_ui_auth package. This package provides some prebuilt "screens" (widgets): [SignInScreen], [EmailVerificationScreen], [ForgotPasswordScreen], and [ProfileScreen]. You can customize the presentation of these widgets to follow your design theme. 

Each of these screens take an "actions" parameter to which you can supply an [AuthStateChangeAction] in order to control what happens when a particular state in the authorization workflow occurs. For example, when the user successfully signs in with a verified email address, you probably want them to go to some sort of "home" page. The example app shows how you can use actions to navigate to various pages based upon the state of authorization. 

## Screenshots

###  Signin and registration

<p style="text-align: center">
  <img src="./README-screenshots/splash.png" width="45%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/signin.png" width="45%">
</p>

## Installation

Download this source code.

Follow the instructions in [Firestore Setup Cheat Sheet](https://courses.ics.hawaii.edu/mobile-application-development/morea/data/reading-firestore-setup-cheat-sheet.html) to setup a Firestore database for this app.

Run the app.
