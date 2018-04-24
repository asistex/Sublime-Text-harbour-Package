# Sublime-Text-harbour-Package
Sublime Text and Harbour

This package has Harbour functions with the syntax.

This package has some Harbour functions listed in https://github.com/Petewg/harbour-core/wiki

At this moment they are:
* Harbour specific core functions. from hb_A* to hb_Z*.
* Clipper compatible functions. from A to Z.
* hbWin lib
* Serial communication port API functions hb_com*()

Thanks to **Pete Petewg** for the documentation of harbour functions.

This project is based on https://github.com/rafathefull/harbour of **Rafael Carmona**

If you encounter a bug, please create an issue here:
https://github.com/asistex/Sublime-Text-Harbour-Package/issues  **New Issue**

***License MIT***

Contributions to this package are welcome.

[![image](https://github.com/asistex/Sublime-Text-harbour-Package/blob/master/slb.jpg)](https://github.com/asistex/Sublime-Text-harbour-Package/)
                 

## Installation

A- [From the command line](#from-the-command-line)

B- [Downloading the zip package](#downloading-the-zip-package)



### From the command line

If you are a git user, you can install it and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

With this method you can get updates of this package using the Git command: **git pull** from the command line.

* 1- Open Sublime Text
* 2- From Sublime main menu, click on: Preferences > Browse Packages. This will open the windows explorer in the Sublime preferences folder, usually is \Sublime Text 3\Packages\
* 3- Close Sublime Text 3.
* 4- Open the command prompt here.  `c:\....\Sublime Text 3\Packages>` 
* 5- Copy the following command:  
```
     git clone https://github.com/asistex/Sublime-Text-harbour-Package.git
```
* 6- Paste it at the command prompt and press Enter.
* 7- While Sublime is not running delete the session file  **.\Sublime Text 3\Local\Session.sublime_session** and if exist also delete **.\Sublime Text 3\Local\Auto Save Session.sublime_session**
* 8- Open Sublime, load a file `.prg` . Click the label on the statusbar at the right corner and select **harbour** from the list. If the statusbar is hidden then goto **Main menu > View > Syntax**



### Downloading the zip package

* 1- Download the file using the GitHub [.zip download option] **https://github.com/asistex/Sublime-Text-harbour-Package/archive/master.zip**
* 2- Open Sublime Text
* 3- From Sublime main menu, click on: Preferences > Browse Packages. This will open the windows explorer in the Sublime preferences folder, usually is `.\Sublime Text 3\Packages\` .
* 4- Close Sublime Text 3.
* 5- Copy or move the downloaded file to `.\Sublime Text 3\Packages\`
* 6- Unzip the package there.  This will create a folder named **harbour**
* 7- Move (drag) the file **harbour.sublime-package** to the folder `.\Sublime Text 3\Installed Packages\`
* 8- While Sublime is not running delete the session file  **.\Sublime Text 3\Local\Session.sublime_session** and if exist also delete **.\Sublime Text 3\Local\Auto Save Session.sublime_session**
* 9- Open Sublime, load a file .prg . Click the label on the statusbar at the right corner and select **harbour** from the list. If the statusbar is hidden then goto **Main menu > View > Syntax**


[![image](https://github.com/asistex/Sublime-Text-harbour-Package/blob/master/sublime.gif)](https://github.com/asistex/Sublime-Text-harbour-Package/)


**https://github.com/asistex**
   
***`Carlos.  Asistex`***