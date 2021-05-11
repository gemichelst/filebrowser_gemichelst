# filebrowser@gemichelst

![GEMICHELSTCLOUD](./assets/raw/logo-nc-gemichelst-white-new-transparent-square@0.5x.png)

filebrowser for armv7 (rpi,bpi etc) with install script, customized design and configuration

## INSTALLATION
clone this repo, go into the directory and run the Installer.
You will need specific permissions for creating dirs and users. Be sure you are root or something similar.
```bash
git clone git@github.com:gemichelst/filebrowser_gemichelst.git
cd filebrowser_gemichelst
bin/filebrowser-installer
```

## CONFIGURATION
you can configure your filebrowser server with the file 'conf/filebrowser.json'.
There you can change the port, ip etc. 

## STARTING
after the installation script has finished a systemd service was created.
after a reboot the filebrowser server will autostart but you can also use this command to start it:
```bash
sudo systemctl start filebrowser@filebrowser.service
```

## THANKS
thanks to the devs from filebrowser. They made this amazing simple and fast filebrowser.
You will find the original amazing source at: [github.com/filebrowser/filebrowser](https://github.com/filebrowser/filebrowser)
