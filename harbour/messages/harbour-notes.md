## mis notas de harbour
## --------------------

this file is called from :
  * main menu > preferences > package settings > harbour > my notes of arduino *

Edit this file as you want.  

editing the file: .\packages\user\Main.sublime-menu
##### Take care about other items in this menu file

This is a sample of the file .\packages\user\Main.sublime-menu 
In this case add two submenus in Preferences > Package Settings
harbour y arduino.

If you want to add on existing file .\packages\user\Main.sublime-menu a submenu just for harbour, then 
add this code


                    {
                        "caption": "harbour",
                        "children":
                        [
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/Harbour/Harbour.sublime-settings"},
                                "caption": "Settings – Default"
                            },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/User/Harbour.sublime-settings"},
                                "caption": "Settings – User"
                            },
                            { "caption": "-" },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/Harbour/messages/harbour-notes.md"},
                                "caption": "my notes of harbour"
                            },
                            { "caption": "-" },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/Harbour/messages/harbour-install.txt"},
                                "caption": "Install message"
                            }
                        ]
                    }  /* if exist another submenu after this, then add a comma after bracket */

###  After 
                "caption": "Package Settings",
                "mnemonic": "P",
                "id": "package-settings",
                "children":
                [


## And before the begining of another submenu



### If the file .\packages\user\Main.sublime-menu does not exist the create it with content.

[
    {
        "caption": "Preferences",
        "mnemonic": "n",
        "id": "preferences",
        "children":
        [
            {
                "caption": "Package Settings",
                "mnemonic": "P",
                "id": "package-settings",
                "children":
                [
                    {
                        "caption": "harbour",
                        "children":
                        [
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/Harbour/Harbour.sublime-settings"},
                                "caption": "Settings – Default"
                            },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/User/Harbour.sublime-settings"},
                                "caption": "Settings – User"
                            },
                            { "caption": "-" },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/Harbour/messages/harbour-notes.md"},
                                "caption": "my notes of harbour"
                            },
                            { "caption": "-" },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/Harbour/messages/harbour-install.txt"},
                                "caption": "Install message"
                            }
                        ]
                    },
                    {
                        "caption": "arduino",
                        "children":
                        [
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/arduino/arduino.sublime-settings"},
                                "caption": "Settings – Default"
                            },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/User/arduino.sublime-settings"},
                                "caption": "Settings – User"
                            },
                            { "caption": "-" },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/arduino/messages/arduino-notes.md"},
                                "caption": "my notes of arduino"
                            },
                            { "caption": "-" },
                            {
                                "command": "open_file",
                                "args": {"file": "${packages}/arduino/messages/arduino-install.txt"},
                                "caption": "Install message"
                            }
                        ]
                    }
                ]
            }
        ]
    }
]
