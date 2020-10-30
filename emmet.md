# How to use Emmet plugin in harbour code

* 1- you have to install Emmet package in Sublime Text.

  I`ve assumed you have installed Sublime Package Control. Then:
    * go to main menu -> `Preference -> Package Control -> Install Package`
    * once is showed all packages type emmet, select it and enter.
    * wait to Sublime install the package


* 2- Add these lines to your Key Binding code
    * go to main menu -> `Preference -> Key Binding`
    * once Sublime show the window with 2 panels, add this code to the right panel.
      Between [ and ] brackets
```
  {
   "keys": ["ctrl+shift+e"], "command": "set_file_type", "args": {"syntax": "Packages/HTML/HTML.sublime-syntax"},
  },
  {
   "keys": ["ctrl+shift+h"], "command": "set_file_type", "args": {"syntax": "Packages/Sublime-Text-harbour-Package/harbour/harbour.sublime-syntax"},
  },
```

Note: if you already have some command there, remmember to add a comma after the last curly bracket

* 3 that`s all

Open a prg file and do what you have to do with harbour code in prg, when you need to type with **Emmet** just
press **CTRL+SHIFT+E** and when you need go back to harbour press **CTRL+SHIFT+H**


*Maybe you must consider change the keys for those that you feel better*








