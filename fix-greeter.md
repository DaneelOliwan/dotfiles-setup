# create a script
sudo echo "xrandr -s 1920x1080" > /etc/X11/Xsession.d/45custom_xrandr-settings 
sudo echo "display-setup-script=/etc/X11/Xsession.d/45custom_xrandr-settings" > /etc/lightdm/pantheon-greeter.conf"
