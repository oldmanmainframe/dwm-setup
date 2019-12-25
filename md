[?1049h[>4;2m[?1h=[?2004h[1;55r[?12h[?12l[22;2t[22;1t[27m[29m[m[H[2J[?25l[55;1H"README" 48L, 1093C[1;1Hdwm - dynamic window manager
============================
dwm is an extremely fast, small, and dynamic window manager for X.


Requirements
------------
In order to build dwm you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dwm is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dwm (if
necessary as root):[19;5Hmake clean install


Running dwm
-----------
Add the following line to your .xinitrc to start dwm using startx:[26;5Hexec dwm

In order to connect dwm to a specific display, make sure that
the DISPLAY environment variable is set correctly, e.g.:[31;5HDISPLAY=foo.bar:1 exec dwm

(This will start dwm on display :1 of the host foo.bar.)

In order to display status info in the bar, you can do something
like this in your .xinitrc:[38;5Hwhile xsetroot -name "`date` `uptime | sed 's/.*,//'`"
    do[40;9Hsleep 1
    done &
    exec dwm


Configuration
-------------
The configuration of dwm is done by creating a custom config.h
and (re)compiling the source code.
[1m[38;5;242m~                                                                                                     [50;1H~                                                                                                     [51;1H~                                                                                                     [52;1H~                                                                                                     [53;1H~                                                                                                     [m[54;1H[1m[7m[38;5;242m[107mREADME   Line: 1/48[2%] Col: 1 Buf: #1 [100][0x64]                                                    ]2;README (~/temp/dwm-6.2) - VIM]1;README[1;1H[?25h[?25l[m[55;1HType  :qa  and press <Enter> to exit Vim[1;1H[?25h[?25l[?25h[?25l[55;1H[K[55;1H:[?2004h[?25hq![?25l[?2004l]2;/home/mikfer/temp/dwm-6.2]1;/home/mikfer/temp/dwm-6.2[23;2t[23;1t[22;2t[22;1t[23;2t[23;1t[55;1H[K[55;1H[?2004l[?1l>[?25h[>4;m[?1049l