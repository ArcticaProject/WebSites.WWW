.. pub: 1
.. link: 
.. description: Roadmap for Arctica Development
.. tags: 
.. date: 2015/05/14 06:18:30
.. title: Roadmap
.. slug: roadmap

# Arctica Server
* core
    * ArcticaSSH | 08/2015 | 28d
    * Rewrite of Telekinesis draft [^1] for Arctica Server | 10/2015 | 28d
    * server manager / session manager | 12/2015 | 56d
    * server docs | 12/2015 | 14d
* graphics
    * nx-libs
        * nx-libs 3.6.x | 10/2015 | 21d
        * nx-libs 3.7.x | 01/2016 | 28d
    * utilize Gate One X11 [^2][^3] | N-A
* audio
    * pulse | 03/2016 | 7d
    * gstreamer | 12/2015 | 14d
* multimedia
    * mTelePlayer port to Arctica Server | 12/2015 | 14-28d
    * HTML5 / Flash / other-browser-media support | 12/2016 | 90-180d
* client-side media
    * file sharing | 09/2015 | 7d
    * printer sharing | 09/2015 | 7d
    * misc USB device handling | 06/2016 | 21d
* brokerage [^4]
    * load balancing | 03/2016
    * WebGUI based on Django | 09/2016
    * VDI solution hooked into Ganeti | 09/2016 | 21d
    * VDI solution hooked into openStack | 06/2017 | N-A [^5] 
# Arctica Client
* Linux client (cmdline) | 12/2015 | 21d
* Linux client (GUIs)
    * appindicator applet / systray applet | 12/2015 | 21d
    * remmina plugin 03/2016 | 14d
    * thin client frontend (based on Unity Greeter)  | 12/2015 | 14d
                         (or something different...)
* Web/Browser Client
    * noVNC websocket based browser plugin | 03/2016 | 14d
* Windows client (cmdline port, native GUI) | 06/2016 | 28d
* Mac OS X client (cmdline port, native Cocoa GUI) | 12/2016 | 56d
* Android, iOS, Chromebook, what-not later...
[^1]: http://code.x2go.org/gitweb?p=telekinesis.git;a=summary
[^2]: once released / available
[^3]: probably under a non-free license
[^4]: Arctica Server's server manager will contain 90% of the broker functionalities
[^5]: only if contracted
