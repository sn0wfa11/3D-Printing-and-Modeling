# Slic3r PE Install and Setup for Ender 3

## Download and Install
Currently there are two versions of Slic3r PE, the stable official release (1.41.x) and the in development 1.42.0 version.

### Official Release
- Download from Prusa's website using the link below. Look for the "Drivers & APPS X.X.X" link and select your correct OS. 
- For Windows, the download is an installer executable that gives you options for which components you would like to install.

https://www.prusa3d.com/drivers/

### Development Version 
- The development version can be downloaded from Prusa's GitHub page on the releases tab as linked to below:
- Scroll down to the "Assets" portion of the most resent 1.42.0 release and select the download for your OS.
- For Windows
  - Select the proper OS type, 32 or 64 bit.
  - The download will be a .ZIP file. Extract this to a regular folder in the location of your choosing.
  - To run slic3r PE, double click the `slic3r.exe` file in the folder that you extracted the .ZIP file to.
  - You can make a link on your desktop to this file by left clicking then selecting New | Shortcut. Browse to the location of `slic3r.exe` and then set the shortcut name.
  - You may be presented with a SmartScreen message. Click "More info", the click the "Run anyway" button.
- For Mac, the download is a normal DMG file. Install as usuall for that package type.
- For source code install, you will need to follow the build and install instructions in the Github Repo.

https://github.com/prusa3d/Slic3r/releases

## Initial Setup
### 1.41.x
- Open slic3r PE and you will be presented with a Configuration Wizard.
  - If you have Prusa printers or would like to set up your own custom printer you can follow the wizard.
    - Also, adding a printer in the wizard will provide you with Prusa’s settings for various filaments.
    - Add a MK3 or generic printer and then you can remove it later.
  - If you don't care about any of Prusa's settings, click "Cancel".
- Download my provided profile to your computer.
- - In slic3r PE, click File | Load Config Bundle...
- Select the profile you just downloaded for import, then click "Open". The config bundle will import.
- Under each tab at the top you should now see profiles for "Ender3"
- Go through and adjust settings for your printer setup.

### 1.42.0
- Open slic3r PE and you will be presented with a Configuration Wizard.
  - If you have Prusa printers or would like to set up your own custom printer you can follow the wizard.
    - Also, adding a printer in the wizard will provide you with Prusa’s settings for various filaments.
    - Add a MK3 or generic printer and then you can remove it later.
  - If you don't care about any of Prusa's settings, click "Cancel".
- Download my provided profile to your computer.
- In slic3r PE, click File | Import | Import Config Bundle...
- Select the profile you just downloaded for import, then click "Open". The config bundle will import.
- Under each tab at the top you should now see profiles for "Ender3"

**Profile Configuration Note (README!)**
- **There are different levels of setting views; Simple, Advanced, and Expert. Moving up the selection will show more settings**
  - To change the settings views go to Configuration | Mode, then select the view you would like.
  - Simple settings have green next to them.
  - Advanced settings have yellow next to them.
  - Expert settings have red next to them.
- Go through and adjust settings for your printer setup.
