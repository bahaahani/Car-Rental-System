# Car Rental System Setup Instructions

## Prerequisites

Before you begin, ensure the following software is installed on your system:

- Node.js: Download the recommended version from the [Node.js website](https://nodejs.org/).
- npm: Comes bundled with Node.js.
- Ionic CLI: Install it globally with `npm install -g @ionic/cli`.
- Angular CLI: Install it globally with `npm install -g @angular/cli`.

## Downloading the Project

Clone the repository to your local machine:

```shell
git clone https://github.com/bahaahani/Car-Rental-System.git
cd Car-Rental-System

Installing Dependencies
Install all the necessary dependencies by running:
npm install
Running the App Locally
Start the app on a local server with:
ionic serve

Building for Production
To build the application for a production deployment:
ionic build --prod

For iOS (requires macOS)

ionic cordova platform add ios
Next, open the .xcworkspace file in Xcode from the platforms/ios directory, select your device as the target, and press the 'Run' button to build the app and deploy it to your device.

To run the application on a device, you'll need to add the platform to your project.

For Android
ionic cordova platform add android
ionic cordova run android


This Markdown file should be saved as `README.md` or another appropriately named Markdown file in the root directory of your GitHub repository. Users can follow these instructions to set up and run the car rental application on their devices.
