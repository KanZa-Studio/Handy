![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/yusubx/Handy/Flutter%20CI/master)
![GitHub forks](https://img.shields.io/github/forks/yusubx/Handy)
![GitHub stars](https://img.shields.io/github/stars/yusubx/Handy)
![GitHub watchers](https://img.shields.io/github/watchers/yusubx/Handy)
![GitHub contributors](https://img.shields.io/github/contributors/yusubx/Handy)
![GitHub last commit](https://img.shields.io/github/last-commit/yusubx/Handy)
![GitHub top language](https://img.shields.io/github/languages/top/Kanza-Studio/Handy)

# Handy

<img src="art/run.jpeg"/>

-------

## Configuration for yourself

This project contains `google-services.json` file of my own. You can connect your own firebase project using the following configrations:

> Please, keep patient and follow the configrations correctly!

**Step 1:** Clone the repository to your device.

**Step 2:** Open `android/app/build.gradle` and change `applicationId` as you want: 

![Step 2](configuration-steps/step-2.PNG)

**Step 3:** Create firebase project and add new android project to firebase.

**Step 4:** Write the `same applicationId` to the `android package name` field:

**Step 5:** Open the `android` directory of `Handy` using Android Studio:

![Step 5](configuration-steps/step5.PNG)

**Step 6:** Tap to `Gradle` from the right side and select `android/app/Tasks/android/signingReport` and wait a bit to get `SHA1` key:

![Step 6](configuration-steps/step6.PNG)

**Step 7:** Copy `SHA1` from terminal:

![Step 7](configuration-steps/step7.PNG)

**Step 8:** Paste to `Debug signing certificate SHA-1` field in `Firebase` and click to `Register` button:

![Step 8](configuration-steps/step8.PNG)

**Step 9:** Download `google-services.json` and click to next button:

![Step 9](configuration-steps/step9.PNG)

**Step 10:** Replace file of `Handy` that is stored in `android/app/` called `google-services.json` with your own `google-services.json` file that you downloaded in the previous step:

![Step 10](configuration-steps/step10.PNG)

**Step 11:** Click `Next` and `Skip` button in the next steps:

![Step 11-1](configuration-steps/step11-1.PNG)

![Step 11-2](configuration-steps/step11-2.PNG)

**Step 12:** Go to `Authentication` screen and enable `Email/Password` and `Google` authentication:

![Step 12](configuration-steps/step12.PNG)



[App Design](http://bit.ly/handyappdesign)

## Maintainers
[Kanan Yusubov](https://github.com/yusubx)

