# Open IO
Open IO is an online multiplayer IO snake game that uses javascript, react, node, and socket.io

# Resources


# Setting Up (Windows, MacOS)
1. Get Node.js
	1. Visit https://nodejs.org/en/
	2. Download Node 10.15.3 from the website.
	![nodejs_website](images/nodejs_website.png)
	3. Once, downloaded, double click to install.
	4. The Node.js Setup Wizard will appear. Follow the instructions to Install.
	![nodejs_wizard](images/nodjs_wizard.png)


2. Check if successfully installed
	**On Windows 10**
	If successfully installed, running "node -v" in Command Prompt will show your version of Node and running "npm -v" will show you your version of npm (your version should be different than the one in the image)
	![version_windows](images/version_windows.png)

	**On Mac OSX**
	If successfully installed, running "node -v" in Terminal will show your version of Node and running "npm -v" will show you your version of npm (your version should be different than the one in the image)
	![version_mac](images/version_mac.png)



# Setting Up (Linux)

1. Get Node.js
	**Debian, Ubuntu, Linux Mint**
	$ sudo apt-get install nodejs npm

	**RHEL, CentOS**
	$ sudo yum install epel-release

	**Fedora**
	$ sudo dnf install nodejs npm

	**Arch Linux**
	$ sudo pacman -S nodejs npm

2. Check if successfully installed.
	If successfully installed, running "node -v" in Terminal will show your version of Node and running "npm -v" will show you your version of npm (your version should be different than the one in the image)


# Running Open IO
1. Clone Open IO From GitHub

	Download from https://github.com/gibboa/open_io or clone with "git clone https://github.com/gibboa/Open_IO.git"

2. Running Open IO
	1. From your command line, go to the Open IO directory.
	2. Run the command "node server.js" to start running.
	3. You will receive the port where you can see it running. In the image below, the port is 8081
	![port](images/port.png)
	4. In your web browser, visit "localhost:x" where x is the port number
	![url](images/url.png)






