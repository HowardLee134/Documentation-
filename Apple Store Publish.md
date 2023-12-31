# Unity Game App Store Submission Guide
## Date Created: Dec. 2023

## Preparation and Configuration

### Step 1. Prerequisites
- Check the Info on [App Store submission requirement](https://developer.apple.com/news/?id=jd9wcyov) to make sure your Mac device is capabale. 
- A Mac computer running macOS with the latest updates installed.
- An Apple Developer account [Apple Developer](https://developer.apple.com/)(Cube Software Team already have an account).
- Unity Hub and Unity Editor.

### Step 2. Set Up Your Unity Project

1. Configure your Unity project for iOS development:
   - Go to "File" -> "Build Settings."
   - Select "iOS" as the platform.
   - Configure the following settings under the "Player Settings" section:
     - Product Name: Your game's name.
     - Company Name: Your company's name.
     - Bundle Identifier: A unique reverse-domain identifier (e.g., com.yourcompany.yourgame).
     - Version and Build Numbers: Update these appropriately(make sure update everytime before you build).
     - App Icons: Add your app icons Image.
       ![PlayerSettingIcon](AppleDocumentation/playerSettingIcon.jpg)

   - Following the Image for Unity API choose any selection
    ![PlayerSettingIcon](AppleDocumentation/playerSetting.jpg)

2. Building Your Game

   - Return to the "Build Settings" window in Unity.
   - Click "Build" or "Build and Run" to generate an Xcode project.
   - Choose a location to save the Xcode project(Highly recommend to create a new IOS build folder in your project path).
     ![Building Your Game](AppleDocumentation/buildSetting.jpg)
### Step 3. Preparing for App Store Submission

1. Apple Developer Account Setup

- Log In: Access your Apple Developer account at the [Apple Developer website](https://developer.apple.com/).
- Create a Unique Identifier:
  - Navigate to "identifier".
   ![identifier](AppleDocumentation/certificate.jpg)
  - Select "Apple ID", then "APP".
  - Complete the "Description" and "Bundle ID" fields(**The Bundle ID should be the same as you create in Unity as Bundle Identifier**).
  - Click "Continue".
    ![identifierBundleID](AppleDocumentation/Certificate_detail.jpg)


2. App Store Connect Configuration

- Set Up an App Store Connect Dashboard:
  - In App Store Connect, click the "+" icon (After the word "APP").
  - Complete the "New App" settings.  
  ![newApp](AppleDocumentation/newApp.PNG)
    
  - Once created, the new App icon appears on the Dashboard.
    ![Dashboard](AppleDocumentation/Dashboard.PNG)

## Configuring Xcode Project Settings

### Step 4. Xcode Project Configuration

1. Open the Xcode project created in Step 2.
2. Update the signing settings in Xcode:
   - Enable 'Automatically Manage Signing.'
   - Navigate to the Provisioning Profile and select your Team.
   - If needed, add your Team by clicking 'Add an Account' and logging in with your Apple Developer Apple ID.
   - Double-check that the Bundle Identifier is correctly configured.
     ![XcodeSigning](AppleDocumentation/singing_page.PNG)
3. Review the Info.plist to ensure that all app features and permissions are correctly set.
    ![XcodeSigning](AppleDocumentation/xcode_info.PNG)
### Step 5. Building Your Unity AR Game in Xcode

- Build your Unity AR game in Xcode by selecting "Build" in Xcode's project settings.
- Allow Xcode to compile your project.
- Upload Your Game to App Store Connect:
   - Navigate to 'Product' -> 'Archive' in Xcode.
   - Once the archive process is finished, check the 'Status' section to ensure there are no warnings(some warning might okay to be there) or errors.
   - Click 'Distribute App.'
   - ![distrube_app](AppleDocumentation/distrube_app.jpg)
## App Store Submission

### Step 6. App Store Submission
1. In App Store Connect:
   - Navigate to your app and select 'TestFlight' to view your app bundle. Verify that the 'STATUS' is error-free.
   - If you encounter a 'miss compliance' error, click 'Manage,' carefully read      Complying with Encryption Export Regulations, and complete the required         Export Compliance Information as per Apple's instructions.
     ![miss_compliance](AppleDocumentation/miss_compliance.jpg)
2. Complete the App Store Connect submission process, including:
   - Providing all necessary metadata, such as the app name, description, keywords, and contact information.
   - Adding screenshots and app previews for your app, resized as necessary (e.g., using [PicResize](https://picresize.com/))..
   - Setting the pricing and availability options for your game.
   - Configuring any in-app purchases, if applicable.
   - Defining age ratings and content restrictions according to the guidelines.
   - In the Build section, select the bundle you uploaded earlier.
   - Double-check that all provided information is accurate and adheres to Apple's guidelines.
   - Click the 'Save' button located at the top right of the page.

### Step 7. App Review and Approval

- Await the assessment of your app by Apple's review team. The review process typically takes several days.
- Monitor your App Store Connect account for updates and communication from Apple regarding your submission.
- If your app is rejected, carefully review the feedback provided by Apple and address any issues.
  ![apple_review](AppleDocumentation/submition_apple_review.PNG)
- If you receive 'App rejected', click [App Rejection and Troubleshooting](https://github.com/HowardLee134/Documentation-/blob/main/App%20Rejection%20and%20Troubleshooting%20.md).

### Step 8. Release Your AR Game

- Once your app is approved, you have the flexibility to choose when to release it on the App Store.
- If you wish to schedule a release in advance, set the release date in App Store Connect.

## Conclusion

Follow these steps for a successful upload of your Unity project to the Apple Store. Regularly test your app post-publication for optimal performance.



This guide and the Unity project are the results of collaborative efforts by the following:

- **Ming Hao (Howard) Lee** - *Software Developer*
- **University of the Pacific Cube Software Team**

---

For any inquiries, contributions, or further information, please contact the University of the Pacific Cube Software Team.
