![](/assets/gitLogo.png)

# Version Control: Install Git

Git is version control software. It helps us keep track of different versions of our code and lets us collaborate with other developers on a project.

<!--sec data-title="Windows" data-id="section0" data-show=true data-collapse=true ces-->

1. Download Git:[https://git-scm.com/downloads](https://git-scm.com/downloads). Click on the icon that represents **your operating system**

   ![Git Download Image](/assets/image05png.png)

      {% hint style='tip' %}
      This takes you to a new page and should automatically start downloading the newest version of the software. Although they offer 32-bit and 64-bit options, you should be able to take the one they suggest as a default.
      {% endhint %}
   
2. Navigate to your Downloads folder and find the Git download. Click to open it and allow it to make changes to your computer.

3. It will guide you through several screens. You can accept the suggested selections.

4. The last step is to configure Git so that you can use it with GitHub later

      1. Open Git Bash.  The `$` is your prompt.

      2. At the prompt set your user name by running the command `git config --global user.name "Your Name"` replacing the text `Your Name` with your own first and last name, keeping the quotation marks.

      3. Next, set your user email addres by running the command `git config --global user.email youremail@example.com` replacing `youremail@example.com` with your own actual email address.
      
2. **OPTIONAL:** Now that Git is installed, you could add it to your Start menu and taskbar to make it easier to find.

      1. Navigate to where the program was installed.  Check here first: `C:\Program Files \(x86\)\Git`

      2. Open the Git folder and right-click on the Git Bash icon.  Look for the **"pin to start"** and **"pin to taskbar"** options. These will make it easy to get to when you want to use it.

<!--endsec-->

<!--sec data-title="Mac" data-id="section1" data-show=true data-collapse=true ces-->

1. Install Homebrew - a package manager to install and manage development software you'll use. 

      1. In Google Chrome, navigate to [http://brew.sh/](http://brew.sh/)
      
      2. Copy the text underneath the "Install Homebrew" header.
      
      ![](/assets/homebrew.png)
      
      3. In iTerm2 paste the text copied from the homebrew website at the arrow command prompt and press enter.
      
             1. If you are prompted to install Command Line Developer Tools select the "Install" button and accept the license agreement.
             
             ![](/assets/license.png)
             
             2. At the prompt `Press RETURN to continue or any other key to abort` press return/enter.
             
             3. When prompted, type in the password that you use to login to your computer.
             
             {% hint style='tip' %}
             It may look like you’re not typing anything in but this is because it doesn’t want to display your password on the screen for security. Just type your full password and press enter.
             {% endhint %}
             
             4. The process will run for a few minutes until it is complete.  When finished type `brew -v`.  This should display the version number of homebrew that you have installed. Your screen should look similar to the following: 
             
             ![](/assets/brew_done.png)

2. Install Git
      
      1. In iTerm2, type `brew install git` and press enter.
      
      2. When the process completes, type `git --version` at the arrow prompt to ensure Git was properly installed.  If it is properly installed you should see something like `git version 2.8.3` returned.
      
      3. Now we need to configure our Git version control so that you can use it with GitHub later

            1. At the prompt (the green arrow) set your user name by running the command `git config --global user.name "Your Name"` replacing the text `Your Name` with your own first and last name, keeping the quotation marks.

            2. Next, set your user email addres by running the command `git config --global user.email youremail@example.com` replacing `youremail@example.com` with your own actual email address.
   
   



