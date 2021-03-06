Refresh-Actionbar-Progress-Item
===============================

An action bar item that implements this common pattern:

   1 . Initially it shows a refresh button.
   2 . If the button is clicked, a background operation begins and the button turns into a progress indicator.
   3 . When the background operation ends, the button is restored to its initial state.
   
  The progress bar shows a magnitude which represents how far the operation has proceeded. The progress bar can also be made
  indeterminate, just like the built-in ProgressBar.
  
  It is possible to add a small badge to the action item. This tells the user that there is new data available.
  
  This library requires ActionBarSherlock, and is thus compatible with Android 2.x and newer. If you don't need 2.x 
  compatibility and thus use the native action bar, check out this fork of the library.
  
  More Info to https://github.com/ManuelPeinado/RefreshActionItem
