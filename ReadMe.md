# METPlus VSCode Environment
## Intro
This repo shows how to get easily started with METPlus

## Setup
1. Download and Install VSCode [here](https://code.visualstudio.com/download)
2. Install Remote Container Extension for VSCode [click the install button](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
3. Download Docker Desktop [here](https://docs.docker.com/engine/install/)
4. Open VSCode, and then open the command palette by going to `View` > `Command Pallette`: type Git clone > copy the URL (This: https://github.com/YakelynRJ/Metplus.git) and clone the Metplus repository and choose a directory container in your laptop.
5. Make sure Docker is running and open the command palette by going to `View` > `Command Pallette`: type Open folder in container and select the Metplus directory you created in step 4 (ignore git upgrade notification)
6. Click in the open workspace button in bottom-rigth notification.
7. Type <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>~</kbd> or click on terminal > new terminal, make sure you choose metplus directory that contains METplus and METplus_Tutorial
9. Voila...Follow the rest of the tutorial instructions [here](https://dtcenter.org/metplus-practical-session-guide-version-3-0/session-1-metplus-setupgrid-grid/metplus-setup/metplus-user-configuration-settings).
10. If you want to work with jupyter nootebook in jupyter lab you can open a new terminal  in the local-repo directory and run 
```bash
. start-jupyter.sh
```
and click on Open in Browser notification. 

## Mounting local folder
If you want to link an external folder or drive to the container from your personal machine, please update the container creation [configuration](/.devcontainer/docker-compose.yml). 

If you already opened your folder in a container in Visual Studio Code, you may need to rebuild the container by pressing <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>P</kbd>.
Rebuild and Reopen Folder in Container. This will recreate your container to mount your data directory. 

To verify that the mounting was succesful, list out the files in the directory:
```shell
ls /data_input
```
## Getting latest changes
If you want to get the latest changes for this repository perform a git pull by executing the command below in the terminal:
```
git pull
```

