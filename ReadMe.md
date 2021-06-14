# METPlus VSCode Environment
## Intro
This repo shows how to get easily started with METPlus

## Setup
1. Download and Install VSCode [here](https://code.visualstudio.com/download)
2. Install Remote Container Extension for VSCode [click the install button](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
3. Download Docker Desktop [here](https://docs.docker.com/engine/install/)
4. Open VSCode, and then open the command palette by going to `View` > `Command Pallette`: type Git clone > copy the URL and clone the Metplus repository and choose a directory container.
5. Open the command palette by going to `View` > `Command Pallette`: type Open folder in container and select the Metplus directory you created in step 4 (ignore git upgrade notification)
6. Click in the open workspace button in bottom-rigth notification.
7. Type CTRL + SHIFT + TILDE or click on terminal > new terminal, make sure you choose metplus directory that contains METplus and METplus_Tutorial
9. Voila...Follow the rest of the tutorial instructions [here](https://dtcenter.org/metplus-practical-session-guide-version-3-0/session-1-metplus-setupgrid-grid/metplus-setup/metplus-user-configuration-settings).
10. If you want to work with jupyter nootebook in jupyter lab you can open a new terminal  in the local-repo directory and run 
```bash
. start-jupyter.sh
```
and click on Open in Browser notification. 
