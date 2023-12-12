# CustomShell-Documentation-Windows
My notes for making a custom shell on windows to replace explorer completely.

# Shell Responsibilties
- UWP Activation
  - [Solved](https://github.com/MishaProductions/CustomShell) by [MishaProductions](https://github.com/MishaProductions).
- Wallpaper Window (hosted by explorer)
  - Should be as easy as spawning a window with ~(WM_CAPTION | WM_THICK) and some other appropriate styles
- Notification Handling
  - AFAIK there isn't any alternative rn, both BlackBox and Cairo can't handles notifs on Win 11.  
