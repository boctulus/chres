# chres
Change easly display resolution in Linux

# How it works

It's a command tool utility, a "front-end" (also for the terminal) for xrandr. Just download.... give execution permission to the script and then run commands to change screen resolution.

Usage

    chres <options>
     
      Options:
     
      -s, --screen                    :0 is the default screen but it can be changed 
      -d, --display                   specify display interface (eDP-1-1,...)
      -r, --resolution                set display resolution
      -R. --reset                     set default resolution
      
      -h, --help                      display this help
      -v, --version                   display version


Examples

	chres       # menu is shown
	chres --resolution 1024x768 
	chres --resolution 1024x768 --display HDMI-1-2
	chres --display eDP-1-1 --reset
	chres --reset --display eDP-1-1 


How to install

    git clone https://github.com/boctulus/chres.git
    sudo ln -s $(pwd)/chres /usr/bin		
