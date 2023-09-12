# CSCI1423_F23
Parent repository for CSCI 1423 Fall 2023 

## Creating your own repository 
1. Click "Use this template"
2. Click "Create a new repository"
3. Name your repository "CSCI1423"
4. Make sure your respository is **PRIVATE** and create repository

## Sharing your repository
1. Go to settings and click on "Collaborators"
2. Under "Manage access" click on "Add people"
3. Add the following usernames: KEdwards25, PSanthosh45, ginarivera93, dgardner-twu

## Cloning your respository to command line (Windows)
1. Open Ubuntu or Terminal. **Do NOT log into your SSH.**
3. Under the Code tab of your repository, click on the green "<> Code" button
4. Copy the HTML link
5. In your Ubuntu/Terminal, type "git clone " and paste the HTML link and enter
6. Enter your GitHub credentials

## Cloning your respository to command line (Mac, iOS)
1. Make a Personal Access Token
   - Open your profile setting in GitHub
   - Click on "Developer Settings" at the bottom of the menu
   - Click on "Personal access tokens" and generate a classic token
     - Set expiration to "no expiration"
     - Select all boxes for Scopes
   - Once generated, copy the access token url
3. Update keychain access
   - Open Keychain Access by searching for it in Finder
   - Search for "github.com"
     - If the keychain exists:
       - Update the password to be the access token url
     - if the keychain does not exist create a new one by clicking the create icon next to search bar
       - Keychain Item Name: github.com
       - Account Name: your GitHub username
       - Password: access token url
   - In your Ubuntu/Terminal, type "git clone " and paste the HTML link and enter
   - When asked for your GitHub credentials:
     - Username: your GitHub username
     - Password: access token url
   
