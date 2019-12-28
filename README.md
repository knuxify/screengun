# Screengun

Screengun is a small, easily expandable screenshot utility helper written in POSIX sh. It is coded to use [maim](https://github.com/naelstrof/maim), however it can be easily modified to use any screenshot utility you'd like (as long as it can be called from the command line and save screenshots).

Screengun is a rewrite of the old ``screenshot-sorter`` utility, which was a daemon running in the background that collected screenshots. I eventually modded it to run maim directly, but it was still quite unwieldy, and as such I decided it was time for a rewrite.
