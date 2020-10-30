# Sublime-Text-harbour-Package
Sublime Text and Harbour.

Package Last Update = 2020/10/30

This package has Harbour functions with the syntax.

This package has some Harbour functions listed in https://github.com/Petewg/harbour-core/wiki

At this moment they are:
* Harbour specific core functions. from hb_A* to hb_Z*.
* Clipper compatible functions. from A to Z.
* hbWin lib
* Serial communication port API functions hb_com*()
* hb_Socket functions
* hb_ zip functions
* hb_regex functions
* Curl functions. (not all, need help with params)
* mod_harbour functions
* Added keys to toggle between harbour syntax and html syntax  **`NEW`**

  You can use **`EMMET`** in a harbour code.

  Read about how to do it in the file **emmet.md**


---

Thanks to **Pete Petewg** for the documentation of harbour functions.

This project is based on https://github.com/rafathefull/harbour of **Rafael Carmona**

If you want to add more functions or snippets and/or if you encounter a bug, please create an issue here:
https://github.com/asistex/Sublime-Text-Harbour-Package/issues  **New Issue**

Contributions to this package are welcome.

***License MIT***

[![image](https://github.com/asistex/Sublime-Text-harbour-Package/blob/master/slb.jpg)](https://github.com/asistex/Sublime-Text-harbour-Package/)


## Installation. (2 options)

A- [Install downloading the zip package](#downloading-the-zip-package)

B- [install from the command line with git tools](#from-the-command-line)



### Downloading the zip package

* 1- Download the zip file using the green GitHub button `Clone or download` select [download zip option]
     You will get the file **Sublime-Text-harbour-Package-master.zip** on your PC.
* 2- Open Sublime Text
* 3- From Sublime main menu, click on: Preferences > Browse Packages. This will open the windows explorer in the Sublime preferences folder, usually is `.\Sublime Text 3\Packages\` .
* 4- Close Sublime Text 3.
* 5- Copy, move or drag the downloaded file `Sublime-Text-harbour-Package-master.zip` to `.\Sublime Text 3\Packages\`
* 6- Unzip the package there. This will create a folder named **Sublime-Text-harbour-Package-master**
* 7- Rename it to **Sublime-Text-harbour-Package**
* 8- While Sublime is not running delete the session file  **.\Sublime Text 3\Local\Session.sublime_session** and if exist also delete **.\Sublime Text 3\Local\Auto Save Session.sublime_session**
* 9- Open Sublime, load a file .prg . Click the label on the statusbar at the right corner and select **harbour** from the list. If the statusbar is hidden then goto **Main menu > View > Syntax**



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






[![image](https://github.com/asistex/ighoo/blob/master/bin/sublime.gif)](https://github.com/asistex/Sublime-Text-harbour-Package/)


**https://github.com/asistex**

***`Carlos.  Asistex`***
