---
title: "Deploying a Win32 App via Intune"
date: 2022-12-29T15:28:33Z
---


## Pre Reqs

* Download the IntuneWin32Util from [Here](https://docs.microsoft.com/en-us/mem/intune/apps/apps-win32-prepare).

* Download the 7-Zip MSI from [Here](https://www.7-zip.org/download.html)
  


1. Create a Folder for your App

    ![](/images/7zip-folder.png) 

2. Copy your 7zip MSI to the folder you just created (This is to keep the copy for record)
   
3. Create a folder on your computer to store the MSI in while we convert it, this is to avoid packing un needed files into the intune installer eg:

    ![](/images/20220425095948.png)  

4. Navigate to where you downloaded the Intune App tool and double click on it to run it.

    ![](/images/20220425100117.png)  

5. For the Source folder, enter the path that you stored the 7Zip MSI locally on your machine and press enter
    
    ![](/images/20220425100222.png)  

6. Enter the file name of the MSI inside the folder and press enter.

    ![](/images/20220425100309.png)  

7. Enter the output folder, this is where you want the Intune file to be created and press enter.

    ![](/images/20220425100352.png)  

8. Specify if you want to add a catalogue folder (no if you are unsure) and press enter.
    
    ![](/images/20220425100449.png)  

9.  The tool will the create a .intunewin file in the output folder you specified, this file is what you will upload to Intune.

    ![](/images/20220425100545.png) 

    