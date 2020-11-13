# Nord Lead 3 Librarian

A simple MacOS-only librarian and patch arranger for the Nord Lead 3.

Written in Swift.

Universal binary, supports Apple Silicon (ARM64) as well as Intel.

Version 1.0 is licensed under CC-BY-ND 4.0. Please read the LICENSE.txt file for more information and a link to the full license text.

## Installing

1. Download the zip file and unzip it somewhere.
1. Drag the "Nord Lead 3 Librarian" executable to your Applications folder. 
1. RIGHT-click (not double-click) on the "Nord Lead 3 Librarian" executable inside your Applications folder and choose "Open" from the popup menu.
1. In the dialogue box that opens, click "Open" again. 
1. The program should henceforth open normally on subsequent attempts. 

## Quick start

1. Connect your Nord Lead 3 to your Mac via MIDI in some manner.
1. In the Nord Lead 3 Librarian, click the MIDI toolbar icon and choose the input and output ports. The MIDI icon will go green if the ports were opened successfully. This does NOT mean it sees your NL3 though, just that it opened the ports ok. 
1. In the MIDI menu, select "Fetch all from synth". 

If the MIDI communications are successful, this should query the NL3 and retrieve all programs and performances from it. At this point you should absolutely make a backup of your synth's memory by saving (File->Save) what you've just loaded, before messing further with it. Then you can drag and drop, rename, reorder, import from other sysex files in part or completely, and do a variety of other operations to manage the sysex data. It should behave largely similarly to the Nord librarians provided for their newer synths. 
