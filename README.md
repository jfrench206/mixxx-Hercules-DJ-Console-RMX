# mixxx-Hercules-DJ-Console-RMX
Controller mapping file for the Hercules DJ Console RMX, updated for Mixxx 2.1 by Jesse French

## Installation
Copy the file "Hercules-DJ-Console-RMX-hid-scripts.js" into your Mixxx controllers directory - see here for instructions: https://www.mixxx.org/wiki/doku.php/controller_mapping_file_locations

Note: if you're already using a previous version of the mapping, rename that file to something else, like "Hercules-DJ-Console-RMX-hid-scripts-old.js"

## Documentation
As in previous versions of this mapping file, Keys 1-4 set hotcues, 5 and 6 set loop begin and end points. The scratch function works, and you can "nudge" playing decks with the jog wheels when scratch is off.

Updates for Mixxx 2.1:

If you hold the Stop button on either deck, you can access a "Shift" layer which allows access to effects and looping functions.

Shift functions:
- If the deck is playing, Stop+Play is a vinyl brake effect. 
- If the deck is stopped, Stop+Play is a vinyl soft start effect. 
- Stop+|< button (previous) decreases Beatloop size
- Stop+>| button (next) increases Beatloop size
- Stop+5, while held down, turns Reloop on for a rolling loop of the given size
- Stop+6 is a normal loop toggle - so if you've set the loop points with 5 and 6, and it's looping, you can turn off the loop with this key combo

FX:
- Stop+treble kill turns on/off effect 1
- Stop+treble knob controls meta knob for effect 1
- same as above for medium and bass kill switches and knobs (for effects 2 and 3)

Other changes:
- Head volume goes to 100%
- Tweaked crossfader behavior for true silence when all the way to one side

## Credits
Original mapping created by RichterSkala, with contributions from Markus Kohlhase.
