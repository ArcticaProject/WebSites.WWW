.. pub: 1
.. link: 
.. description: Roadmap for Arctica Development
.. tags: 
.. date: 2015/05/14 06:18:30
.. title: Roadmap
.. slug: roadmap

# Arctica Server
* Arctica Core
    * ArcticaSSH | 08/2015 | 28d
    * Rewrite of Telekinesis draft [^1] for Arctica Server | 10/2015 | 28d
    * Server manager / session manager | 12/2015 | 56d
    * Server documentation | 12/2015 | 14d
* Graphical Components
    * nx-libs
        * nx-libs 3.6.x | 10/2015 | 21d
        * nx-libs 3.7.x | 01/2016 | 28d
    * utilize Gate One X11 [^2][^3] | N-A
* Audio Components
    * Pulseaudio | 03/2016 | 7d
    * GStreamer | 12/2015 | 14d
* Arctica Multimedia
    * mTelePlayer port to Arctica Server | 12/2015 | 14-28d
    * HTML5 / Flash / other-browser-media support | 12/2016 | 90-180d
* Client-side media
    * File sharing | 09/2015 | 7d
    * Printer sharing | 09/2015 | 7d
    * Misc USB device handling | 06/2016 | 21d
* Brokerage [^4]
    * Load balancing | 03/2016
    * WebGUI based on Django | 09/2016
    * VDI solution hooked into Ganeti | 09/2016 | 21d
    * VDI solution hooked into openStack | 06/2017 | N-A [^5] 
# Arctica Client
* Linux client (cmdline) | 12/2015 | 21d
* Linux client (GUIs)
    * Appindicator applet / systray applet | 12/2015 | 21d
    * Remmina plugin 03/2016 | 14d
    * Thin client frontend (based on Unity Greeter)  | 12/2015 | 14d
                         (or something different...)
* Web/Browser Client
    * noVNC websocket based browser plugin | 03/2016 | 14d
* Windows client (cmdline port, native GUI) | 06/2016 | 28d
* Mac OS X client (cmdline port, native Cocoa GUI) | 12/2016 | 56d
* Android, iOS, Chromebook, what-not later...

[^1]: http://code.x2go.org/gitweb?p=telekinesis.git;a=summary
[^2]: Once released / available
[^3]: Probably under a non-free license
[^4]: Arctica Server's server manager will contain 90% of the broker functionalities
[^5]: Only if contracted
