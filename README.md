# Flutter Firebase Auth Example

This is a simplified version of the example app provided with the [firebase\_ui\_auth](https://github.com/firebase/flutterfire/tree/master/packages/firebase_ui_auth) package.

This app only provides code to support email signin.

This code illustrates the basic design pattern for the Firebase_ui_auth package. This package provides some prebuilt "screens" (widgets): [SignInScreen], [EmailVerificationScreen], [ForgotPasswordScreen], and [ProfileScreen]. You can customize the presentation of these widgets to follow your design theme. 

Each of these screens take an "actions" parameter to which you can supply an [AuthStateChangeAction] in order to control what happens when a particular state in the authorization workflow occurs. For example, when the user successfully signs in with a verified email address, you probably want them to go to some sort of "home" page. The example app shows how you can use actions to navigate to various pages based upon the state of authorization. 

## Screenshots

Normal signin with a pre-existing verified account takes you to the profile screen:

<p style="text-align: center">
  <img src="https://github.com/philipmjohnson/flutter_firebase_auth_example/raw/main/README-signin.png" width="45%">
&nbsp; &nbsp; 
  <img src="https://github.com/philipmjohnson/flutter_firebase_auth_example/raw/main/README-profile.png" width="45%">
</p>

If you don't have an account, you go to the register screen. After filling it out, you have to wait to receive an email to verify your email address:

<p style="text-align: center">
  <img src="https://github.com/philipmjohnson/flutter_firebase_auth_example/raw/main/README-register.png" width="45%">
&nbsp; &nbsp; 
  <img src="https://github.com/philipmjohnson/flutter_firebase_auth_example/raw/main/README-verify-email.png" width="45%">
</p>

You'll receive an email like the following. After clicking the link, you get an indication that the email was verified:

<p style="text-align: center">
  <img src="https://github.com/philipmjohnson/flutter_firebase_auth_example/raw/main/README-email-verified-browser.png" width="45%">
&nbsp; &nbsp; 
  <img src="https://github.com/philipmjohnson/flutter_firebase_auth_example/raw/main/README-email-verified-browser.png" width="45%">
</p>


## Installation

Download this source code.

Follow the instructions in [Firestore Setup Cheat Sheet](https://courses.ics.hawaii.edu/mobile-application-development/morea/data/reading-firestore-setup-cheat-sheet.html) to setup a Firestore database for this app.

Run the app.
