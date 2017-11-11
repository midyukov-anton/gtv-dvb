## GTV 1.0

- Digital TV player
- DVB-T/T2, DVB-S/S2, DVB-C


![alt text](screenshots.png "Preview")


### Requirements:
- Graphical interfaces - [Gtk+3](https://developer.gnome.org/gtk3)
- Audio & Video & Digital TV - [Gstreamer 1.0](https://gstreamer.freedesktop.org)

### License:
- [GNU LESSER GENERAL PUBLIC LICENSE](http://www.gnu.org/licenses/lgpl.html)

### Depends:
- gtk+3, gstreamer, gst-plugins-base, gst-plugins-good, gst-plugins-ugly, gst-plugins-bad, gst-libav

### Compile:
- sh scripts/compile.sh
  
### Install ( home ):
- sh scripts/install-home.sh

### Uninstall ( home ):
- sh scripts/uninstall-home.sh


### Channels:
- Scan channels manually ( Ctrl + U ).
- Convert - dvb_channel.conf ( format [DVBv5](https://www.linuxtv.org/docs/libdvbv5/index.html) ).
	
- dvb_channel.conf - created by command: [dvbv5-scan](https://www.linuxtv.org/downloads/v4l-utils) [OPTION...] [initial file](https://www.linuxtv.org/downloads/dtv-scan-tables)

### Record:
- Encoder
- Ts


