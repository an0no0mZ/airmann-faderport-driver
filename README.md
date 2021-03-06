Airmann's Renoise Faderport driver is a sophisticated LUA tool, which integrates the PreSonus Faderport DAW Controller 
seamlessly into Renoise. Focus is laid on mixing, automation envelope creation, and general DAW control. 
This tool can seriously improve your workflow and mixing process.

License: Apache License 2.0 (http://www.apache.org/licenses/LICENSE-2.0)

Features:
- support of all FaderPort buttons, touch-sensitive motor fader, 
  endless pan control and lights (full bidirectional communication)
- Footswitch support for hands-free operation. You can connect an usual on/off footswitch to the FaderPort. 
  Footswitch has the same function as transport play. It's especially useful for hands-free 
  recording of audio and midi data.
- transport: play, play from position, stop, panic stop, forward, rewind, record / edit, loop, 
  block loop, block loop forward/backward
- track: mute, solo, select next track, select previous track, select master track, jump to song start / end, record sample
- pre-fx / post-fx volume / pan, and any DSP device parameter can be controlled
- currently selected track is automatically bound to FaderPort. Binding is displayed in status bar
- currently selected device/plug-in etc. can automatically be bound to FaderPort
- customizable navigation through device / plug-in parameters. 
  Relevant device parameter lists can be defined via preferences. Presets for all native devices are included.
- full automation envelope support: read, write, touch, latch mode
- 10 bit high resolution (1024 steps) for fader values (allows for precise mixing)
- endless pan control support with speed feature, adjustable virtual resolution (default 7 bit, 128 steps), 
  auto down scaling and adjustable "anti-suck" protection
- fader and pan controller can be swapped (e.g. fader controls stereo panning)
- fader value can be reset to Renoise default value (e.g. volume to 0 dB)
- fine trim mode: fader values can be fine trimmed via shift+pan control
- switch between views: mixer, pattern editor, sample editor
- sticky mode support: FaderPort controls can be sticked / bound to a specific track or device
- undo / redo support (experimental)
- Renoise status bar support (displays parameter bindings and value changes) 

If you find this driver usefull, you can support my further work with a donation:

DONATE VIA PAYPAL: 
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=DBKSZKFZA7CW8

LINKS:
http://airmann.de/
https://soundcloud.com/airmann
https://www.youtube.com/user/4irmann
