# iTerm2 tips

## using ⌥+← or ⌥+→ to word jump, ⌥+backspace to delete a word 
- goto iTerm2 > Preferences > Profiles > Keys, General tab

  and set "Left option key" to "Esc+"
- goto Key mappings tab
  
  find (or create) keyboard shortcut:

   ⌥+←, set Action to "Send escape squence" and set Esc+b

   ⌥+→, set Action to "Send escape squence" and set Esc+f

changes in exported keymap:
 
    "0xf702-0x280000-0x0": {
        "Version": 0,
        "Action": 10,
        "Text": "b",
        "Label": ""
      },
    "0xf703-0x280000-0x0": {
        "Version": 0,
        "Action": 10,
        "Text": "f",
        "Label": ""
      },
    
  

 
