# Node & npm

Node is a JavaScript runtime - this means where JavaScript used to be confined to a web browser you can now run JavaScript on your computer.

npm is a package manager for JavaScript packages.  This allows you to manage and use code from other developers so you don't have to reinvent the wheel and can reuse handy bits of code for common functionality.

### Node
Click on the arrow (^) below to expand the section for your operating system.

<!--sec data-title="Windows" data-id="section0" data-show=true data-collapse=true ces-->
1. In Google Chrome go to [nodejs.org/en/download](https://nodejs.org/en/download/).

2.Click on the Windows Installer option and the installer will download: 

   ![](/assets/node-install.png)

3. Run through the installer using the default options provided.

4. In Git Bash, check that you have correctly installed Node by typing `node --version`. 

    If a number is output, Node is installed and you can proceed with the npm section below.

    If you receive a command not found message you'll need to troubleshoot what went wrong during your install - grab a mentor to help!  
<!--endsec-->

<!--sec data-title="Mac" data-id="section1" data-show=true data-collapse=true ces-->
1. In iTerm2, type `brew -v`. 

    If a number is output, proceed with step 2.

    If you receive a command not found message you'll need to install Homebrew as directed in the [Version Control: Git](/version-control---git.md) section. 

2. In iTerm2, type `brew update` to ensure Homebrew is up to date.

3. In iTerm2, type `brew doctor` to make sure your system is ready to brew. Grab a mentor to talk through any messages you get from this step that you aren't sure about. 
    
4. In iTerm2, type `brew install node` to install Node.

5. In iTerm 2, type `node --version`. 

    If a number is output, Node is installed and you can proceed with the npm section below.

    If you receive a command not found message you'll need to troubleshoot what went wrong during your install - grab a mentor to help!  
<!--endsec-->

### npm

npm is installed with Node.  Check that you have npm installed in your command line tool \(Git Bash for windows or iTerm2 for macs\) by typing `npm --version`. 

1. In Git Bash or iTerm2, type `npm install npm -g` to upgrade npm.

