## notes
============

Custom Key Bindings

Main Menu -> Preference -> Key Binding

Add these command lines between [ and ] like is showed below or if you already have
defined commands add a comma at the end and paste these commands

[
  // This command enable Emmet in harbour
  {
   "keys": ["ctrl+shift+e"], "command": "set_file_type", "args": {"syntax": "Packages/HTML/HTML.sublime-syntax"},
  },
  // This command restore harbour
  {
   "keys": ["ctrl+shift+h"], "command": "set_file_type", "args": {"syntax": "Packages/Sublime-Text-harbour-Package/harbour/harbour.sublime-syntax"},
  },
  // This command enable Toggle comments with the key CTRL+/ ( / = teclado numerico)
  {
   "keys": ["ctrl+keypad_divide"], "command": "toggle_comment", "args": { "block": false }
  },
  // This command enable Toggle comments with the key CTRL+SHIFT+/ ( / = teclado numerico)
  {
   "keys": ["ctrl+shift+keypad_divide"], "command": "toggle_comment", "args": { "block": true }
  },
]
