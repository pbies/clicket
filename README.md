# clicket 1.0.1

	https://github.com/pbies/clicket

Changed startup to system tray, no window on screen at startup.

Used Claude AI to fix some bugs.

Install nvm-setup.exe from https://github.com/coreybutler/nvm-windows/releases

Run in pwsh (use your version numbers):
```
nvm install latest
nvm use 26.7.0
npm install -g npm@12.0.2

npm install --save-dev @electron/rebuild --ignore-scripts
npx electron-rebuild -f -w global-mouse-events
npm run build-installer
```
and run then the installer from "dist" folder.

Original work:

	https://github.com/spreyo/clicket



# clicket
Inspired by  hainguyents13's [Mechvibes](https://github.com/hainguyents13/mechvibes), clicket is an app  that plays clicking sounds when you click your mouse. Clicket uses  the ElectronJS framework and React. 

# Installing
The app is currently only available for windows, but I plan on adding support for more platforms.

### Windows 
To install the app on Windows, download the  setup file from [releases](https://github.com/spreyo/clicket/releases)  and follow the instructions. 
# Sound Packs
Currently, there are 8 default sound packs pre-installed, but it is possible to add your own packs.

To add a new sound pack, navigate to the ***./sounds*** directory , create a new folder and put the ***click.mp3*** in it. The new sound will then be available after restarting the app.

>   ./sounds/MyCustomPack/click.mp3

# Screenshots

![](/clicket.png?raw=true)
