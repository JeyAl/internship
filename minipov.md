## MiniPOV4 Configuration Guide  

Fist, you want to visit the following Website:  
https://learn.adafruit.com/minipov4-diy-full-color-persistence-of-vision-light-painting-kit?view=all  
On this Website, scroll down to the "Install Windows Drivers" section.  
Here, you want to click on this link:
![title](https://github.com/JeyAl/internship/blob/master/images/drivers_link.PNG)
and then download the required drivers:
![title](https://github.com/JeyAl/internship/blob/master/images/drivers_download.PNG)

Follow the installation instructions of the drivers and install the drivers that are selected by default.  
After you installed the driver, plug in the MiniPOV4 while being turned off, then when it is plugged in, turn it on.
In your device Manager, there should be a USBTiny device.

![title](https://github.com/JeyAl/internship/blob/master/images/USBTiny.PNG)

Afterwards, scroll a bit further down to the "Download Software" section.  
Download the 2 highlighted files, shown as green buttons:  

![title](https://github.com/JeyAl/internship/blob/master/images/downloads.PNG)

And download Processing by clicking on the blue button in the same section:

![title](https://github.com/JeyAl/internship/blob/master/images/processing.PNG)

Unpack all these files into a Folder on your Desktop.  
When you're done downloading, open up processing and quit again.  
This will create a folder "Processing" in your Documents.  
Inside this folder, create a folder "libraries" if it doesn't exist yet.  
Then put the folder "controlP5" that you previously downloaded in the "libraries" folder.  
So the path should be "My Documents/Processing/libraries/controlP5/library.properties".  
Now open Processing again.  Click on "File" and then "Open..." and then select the MiniPov4_ImageConverter Folder that you previously downloaded and unpacked and then select the file with the same name.  
Next, click on the run button in the top left below the "File" tab.  
The following window should appear:  

![title](https://github.com/JeyAl/internship/blob/master/images/converter.PNG)
Now click "open image file" and select your desired image. 
Then click on "download to minipov4" and it should successfully save the pattern to the minipov!  





