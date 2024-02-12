# Configuration for ChimeraX

This is my configuration for [UCSF ChimeraX][chimerax]. I took most of Oli
Clarke's ([@olibclarke][oli]) [configuration][oli-config] as a starting point,
tweaked a few things and added other things I often use. I also organized it in
one main initialization file (`init.cxc`) that opens other files, allowing me to
group things that are related and to selectively disable some configuration if
necessary (by simply commenting the corresponding line in `init.cxc`).

To use this configuration, clone the repository or download its current state,
then in ChimeraX's [Startup settings][startup-settings] add the path to the
`presets` directory in "Custom presets folder" and add `open /path/to/init.cxc`
in "Execute these commands at startup". 

Alternatively, you can copy individual files to your own configuration, but
mind that there are some dependencies between files (so that I only need to
edit one file when I want to change a setting used in several places).

[chimerax]: https://www.cgl.ucsf.edu/chimerax

[oli]: https://github.com/olibclarke

[oli-config]: https://github.com/olibclarke/chimerax-trimmings

[startup-settings]: https://www.cgl.ucsf.edu/chimerax/docs/user/preferences.html#startup

