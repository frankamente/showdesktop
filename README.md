# showdesktop
Resources for adding "show desktop" icon on Plank (default dock on elementary OS Freya).

##Install:

The first step, install `wmctrl` package:

    sudo apt-get install wmctrl

Next step, download and install script:

    cd /tmp && wget https://github.com/png2378/showdesktop/archive/master.zip
    unzip master.zip && cd showdesktop-master
    sudo mv showdesktop /usr/local/bin/ && sudo mv showdesktop.desktop /usr/share/applications/ && sudo mv showdesktop.svg /usr/share/icons/elementary/apps/48/

The finish step, add icon on Plank:

    mv showdesktop.dockitem ~/.config/plank/dock1/launchers/
    
Result:

[![][1]][1]

  [1]: http://i.stack.imgur.com/cwhXi.png
