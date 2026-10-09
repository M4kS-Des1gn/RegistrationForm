# Registration Form App

## Description

Registration Form is a simple Android application developed in Java using Android Studio. It allows users to enter their personal information through a registration form and view the submitted details in a pop-up dialog.

The application demonstrates basic Android UI components, retrieving user input, handling button clicks, and displaying information using an `AlertDialog`.

## Features

* Enter a username and full name.
* Enter country, email address, and phone number.
* Enter a password.
* Select gender (Male or Female).
* Accept or decline the terms and conditions using a checkbox.
* Display all entered information in a registration details dialog.

## Technologies Used

* **Language:** Java
* **IDE:** Android Studio
* **Platform:** Android
* **UI Layout:** XML
* **Main Activity:** `MainActivity.java`
* **Layout File:** `activity_main.xml`

## Project Structure

```text
RegistrationForm/
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── com/example/registrationform/
│           │       └── MainActivity.java
│           ├── res/
│           │   └── layout/
│           │       └── activity_main.xml
│           └── AndroidManifest.xml
├── build.gradle
└── README.md
```

## How to Use

1. Open the application on an Android device or emulator.
2. Enter your registration information in the provided fields.
3. Select your gender.
4. Choose whether to accept the terms and conditions.
5. Press the **Create Account** button.
6. Review the entered information in the **Registration Details** dialog.
7. Press **OK** to close the dialog.

## How It Works

The `MainActivity` class connects the Java code to the XML layout using `setContentView()` and `findViewById()`.

When the user presses the **Create Account** button, the application:

1. Reads the values from the input fields.
2. Determines the selected gender.
3. Checks whether the terms and conditions checkbox is selected.
4. Combines the collected information into a formatted string.
5. Displays the information in an `AlertDialog`.

## Limitations

* The application does not save registration information permanently.
* Input validation is not implemented.
* The application does not create a real user account.
* Passwords are displayed as plain text in the dialog.
* Acceptance of the terms and conditions is recorded but not enforced.

## Future Improvements

* Add input validation for required fields and email format.
* Require users to accept the terms and conditions before proceeding.
* Add secure account creation and database storage.
* Avoid displaying passwords in plain text.
* Add password visibility controls and improved error messages.

## Author

Created as an Android Studio learning project to practice Java programming and Android user interface development.
