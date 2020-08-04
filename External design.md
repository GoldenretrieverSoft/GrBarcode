# Purpose and Scope of the Software
## Purpose
 To read information from merchandise barcode.
## Scope of the Software
 * read barcode from camera.
 * find infomation from jancode.
 * note infomation from database.
 * Using TTS speak infomation.
 
#  Interface Requirements and Environment
  User Interface
  
## main activity(screen)

     First Layout                       Second Layout
     +------------------------------+   +------------------------------+
     |                              |   |                              |
     |                              |   |                              |
     |                              |   |                              |
     |        Camera button         |   |                              |
     |                              |   |                              |
     |                              |   |          Continuos           |
     |                              |   |                              |
     +------------------------------+   |           Layout             |
     |              |               |   |                              |
     |              |               |   |                              |
     |              |               |   |                              |
     |    Setting   |     Exit      |   |                              |
     |    Button    |     Button    |   |                              |
     |    (futher)  |               |   |                              |
     |              |               |   |                              |
     +------------------------------+   +------------------------------+
   
  When Initalizing screen
  - download database (futher)
   
  After screen Initialized, 
  - Wait servaral second And Turn off Screen for save battery


### Action
  Camera Button
   Get barcode from camera.
   
   feature 
    * Automaically find barcode. and read automatcally
    * Find item's infomation.(local database)
    * Read item's infomation.  
  
  Setting button
   * (futher)Go to setting screen
  
  Exit Button
   * Close appication
  
