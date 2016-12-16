# Coding &amp; Cocktails - The Tools {#coding-cocktails-the-tools}

Coding &amp; Cocktails - The Tools![](export/assets/image09png.png)codingcocktailsbadge-200.png

During the sessions we’ll be using some programs and accounts to help with your coding. These are the tools many developers use on a regular basis.

Install Google Chrome

We use Chrome and Google-related tools frequently so this is a good browser to have installed. You can download it here: ([https://www.google.com/chrome/browser/desktop/index.html](https://www.google.com/chrome/browser/desktop/index.html))

Create a Folder For Coding &amp; Cocktails Homework

Create a folder in your home directory (this is typically /users/yourname on macs or C:/Users/yourname on windows machine) called CodingAndCocktails - we’ll create folders here for our different projects. _Note: most command line terminals (including the ones we use) are not case sensitive - but a few are!_ For our purposes, a folder named CodingAndCocktails is the same as one named codingandcocktails.

Install Git

Git is version control software. It helps us keep track of different versions of our code and lets us collaborate with other developers on a project.

*   Download Git:([https://git-scm.com/downloads](https://git-scm.com/downloads)). Click on the icon that represents **your operating system**.

![](export/assets/image05png.png)

This takes you to a new page and should automatically start downloading the newest version of the software. Although they offer 32-bit and 64-bit options, you should be able to take the one they suggest as a default.

*   Navigate to your Downloads folder and find the Git download. Click to open it and allow it to make changes to your computer. Next, it will guide you through several screens. For the most part, you can accept the suggested selections.

You may wish to select the option to add an icon to your desktop to make it easier to find and open the app later. Once you click through the configuration options, click **_Finish_ **to complete the installation..

*   Optional (Windows only): now that Git is installed, you could add it to your start menu and taskbar to make it easier to find.

    *   Navigate to where the program was installed. Check here first: _C:\Program Files (x86)\Git_

    *   Open the Git folder and **right-click on the Git Bash Icon**, and look for an option to “pin to Start” and “pin to taskbar”. These will make it easy to get to when you want to use it.

*   The last step is to configure Git so that you can use it with GitHub later.

    *   Windows users, open Git Bash. (Mac users, you’ll want to do this in iTerm2 AFTER you install it in the next section) . The dollar sign is your prompt. First, you set your user name with the command git config --global user.name &quot;Your Name&quot; (replacing Your Name with your own name, but leaving the quotation marks around it)

    *   Second, use command git config --global user.email youremail@example.com (replacing the sample with your actual email) to set your email address in Git.

Command Line Tools

The command prompt is what we use to enter specific commands for some of our tools, such as when we use Git for version control. While point-and-click programs work for many daily uses, when it comes to programming eventually you will need to use the command line to take advantage of the most powerful tools your computer has to offer, so we teach you to get comfortable with it right from the beginning.

In **Windows**, you already have a command prompt installed. You can find it by going to Start--&gt;Programs and looking for “Command Prompt”. You can also find it through Windows explorer. The **Windows** command prompt does not offer much flexibility and functionality, however. Instead, we will use Git Bash, which was part of your Git Installation above.

If you are a **Mac** user, you can use iTerm2 + oh-my-zsh

*   Download and install iTerm2 from the following link: [https://www.iterm2.com/](https://www.iterm2.com/)

*   For oh-my-zsh go to the following link:[https://github.com/robbyrussell/oh-my-zsh#basic-installation](https://github.com/robbyrussell/oh-my-zsh#basic-installation)

    *   [C](https://github.com/robbyrussell/oh-my-zsh#basic-installation)o[p](https://github.com/robbyrussell/oh-my-zsh#basic-installation)y[](https://github.com/robbyrussell/oh-my-zsh#basic-installation)a[l](https://github.com/robbyrussell/oh-my-zsh#basic-installation)l[](https://github.com/robbyrussell/oh-my-zsh#basic-installation)o[f](https://github.com/robbyrussell/oh-my-zsh#basic-installation)[t](https://github.com/robbyrussell/oh-my-zsh#basic-installation)h[e](https://github.com/robbyrussell/oh-my-zsh#basic-installation)[t](https://github.com/robbyrussell/oh-my-zsh#basic-installation)e[x](https://github.com/robbyrussell/oh-my-zsh#basic-installation)t[](https://github.com/robbyrussell/oh-my-zsh#basic-installation)i[n](https://github.com/robbyrussell/oh-my-zsh#basic-installation)[t](https://github.com/robbyrussell/oh-my-zsh#basic-installation)h[e](https://github.com/robbyrussell/oh-my-zsh#basic-installation)[g](https://github.com/robbyrussell/oh-my-zsh#basic-installation)r[a](https://github.com/robbyrussell/oh-my-zsh#basic-installation)y[](https://github.com/robbyrussell/oh-my-zsh#basic-installation)b[o](https://github.com/robbyrussell/oh-my-zsh#basic-installation)x[](https://github.com/robbyrussell/oh-my-zsh#basic-installation)u[n](https://github.com/robbyrussell/oh-my-zsh#basic-installation)d[e](https://github.com/robbyrussell/oh-my-zsh#basic-installation)r[](https://github.com/robbyrussell/oh-my-zsh#basic-installation)t[h](https://github.com/robbyrussell/oh-my-zsh#basic-installation)e[](https://github.com/robbyrussell/oh-my-zsh#basic-installation)“[v](https://github.com/robbyrussell/oh-my-zsh#basic-installation)i[a](https://github.com/robbyrussell/oh-my-zsh#basic-installation)[c](https://github.com/robbyrussell/oh-my-zsh#basic-installation)u[r](https://github.com/robbyrussell/oh-my-zsh#basic-installation)l[”](https://github.com/robbyrussell/oh-my-zsh#basic-installation)[t](https://github.com/robbyrussell/oh-my-zsh#basic-installation)e[x](https://github.com/robbyrussell/oh-my-zsh#basic-installation)t and paste it at the prompt in iTerm2 and press &lt;**Enter&gt;**[:](https://github.com/robbyrussell/oh-my-zsh#basic-installation)

![](export/assets/image07png.png)Screen Shot 2016-03-31 at 10.01.21 PM.png

*   *   When prompted for a password enter the password that you use to login to your computer. It may look like you’re not typing anything in but this is because it doesn’t want to display your password on the screen for security. Just type your full password and press enter.

*   *   When the process is complete your screen should look similar to the following (note the display in ascii art that oh my zsh ….is now installed and you have a nice colorful arrow prompt):

![](export/assets/image11png.png)Screen Shot 2016-03-31 at 10.05.11 PM.png

Oh-my-zsh helps identify certain things with different colors. Here are some of the colors you might run across.

*   Your arrow indicating your prompt will be green.

*   The name of the directory (aka folder) you’re currently in will be displayed in aqua (The above picture I’m in my home directory (/users/myusername) indicated by the ~ - a shortcut that references the home directory).

*   If you’re in a git repository your branch name will be displayed in a salmon color.

*   If you have changes made in the repository that you’re in that haven’t been committed yet you’ll see a yellow x symbol at the end of your prompt ine.

Sublime Text 2

Sublime Text 2 is the Integrated Development Environment (IDE) we use. After downloading we will configure it with extra tools called _plugins_ that will make your coding life easier.

Note: Sublime can be downloaded for free but they do ask that you buy a license to use it if you like it. However, the tool doesn’t just stop working after the evaluation period so if you like it and decide to continue using it you should support the developers by buying a license when you are ready to make that commitment.

*   Install Sublime Text 2 - [http://www.sublimetext.com/2](http://www.sublimetext.com/2). For Windows, download the 64-bit version. Follow the normal installation process.

*   Follow the prompts as they appear and click **Finish** when prompted to complete the installation.

Configuring Sublime Text:

Next, to get the most out of Sublime, you’ll want to install some additional plugins. If you have ever downloaded and installed a custom font to use in your word processing program, installing plugins is similar. They are additional features that can be individually installed to enhance your experience.

*   Install Package Control ([https://packagecontrol.io/installation](https://packagecontrol.io/installation)). This will help install other plugins.

    *   Go to **View menu--&gt;Console**. This splits your Sublime Screen into several regions.

    *   At the package control web site above, click on the “Sublime Text 2” tab and copy the paragraph of code _as is_. Paste it into the input area of your console, as shown below, and press ****to install the package. The white area in the middle third of the page will tell you that it is downloading package control.

![](export/assets/image08png.png).

You will be prompted to restart Sublime Text for the changes to take effect. Go ahead and do that now. Now that the package control is installed, when you navigate to **Preferences--&gt;Package Control** (or type cmd+shift+p (Windows) or cmd+shift+p (Macs))**,** you have more options available. Typing in the command executes the action:

![](export/assets/image04png.png)

*   Additional plugins:Press ctrl+shift+p (Windows) or cmd+shift+p (Mac) to open the Command Palette Search for “Package Control: Install Package” and press **enter** when you find it. Then package control will open a list of available packages/plugins for you to install.

    *   Emmet ([https://github.com/sergeche/emmet-sublime#how-to-install](https://github.com/sergeche/emmet-sublime#how-to-install)) – quickly generate html/xml/css code

    *   BracketHighlighter ([http://facelessuser.github.io/BracketHighlighter/](http://facelessuser.github.io/BracketHighlighter/)) – view matching opening/closing brackets easily in the gutter (left side)

    *   ColorPicker ([http://weslly.github.io/ColorPicker/](http://weslly.github.io/ColorPicker/)) – insert/change/select colors

    *   SublimeLinter ([https://github.com/SublimeLinter/SublimeLinter-for-ST2](https://github.com/SublimeLinter/SublimeLinter-for-ST2)) – **Note:** must have node.js ([https://nodejs.org/](https://nodejs.org/)) installed on Windows if you are working with javascript or CSS

    *   Markdown Editing ([http://sublimetext-markdown.github.io/MarkdownEditing/](http://sublimetext-markdown.github.io/MarkdownEditing/))/ Markdown Preview ([https://github.com/revolunet/sublimetext-markdown-preview](https://github.com/revolunet/sublimetext-markdown-preview)) - create and preview markdown formatting

*   *   Make it look pretty with themes

        *   Soda ([http://buymeasoda.github.io/soda-theme/](http://buymeasoda.github.io/soda-theme/)) is a popular theme that comes in light and dark versions.

        *   Dracula ([https://github.com/zenorocha/dracula-theme#sublime-text](https://github.com/zenorocha/dracula-theme#sublime-text)) theme is colorful and fun

**Note:** To uninstall a package open Command Palette and search for “Package Control: Remove Package.” Then select the package you’d like to uninstall.

Using Sublime - Helpful Shortcuts to Get You Started

*   Re-indent: indents the selected section properly for easier readability

    *   ctrl/cmd+shift+p - then search for “reindent”

*   Keyboard Shortcuts

    *   select all: ctrl/cmd + a

    *   cut: ctrl/cmd + x

    *   copy: ctrl/cmd + c

    *   paste: ctrl/cmd + v

    *   undo: ctrl/cmd + z

    *   save: ctrl/cmd + s

    *   sublime command palette: ctrl/cmd + shift + p

*   Splitting the Screen

    *   1 - 4 columns: alt+shift+ 1-4 (windows) or option + cmd + 1-4 (mac)

    *   2 - 3 rows: alt + shift + 8 or 9 (windows) OR opt + shift + cmd + 2 or 3 (mac)

    *   Grid of 4: alt + shift + 5 (windows) OR opt + cmd + 5 (mac)

    *   Shift-tab to remove a leading tab for the currently selected text

*   Move lines up or down: ctrl + shift + up or down arrows (windows) OR ctrl + cmd + up or down arrows (mac)

*   Multi cursor - make edits in several places at once: ctrl/cmd+d

RUBY (Windows Users Only)

To use Sass, Windows users need to install the Ruby programming language. Mac users can skip this section because Ruby already comes installed on your operating system. Ruby allows us to use SASS as a CSS compiler for our web pages.

*   Go to the Ruby site to download it: [rubyinstaller.org](http://rubyinstaller.org/) . The big red **Download** button will redirect you to a page of options.

*   The page provides some direction about which version to choose, but we recommend [**Ruby 2.2.4 (x64)**](http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.2.4-x64.exe)[. ](http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.2.4-x64.exe)[Clicking this option will download Ruby to your downloads folder. As with other downloads, click on the *.exe file and allow the program to make changes to your computer.](http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.2.4-x64.exe)

*   Select the language, accept the license, and take note of where it suggests that you load the application - probably here: C:\Ruby22-x64\.

Handy User Accounts

Coding &amp; Cocktails supports your own efforts to learn to code. Therefore, in between sessions, you will want to continue to practice on your own. We refer to these sites often in the sessions as critical tools that we use to help learn to code. The accounts are free unless you choose to buy a premium subscription but that is not necessary for anything we do here.

*   Github ([https://github.com/](https://github.com/)) - this is the essential cloud-based companion tool to Git.

*   Codecademy ([https://www.codecademy.com](https://www.codecademy.com)) - provides easy to follow, hands-on lessons on many of the topics covered in class.

*   Slack - our 24x7 chat room is [kcwit.slack.com](http://kcwit.slack.com) The #codingandcocktails channel will help you keep in touch with all of your Coding &amp; Cocktails girlfriends. However, an administrator has to invite you so if you did not receive an invitation, please email us at codingandcocktails@kcwomenintech.org and we’ll take care of you.