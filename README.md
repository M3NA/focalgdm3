# focalgdm3

_**This script assumes that the Installation of Ubuntu 20.04 is a fresh install. If you tried to change the GDM background with someother scripts, you first need to reset those changes. Other scripts may have the option --reset.**_

Change the login screen background for Ubuntu 20.04 and 21.04
this script is to change the login screen background of Ubuntu 20.04 and 21.04.


you can download the `focalgdm3` file via command line

    wget -qO - https://github.com/PRATAP-KUMAR/focalgdm3/archive/TrailRun.tar.gz | tar zx --strip-components=1 focalgdm3-TrailRun/focalgdm3

Once you downloaded the script `focalgdm3`. cd to the downloaded script file.

to set the background with Image  
`sudo ./focalgdm3 /absolute/path/to/image`

to set the background with color  
`sudo ./focalgdm3 \#aAbBcC` replace `#aAbBcC` with any vaid hex color code..

to reset everything that the script made..  
`sudo ./focalgdm3 --reset`

![result of Image](https://i.stack.imgur.com/ssYjj.png)

![result of Image with OSK](https://i.stack.imgur.com/xcpwT.png)

![result of color](https://i.stack.imgur.com/KmliD.png)

![result of color with OSK](https://i.stack.imgur.com/TFWP5.png)
