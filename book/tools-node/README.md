# Node and npm

Node is a JavaScript runtime - this means JavaScript is no longer confined to a web browser.  You can now run JavaScript on your computer.

npm is a package manager for JavaScript packages.  This allows you to manage and use code from other developers so you don't have to reinvent the wheel and can reuse handy bits of code for common functionality.

{% hint style='info' %}
The <i class="fa fa-share fa-rotate-180"></i> icon tells you when to press `Enter`.
{% endhint %}

## Node
Click on the arrow (<i class="fa fa-chevron-up" aria-hidden="true"></i>) below to expand the section for your operating system.

<!--sec data-title="Windows" data-id="section0" data-show=true data-collapse=true ces-->

### To install or update Node, follow the instructions listed

1. In Google Chrome go to [nodejs.org/en/download/current](https://nodejs.org/en/download/current/). 

1. Click on the "Windows Installer" option and the installer will download.

   ![](images/node-windows.png)

1. In your "Downloads" folder, right click on the Node installer and select **Properties**. Check the checkbox to **Unblock** in the **Security** section.

   ![](images/windows-security.png)

1. Run through the installer using the default options provided.

1. In Cmder, check that you have correctly installed Node by typing `node --version` <i class="fa fa-share fa-rotate-180"></i>. 

   If the output contains a number, Node installed and you can proceed with the npm section below. The picture may not match your installation version.

    ![](images/node-version-windows.png)

    {% hint style='danger' %}
If you receive a command not found message you'll need to troubleshoot what went wrong during your install - grab a mentor to help!
    {% endhint %}  
<!--endsec-->

<!--sec data-title="Mac" data-id="section1" data-show=true data-collapse=true ces-->

1. In iTerm2, type `brew -v` <i class="fa fa-share fa-rotate-180"></i>. 

   If the output contains a number, you can proceed installing or upgrading Node. The picture may not match your installation version.

   ![](images/brew-version.png)

   {% hint style='danger' %}
If you receive a command not found message you'll need to install Homebrew as directed in the [Git](/tools-git/README.md) section.     
   {% endhint %}  

1. In iTerm2, type `brew update` <i class="fa fa-share fa-rotate-180"></i> to ensure Homebrew is up to date.

1. In iTerm2, type `brew doctor` <i class="fa fa-share fa-rotate-180"></i> to make sure your system is ready to brew. Grab a mentor to talk through any messages you get from this step that you aren't sure about. 

   ![](images/brew-doctor.png)

### Install Node
    
1. In iTerm2, type `brew install node` <i class="fa fa-share fa-rotate-180"></i> to install Node.


### Update Node

1. In iTerm2, type `brew upgrade node` <i class="fa fa-share fa-rotate-180"></i> to update Node.


### Verify 
1. In iTerm2, type `node --version` <i class="fa fa-share fa-rotate-180"></i>. 
   
   If the output contains a number, Node installed and you can proceed with the npm section below. The picture may not match your installation version.

    ![](images/node-version.png)

    {% hint style='danger' %}
If you receive a command not found message you'll need to troubleshoot what went wrong during your install - grab a mentor to help!
    {% endhint %}  
<!--endsec-->

## npm

npm installs automatically with Node.  Check that you have npm installed in your command line tool \(Cmder for Windows or iTerm2 for Mac\) by typing `npm --version` <i class="fa fa-share fa-rotate-180"></i>. 

1. In Cmder or iTerm2, type `npm install npm -g` <i class="fa fa-share fa-rotate-180"></i>.

