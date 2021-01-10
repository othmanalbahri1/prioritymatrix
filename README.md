# PriorityMatrix
A Rainmeter skin to organize your to-do list according to a 2x2 priority matrix. More info on this method [here](https://en.wikipedia.org/wiki/Time_management#The_Eisenhower_Method).

![demo](https://user-images.githubusercontent.com/53126078/70654816-f9ab4780-1c4e-11ea-86d8-a253644707e6.jpg)

# Setup (Windows only):
1. [Download and install Rainmeter](https://www.rainmeter.net) (see below for cloud syncing across devices).
2. Click "Clone or download" on this Github page (green button above) and select Download Zip.
3. Unzip the downloaded file and copy the PriorityMatrix folder to the Skins folder where you installed Rainmeter (/Rainmeter/Skins/PriorityMatrix/).
4. Open Rainmeter (find Rainmeter.exe or Rainmeter icon in taskbar).
5. Click Refresh All.
6. PriorityMatrix should now be listed on the left. Expand it, click PriorityMatrix.ini then Load.

# Alternative Setup (Windows only):
If the above setup section doesn't work for you, [click here](https://github.com/othmanalbahri1/prioritymatrix/files/5792858/Rainmeter.zip) to downlaod a portable version of Rainmeter which includes PriorityMatrix then follow these steps:
1. Unzip the file 
2. Copy the unzipped Rainmeter folder to a convenient location (e.g. Documents)
3. Inside the Rainmeter folder, run Rainmeter.exe. PriorityMatrix should load automatically.
4. To star PriorityMatrix on startup, follow [this guide](https://www.howtogeek.com/208224/how-to-add-programs-files-and-folders-to-system-startup-in-windows-8.1).

# Adding tasks:
Clicking on Do now, Delegate, Schedule, or Eliminate opens a text file to enter/edit your tasks. Edit as desired and save it (you can use any UTF-16 characters such as check marks or empty boxes). It should update the relevant quadrant automatically. 

# Always on Desktop
To keep PriorityMatrix stuck to the Desktop, right click on it (after it's been loaded): Settings -> Poisition -> On Desktop

This prevents interference with other apps' UIs.

# Cloud syncing:
You can sync tasks across devices by installing the portable version of Rainmeter on a cloud folder (eg Onedrive). To launch PriorityMatrix on startup in this case follow [this guide](https://www.howtogeek.com/208224/how-to-add-programs-files-and-folders-to-system-startup-in-windows-8.1).

# Other ideas:
1. Each quadrant takes about 14 lines. Anything that's not in the first 14 lines of the text file will not be shown in the quadrant. You can use that hidden space to store stuff like completed tasks or UTF-16 characters for future use.

2. Since each quadrant is a simple text file, you can easily integrate web-parsers or automation scripts for your tasks.
