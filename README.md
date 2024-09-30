# VL.SuperCollider

Library to execute basic SuperCollider tasks in vvvv.
Basically a wrapper around *sclang* that generates simple commands to control the SuperCollider audio server.

Warning: Currently in development! Don't expect any gentle waltz yet.

Built upon [SuperCollider](https://vvvv.org) and [VL.SCSynth](https://github.com/cnisidis/VL.SCSynth).

## Credits
In collaboration with [Constantine Nisidis](https://www.nisidis.com/).

## Useful Ressources

### VL

Detect if a node is connected downstream<br />>
https://discourse.vvvv.org/t/detect-if-a-node-is-connected-downstream/20878

About disposing
https://discourse.vvvv.org/t/dispose-questions/21110<br />>

Starting the server<br />>
https://discourse.vvvv.org/t/start-supercollider-server-in-background/20532/4

### SuperCollider

Side by side comparison of direction communication vs. sclang<br />>
https://doc.sccode.org/Guides/NodeMessaging.html

OSC port for ingoing and outgoing messages<br />>
https://scsynth.org/t/reply-port-of-asychronous-commands/6494/2

Starting the server from VL<br />>
https://scsynth.org/t/start-sc-server-in-c/5803

Sending raw OSC commands to create Synths<br />>
https://scsynth.org/t/how-to-send-raw-osc-to-create-a-simple-sound/7166/6

Parsing SynthDef as binary format<br />>
https://scsynth.org/t/parse-synthdef-for-transmission-to-server/6497/6

### Others

Supriya SuperCollider implementation in Python<br />>
https://github.com/josiah-wolf-oberholtzer/supriya