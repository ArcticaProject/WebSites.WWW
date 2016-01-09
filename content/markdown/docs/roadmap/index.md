.. pub: 1
.. link: 
.. description: Roadmap for Arctica Development
.. tags: 
.. date: 2016/01/09 22:16:30
.. title: Roadmap
.. slug: roadmap

# Arctica Server
* Arctica Core
    * ArcticaSSH | 02/2016 | 28d
    * Rewrite of Telekinesis draft [^1] for Arctica Server | 05/2016 | 28d
    * Server manager / session manager | 10/2016 | 56d
    * Server documentation | 10/2016 | 14d
* Graphical Components
    * nx-libs
        * nx-libs 3.6.x | 02/2016 | 21d
        * nx-libs 3.7.x | 02/2017 | 28d
    * utilize Gate One X11 [^2][^3] | N-A
* Audio Components
    * Pulseaudio | 06/2016 | 7d
    * GStreamer | 03/2016 | 14d
* Arctica Multimedia
    * mTelePlayer port to Arctica Server | 05/2016 | 14-28d
    * HTML5 / Flash / other-browser-media support | 06/2016 | 90-180d
* Client-side media
    * File sharing | 09/2016 | 7d
    * Printer sharing | 09/2016 | 7d
    * Misc USB device handling | 06/2016 | 21d
* Brokerage [^4]
    * Load balancing | 12/2016
    * WebGUI based on Django | 03/2017
    * VDI solution hooked into Ganeti | 03/2017 | 21d
    * VDI solution hooked into openStack | 06/2017 | N-A [^5] 
# Arctica Client
* Linux client (cmdline) | 03/2016 | 21d
* Linux client (GUIs)
    * Appindicator applet / systray applet | 06/2016 | 21d
    * Remmina plugin 09/2016 | 14d
    * Thin client frontend (based on Unity Greeter)  | 10/2016 | 14d
* Web/Browser Client
    * noVNC websocket based browser plugin | 12/2016 | 14d
* Windows client (cmdline port, native GUI) | 06/2017 | 28d
* Mac OS X client (cmdline port, native Cocoa GUI) | 12/2017 | 56d
* SailfishOS, Android, iOS, Chromebook, what-not later...

[^1]: http://code.x2go.org/gitweb?p=telekinesis.git;a=summary
[^2]: Once released / available
[^3]: Probably under a non-free license
[^4]: Arctica Server's server manager will contain 90% of the broker functionalities
[^5]: Only if contracted
