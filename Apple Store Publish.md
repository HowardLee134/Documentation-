# Unity AR Game App Store Submission Guide

## Preparation and Configuration

### Step 1. Prerequisites
- Check the Info on [App Store submission requirement](https://developer.apple.com/news/?id=jd9wcyov) to make sure your Mac device is capabale. 
- A Mac computer running macOS with the latest updates installed.
- An Apple Developer account [Apple Developer](https://developer.apple.com/)(Cube Software Team already have an account).
- Unity Hub and Unity Editor 


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

2. Building Your Game

   - Return to the "Build Settings" window in Unity.
   - Click "Build" or "Build and Run" to generate an Xcode project.
   - Choose a location to save the Xcode project(Highly recommend to create a new IOS build folder in your project path).

### Step 3. Preparing for App Store Submission

1. Log in to your Apple Developer account ([Apple Developer](https://developer.apple.com/)).
2. Create an App ID in the Developer Center specifically for your game.
3. Create a provisioning profile for distribution in Xcode.
4. Set up an App Store Connect record for your game ([App Store Connect](https://appstoreconnect.apple.com/)).

## Configuring Xcode Project Settings

### 6. Xcode Project Configuration

1. Open the Xcode project created in Step 4.
2. Update the signing settings in Xcode with the provisioning profile and App ID created in Step 5.
3. Set the Deployment Target in Xcode to the minimum iOS version required by your game.
4. Review and update any entitlements, app icons, and splash screens directly in Xcode as needed.

### 7. Building Your Game in Xcode

- Build your Unity AR game in Xcode by clicking "Build" in Xcode's project settings.
- Allow Xcode to compile your project.

## App Store Submission

### 8. App Store Submission

1. Open the Application Loader tool (part of Xcode) and select your game's build.
2. Follow the prompts to upload your game to App Store Connect.
3. Complete the App Store Connect submission process, including:
   - Filling out all necessary metadata, such as app name, description, keywords, and contact information.
   - Adding screenshots and app previews that showcase your AR game.
   - Setting the price and availability of your game.
   - Defining in-app purchases, if applicable.
   - Configuring age ratings and content restrictions.
4. Double-check that all information is accurate and follows Apple's guidelines.

### 9. App Review and Approval

- Wait for Apple's review team to assess your app. The review process typically takes several days.
- Monitor your App Store Connect account for updates and communication from Apple regarding your submission.

### 10. Release Your AR Game

- Once your app is approved, you can choose when to release it on the App Store.
- Set the release date in App Store Connect if you want to schedule the release in advance.
- Promote your game through marketing and social media channels to reach a wider audience.
