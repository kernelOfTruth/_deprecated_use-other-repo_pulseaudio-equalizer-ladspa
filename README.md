# pulseaudio-equalizer-ladspa
pulseaudio-equalizer-ladspa - patches, source, etc.

--------------------------------------------------------------------------------------

/etc/pulse/system.pa
might need 'load-module module-stream-restore restore_device=false'

--------------------------------------------------------------------------------------

The files to copy over to your installation are in the folder 'pulseaudio-equalizer'

--------------------------------------------------------------------------------------

Leave the ~/.config/pulse/presets folder empty,

otherwise the presets will occur twice !

--------------------------------------------------------------------------------------

Dependencies needed to get it working are:

media-libs/ladspa-sdk
media-plugins/swh-plugins

otherwise it will (more or less) silently fail
