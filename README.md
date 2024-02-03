# Configuration for ChimeraX

This is my configuration for [UCSF ChimeraX][chimerax]. I took most of Oli
Clarke's (@olibclarke) [configuration][oli-config] as a starting point, tweaked
a few things and added other things I often use. I also organized it in one main
initialization file (`init.cxc`) that opens other files, allowing me to group
things that are related and to selectively disable some configuration if
necessary (by simply commenting the corresponding line in `init.cxc`).

To use this configuration, clone the repository or download its current state,
then in ChimeraX's [Startup settings][startup-settings] add the path to the
`presets` directory in "Custom presets folder" and add `open /path/to/init.cxc`
in "Execute these commands at startup". 

[chimerax]: https://www.cgl.ucsf.edu/chimerax

[oli-config]: https://github.com/olibclarke/chimerax-trimmings

[startup-settings]: https://www.cgl.ucsf.edu/chimerax/docs/user/preferences.html#startup
