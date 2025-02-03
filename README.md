# TarkovDLSS4
Guide on how to implement DLSS 4 in tarkov WITHOUT Nvidia App

**Prerequisites:**

**DDU (Display Driver Uninstaller)** - https://www.wagnardsoft.com/display-driver-uninstaller-DDU-


**Nvcleanstall or NVslimmer** - 
https://www.techpowerup.com/download/techpowerup-nvcleanstall/ 
https://www.majorgeeks.com/files/details/nvslimmer.html



**Nvidia Profile Inspector** - https://github.com/Orbmu2k/nvidiaProfileInspector/releases



**CURRENT/LATEST NVIDIA DRIVER (572.16 or later)** - https://www.nvidia.com/en-us/geforce/drivers/





**This guide is going to be a step by step for a windows 11 only. I do not have a win 10 or any other OS on hand for testing!**

**Logic/Reasoning for this method:** I just don't like the nvidia app nor do I use any of the features included. AKA I consider it bloatware...
Thus being said this new feature is a great step in the right direction for them and I do believe its implementation to EFT is great for people that are struggling to run the game in its current state...


**How-To:**

**BEFORE DOING ANYTHING TO YOUR PC MAKE A RESTORE POINT ALWAYS!!!!!** (I cannot emphasize this enough). Take any screenshots of your current NVControl Panel settings if needed.

https://support.microsoft.com/en-us/windows/system-protection-e9126e6e-fa64-4f5f-874d-9db90e57645a

Step 1: Download your driver via the Nvidia site or use NVCleanstall as it has a downloader for current drivers built in
(for my own safety as well as not being liable for breaking anyones system I will NOT go into detail about how to debloat the drivers with either piece of software)

Step 2: **Download DDU**

Step 3: Reboot into safe mode - 

To Access The Windows Recovery Environment - Hold shift on your keyboard while performing a restart within windows and hold it down until you see you PCs or Windows 11 splash screen

![WinREtoSafemode](https://github.com/user-attachments/assets/c646d48a-21ff-4ef2-ae61-ba636f15a3e8)

Step 4: Run DDU and perform a clean driver removal (this will remove all nvidia components) without restarting

![DDU](https://github.com/user-attachments/assets/381d4d23-941c-454c-a09e-18b8bcde8ee0)

Step 5: Install the newly downloaded or debloated drivers you have on hand once installed reboot into the normal windows environment

Step 6: Launch Nividia Profile Inspector

6.a: Click the magnifying glass icon at the top of the program

![1](https://github.com/user-attachments/assets/1372604f-d65e-44f4-9681-a2355422b580)

6.b: Push Ctrl+F and look up the word "Over"
  
  Under the "Other" section you will see the "Override" switches
 
  **TARKOV ONLY SUPPORTS SUPER RESOLUTION**
  
  Thus being said Override DLSS-SR presets and Enable DLSS-SR override are the only two switches we will adjust
  
  **ALSO WE ARE CHANGING THESE UNDER THE GLOBAL PROFILE THIS WILL CHANGE DLSS IN ALL GAMES SUPPORTING DLSS**

![2](https://github.com/user-attachments/assets/c6a5e039-3d36-4514-9acc-4788d11337da)
