# TickTock
# Setup
This section contains information regarding installations and basic project setup.

## Installations
This project uses Expo to run React Native apps. If you don't have Expo and its required dependencies installed, you can find an installation guide here: [https://docs.expo.dev/get-started/installation/](https://docs.expo.dev/get-started/installation/).

You will also need Git to work with code commits. You can use the installation guide found here: [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

To run commands, you can use a terminal. Git Bash, Windows PowerShell, and the native Terminal applications for both Mac and Linux work for this.

## Initial Repo
First, create a new directory that will contain all of your code. You can create this anywhere you like.

Then, type the following to create an empty Git repository:

    git init

Then, to link to the remote repository (located on this GitHub):

    git remote add origin https://github.com/aggie-coding-club/TickTock.git

Then, clone the files into your directory by running this command:

    git clone https://github.com/aggie-coding-club/TickTock.git

Once that's done, you need to create all the packages required for Expo. Making sure you have Node installed (refer to the [Setup](#Setup) section), run the following command:

    npm install


# Usage
Once you have your app, you can start the app using:

    expo start

This will bring up a page with a QR Code to scan. Making sure you have the Expo app on your phone, you can scan this to bring up a live-update feed of the app.

You can also run:

    npm run ios
    
Or:

    npm run android

To run the app on an ios simulator (Mac only) or android simulator.

# Code Commit Process
This section will detail the process you can use to commit code (Add code to the GitHub). Follow this process every time you want to contribute to the project.


Start by getting the latest version of the application. Making sure you're in the directory of your project, run this command:

    git pull origin main

Then, you want to create a new branch. You are going to work off this branch exclusively for your code. For ease of naming, please name the branch **Your first name and last initial**. So, my name being Ilham Aryawan, I would run:

    git checkout -b ilhamA

Once you're done, edit and commit your code as you please.

When you finish, push your code to the main repository using this command:

    git push origin ilhamA

Once you've done that, visit GitHub and create a pull request. You can learn more about pull requests here: [https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

Once you're done, you can switch back to the main branch and delete the feature branch you were using. You can do it using the following 2 commands:

    git checkout main
    git branch -D ilham A
