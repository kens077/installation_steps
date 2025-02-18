# How to install and setup NodeJS and npm?
- **step 1:**
Open the Terminal on your Ubuntu system. You can do this by pressing the **"Ctrl+Alt+T"** keys simultaneously.
- **step 2:**
Update your package list by typing the following command in the Terminal:

   `sudo apt-get update`
 - **step3:**
  Install Nodejs using the following command: 
  
    `sudo apt get install node js`
  - **step4:**
   Check if Node.js is installed by typing the following command:
   
    `node -v`
    
    This will display the version number of Node.js installed on your system.
   - **step5:**
Install NPM (Node Package Manager) by typing the following command:

      `sudo apt-get install npm`
   - **step6:**
    Check if NPM is installed by typing the following command:

      `npm -v`
   - **step7:**
      If you encounter any issues with the installation, you can try updating the package list again by typing the following command:
      
        `sudo apt-get update`

       Then repeat steps 3-6.
## Steps to update the nodejs and npm versions

- **step 1:**
Open the Terminal on your Ubuntu system.
- **step 2:**
Check the currently installed versions of Node.js and NPM by typing the following commands:

   `node -v npm -v`
 - **step3:**
 To update Node.js, you can use the Node Version Manager (nvm) tool. If you do not have nvm installed, you can install it using the following command:
  

   curl -o- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh) | bash
  - **step4:**
 Once nvm is installed, you can use it to install the latest version of Node.js by typing the following command:
   
    `nvm install node`
    
    This will install the latest version of Node.js. You can verify the version by typing the following command:
    
    `node -v`
   - **step5:**
To update NPM to the latest version, you can use the following command:

     `npm install -g npm@latest`

     This will install the latest version of NPM globally. You can verify the version by typing the following command:
 
     `npm -v`

     If you want to update NPM for a specific project, you can navigate to the project directory and run the above command without the -g flag.
