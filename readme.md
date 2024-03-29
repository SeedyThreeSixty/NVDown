# NVDown, by Seedy-Threepio!
Want an easy, speedy way of downloading virtually any version of the NVDA screen reader you want? Look no further than NVDown!
**
# What is NVDown, I hear thee cry
When you go to download the NVDA (Non-Visual Desktop Access) screen reader from the [NV Access download page](https://www.nvaccess.org/download), you only have the option of downloading the latest available version of NVDA. But what if you're running an older version of Windows, either inside a virtual machine or on physical hardware, that requires a specific version of the popular open source screen reader, you like how a certain version works better than another one, or you just want to experiment?
NVDown solves this problem by giving you the freedom to download and install virtually any version of NVDA you desire, from the very highest version, way down to version 2013.3!
## Notes
- NVDown only supports downloading NVDA versions down to 2013.3.
- Only final versions of NVDA are supported. This means you cannot use NVDown to download alpha, beta or RC (release candidate) versions of NVDA. You will get the most reliable, stable NVDA experience from the final version since it will have been extensively tested and refined prior to public release.
**
# NVDown System Requirements
Since NVDA is a Windows-only screen reader, NVDown is only compatible with, and will only run on, the Windows operating system.
You need at least Windows XP in order to run NVDown. I recommend Windows XP SP 3, however SP 2 might work; I don't have it installed on anything to test it with.
**
# Launching and Using NVDown
## Launching NVDown
Perform the following steps to launch NVDown.
- Extract the NVDown.zip file to a location of your choice. I'll assume you have enough computer smarts to extract zip files. If not, there's a little thing called a search engine which I highly recommend you use. :)
- Navigate to the location within which the extracted NVDown files are housed, and open the file called NVDown.exe. Windows doesn't show file extensions by default, so the filename will probably show as NVDown. Configuring Windows to show file extensions is beyond this guide.
## Using NVDown
After you open the NVDown.exe file, a terminal will appear. If you don't see the terminal window straight away, press Alt + Tab until you land on it. Inside the terminal, you'll be prompted for the following things. When you're finished entering data, press Enter to confirm the input and proceed to the next prompt.
- The version of NVDA you wish to download. This can be any value from 2013.3 to... well, there isn't really an upper limit for now. Currently, the highest version of NVDA is 2021.3. The value must end in either .1, .2, .3 or .4. There are no .0 releases of NVDA, as the version number format is year.quarter.
- A patch/minor version number. Sometimes, a small bugfix update will be released shortly after a major new NVDA release. These updates iron out little niggles in a major release that maybe didn't get caught during alpha/beta testing. These small releases are typically sufffixed with .1. For example, 2019.2.1 or 2021.3.1. If 2019.2.1 was what you wanted, you'd enter 2019.2 into the version field, and the number 1 into the patch field. If you want to download NVDA without any patches/hotfixes, simply leave this field blank.
When all required information has been supplied, NVDown will go out and download the installer for your desired version of NVDA. Rest assured that all downloads performed with NVDown are 100% official, since the files come directly from the NV Access website. Everything is left untouched, including the original filenames of NVDA installers.
Once the download has completed, you will be asked if you want NVDown to launch the NVDA installer for you or not. To have NVDown launch the installer automatically, type the number 1. If you want to launch the installer yourself, type the number 2 and NVDown will exit.
When NVDown launches the NVDA installer, it simply starts the executable and exits. No arguments are passed to the installer, leaving you free to configure your NVDA installation as you wish.
**
# Error Handling and Logging
In the event that NVdown runs into an error, such as being unable to connect to the NV Access website, an error log will be generated and an error message displayed inside the terminal. The error log, called ErrorFile.log, will be written to NVDown's program folder and can be opened with any text editor you like, be it Notepad, Notepad++, Vim etc.
Error logs generated by NVDown contain the following information.
- The exact date and time at which the error occurred.
- The type of error that occurred, like a user input related error or an error connecting to NV Access.
- A brief summary of what error was encountered and why it happened.
- The actual error message, as obtained from traceback data. This is really only for the developer's knowledge, users will get a much friendlier error message inside the NVDown terminal. Yay for abstraction, I guess.
Please try to include this log file, if applicable, when filing an issue on GitHub.
**
# Known Issues
It might take a short while for NVDown to connect to the NV Access site. I'm not sure why this happens, it could just be my internet connection.
# Credits
The NVDA screen reader is developed and maintained by NV Access, an Austrailian organization that aims to provide free access to computers and the internet for blind/visually impaired people the world over. The NV Access philosophy is simple. Neither cost nor blindness should be a barrier to people's access to any form of digital technology.
Thanks to an ever-growing list of volunteers, the Non-visual Desktop Access project continues to grow and evolve through the use of add-ons that allow for the limitless expansion and customization of the life-changing screen reader!
• [Visit the NV Access website](https://www.nvaccess.org)  
• [Follow NV Access on Twitter](https://www.twitter.com/NVAccess)  
• [The NVDA add-on repository](http://addons.nvda-project.org/)  
