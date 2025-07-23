**_Welcome to my custom Polybar Themes!_**


### *GETTING STARTED*

*_In order to use the themes provided install poly-bar through: [https://github.com/polybar/polybar](https://github.com/url)_
*_Here is a guide for learning on how rofi works and what it does: [https://github.com/davatorium/rofi](url)_

_Or run this in terminal for **Ubuntu/Mint Users**:_

```
sudo apt install polybar
```

 **_In order for the custom menu to work you need rofi, you can install rofi by typing:_**
```
sudo apt update
sudo apt install rofi
```

First, install the themes package by installing this zip: 
[PlaguesPolybarThemes.zip](https://github.com/user-attachments/files/21393241/PlaguesPolybarThemes.zip)

Inside the [PlaguesPolybarThemes.zip](https://github.com/user-attachments/files/21393241/PlaguesPolybarThemes.zip) you should see folders inside with theme names select which theme you would like by clicking each folder and seeing the previews. Once you find a folder to your liking, select the folder and click the README file in order to recieve futher instruction for installing and setting up!

Your Folders should look like this: 

<img width="512" height="254" alt="Image" src="https://github.com/user-attachments/assets/cfd1b6a1-cbf0-4b77-bd37-7650c9740def" />

<img width="512" height="383" alt="Image" src="https://github.com/user-attachments/assets/6ba603e4-9df9-4a2b-ae75-3d06d9f7a7e7" />

### *PATH SETUP (IMPORTANT!)*

Your new **polybar** will be located in **_/etc/polybar_**
Under this folder you will see a **_config.ini_**

*In order to locate **_.config_** You need to see your hidden folders use the shortcut: `CTRL+H` *
In order for this custom theme to work you need to make a new path

-Go to **_/home/.config_** 
-Create a new folder called **"_polybar_"** 
-You now should a new location it should look like: **_/home/.config/polybar_**

**_Your path is all setup!_**

### *INSTALLATION*
**_**Make sure you delete your topbar you currently have!**
*Depending on the distro the GNOME enviormental topbar will block polybar so delete it*_**

-Delete everything inside **_/home/.config/polybar_** 
-Open the zip file: [PlaguesPolybarThemes.zip](https://github.com/user-attachments/files/21393241/PlaguesPolybarThemes.zip)
-Select which theme folder you want. Example: _**GlacierTheme**_
-Then inside the folder select everything 
-Paste it into the _**polybar**_ folder 

You should have your custom theme! 
To test it open up terminal and drag the **_launch.sh_** in there and press `ENTER`
In order to close it just type in `killall polybar` this will close it 

### *FINAL SETUP*

-Open up `Startup Applications` in your Linux menu
-Click on `ADD`
-Name it **_polybar_** and inside command paste in
-Make sure **_YOURLINUXUSER_** is replaced with whatever **_user_** you have in your file
`/home/YOURLINUXUSER/.config/polybar/launch.sh`
-Make sure it is toggled on
-Reboot your pc

**_Enjoy your new beautiful desktop topbar!_**

