# atomo-all_boards
This is a collection of PCB designs for microcontroller development boards created for the Atomo line. We are releasing these files and designs to the world prior to our first production run. Any feedback on them is appreciated. 

Some basics:
1. We are releasing the raw design files and not the production silk screen with our commercial logo for Atomo. (We reserve the copyright on the Atomo brand.)
2. Yes, the refdes locations are on the parts for the most part. Earlier versions of the design attempted to keep all of the refdes markers in locations that could be used for silkscreen printing, but this required some very convoluted manual indications of what matches what. The density on these boards is just too high to have a clean 1:1 refdes printing on the boards. For the production silkscreens, we will be creating markings that is only for typical end use features and for major components or functional areas.
3. The 10-pin JTAG headers have been moved to the 26-pin/40-pin headers to reduce cost and to make all boards programmable using a Raspberry Pi or similar. 
4. Updated the 26-pin and 40-pin headers so that the pins are the same configuration for the first 26 pins. The 40-pin header is compatible with the ethernet adapter. 

So, this is the current state of the finished design files. To be added are the backplane and module files. The intent now is to try to move this into a more open development project to keep things growing. If you are interested in contributing, please contact the project. 
