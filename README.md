# Nautilus-Nemo-Hide

These are two extensions for Nautilus and Nemo to hide files through the context menu.  
Nautilus-hide project is from https://github.com/Jason-Wood/nautilus-hide  
Nemo-hide project is from https://github.com/KDB2/Nemo-hide  

1. These are dependencies that you need to install for these extensions to work
    * cmake
    * gettext
    * xdotool
    * python-nautilus
    * python-nemo
    
2. Using admin previlege in a file manager, copy the .py to the appropriate folder
    > sudo cp nautilus-hide.py /usr/share/nautilus-python/extensions  
    > OR  
    > sudo cp nemo-hide.py /usr/share/nemo-python/extensions
    
3. Restart the file manager to reload the extensions
    > nautilus -q  
    > OR  
    > nemo -q
