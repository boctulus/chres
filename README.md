# chres
Change easly display resolution in Linux

Usage

    chres <options>
     
	Options:
     
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
    cd chres 
    sudo ln -s $(pwd)/chres /usr/bin		
