# Intro To Dev

## Code storage and versioning

1. Create a github account, why? 
	1. What is github - it is a code version tool where you can store your code in form of repositories
	2. Can it to do more - it helps you create a structured and historical view of your work and your contributions towards someone else’s; which then creates a profile or portfolio of your work
	3. Why do you need it - our laptops and desktops may fail and we may not be able to retrieve the hard work we put in to create something we had dreamt of
	4. Some inspiration - [https://github.com/clementmihailescu]
2. Create a github account, how?
	1. Visit [https://github.com/]
	2. Register with your email ids
	3. Login in to [https://github.com/]
	4. Create repository 
		1. Repository name - introtodev<your-name>

## Starting towards development environment setup
### Source code management
1. Install git scm
	1. Download git from [https://git-scm.com/downloads]
	2. Install git scm from the installer
	3. Open command prompt in Windows and terminal in MacOS and run the following command to make sure git is installed
		git --version
2. Get the code from github to your local development machine
	1. Login in to your github account and move to the repository that you just created in the earlier steps 
	2. Click on the button named Code
(img)
	3. Copy the URL that is provided in the sub menu that opens up and we will call it <path-to-repository>
	4. Create a local directory structure in you development machine
		1. Windows - <drive>\\Mages\\FSDP
		2. MacOS - <user-directory>/Mages/FSDP
	5. Open command prompt for Windows and terminal for MacOS
	6. In the command prompt / terminal, move to the directory we created in the earlier step no. 4 and run the following command; the process is called **cloning** / checking out code
		git clone <path-to-repository>
3. Download github desktop
	1. Since we will have our repository in github, we may want to have a visual tool for managing the same
	2. Download github desktop from [https://desktop.github.com/]
	3. Install the github desktop from the installer
	4. Once installed, open github desktop and login using your github account that you created earlier
	5. Authorize the desktop app once asked
	6. Add relevant details once asked
	7. Click on Add local repository
	8. Provide the local directory path where we cloned in earlier steps

### Code development environment

1. Install Visual Studio Code
	1. Download visual studio code for your specific platform from [https://code.visualstudio.com/download]
	2. Install visual studio code from the installer
	3. Open visual studio code to verify installation
2. Open your code inside visual studio code
	1. Click on Add Folder to workspace
		(img)
	2. Add the folder that holds the code that we cloned in earlier steps
	3. You will be able to see the code and in visual studio code and some more data on different bars in visual studio code
