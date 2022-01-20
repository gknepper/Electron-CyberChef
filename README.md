# Electron-CyberChef

Electron wrapper for CyberChef

To update CyberChef, Just expand all content of CyberChef_vX.XX.XX.zip in the root directory and rename the  CyberChef_vX.XX.XX.html to index.html.

- Based on https://github.com/electron-userland/electron-webpack-quick-start

- Created from v9.32.3 https://github.com/gchq/CyberChef/

- Depends on https://github.com/electron-userland/electron-builder

To create the mac DMG package run:

```
git clone https://github.com/gknepper/Electron-CyberChef
cd Electron-CyberChef
yarn add electron-builder --dev
electron-builder -m 
```
Installer will be created at Electron-CyberChef/dist/CyberChef-1.0.0.dmg
