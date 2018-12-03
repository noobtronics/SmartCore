
# Table of contents
* Installation:
* [How to Install using Boards Manager](#how-to-install-using-boards-manager)


# How to Install using Boards Manager

1) In Arduino IDE, Open File->Preferences
2) Copy following URL in 'Additional Boards Manager URLs':
https://noobtronics.github.io/SmartCore/package_noobtronics_SmartCore_index.json

3) Make sure you have tick marked the 'compilation' and 'upload' in 'Show verbose output during' setting
![](https://raw.githubusercontent.com/noobtronics/SmartCore/master/images/guide/Preferences.jpg)

4) Click OK. Then open Boards Manager from Tools -> Board -> Boards Manager
![](https://raw.githubusercontent.com/noobtronics/SmartCore/master/images/guide/boardmanager.jpg)

5) You should see 'SmartCore' library by noobtronics in the end of Boards Manager windows like below. If you don't something is wrong with your setup. Try reinstalling Arduino IDE to fix the issue or contact us.
![](https://raw.githubusercontent.com/noobtronics/SmartCore/master/images/guide/library_install.jpg)

6) Click Install
![](https://raw.githubusercontent.com/noobtronics/SmartCore/master/images/guide/library_installing.jpg)
![](https://raw.githubusercontent.com/noobtronics/SmartCore/master/images/guide/Installed.PNG)

7) Close Boards Manager and check if Noobtronics boards are coming in the boards list
![](https://raw.githubusercontent.com/noobtronics/SmartCore/master/images/guide/board_display.jpg)


# How to Install Manually
1) If your board manager is not working as expected, you can install SmartCore library manually. Download the library from here -
https://github.com/noobtronics/SmartCore/archive/master.zip
2) Extract the Zip File. Copy the SmartCore folder in hardware directory of Arduino IDE Folder.
eg. Arduino IDE Path is - 
> C:\Program Files (x86)\Arduino

You should copy SmartCore folder so that directory structure is as follows:
> C:\Program Files (x86)\Arduino\hardware\SmartCore\avr\boards.txt

3) Start / Restart IDE and you should see SmartCore boards in the Boards List.
