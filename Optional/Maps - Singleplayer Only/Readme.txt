What Do These Do?
These versions of the maps include day-night cycles, allow 1 of 3 civ-specific starting music files to play before the main soundtrack, and allow a voice line spoken by Explorers to play (non-Europeans play a culture-related sound instead).

Why Are They Singleplayer Only?
The map scripts that perform these functions cause OOS (Out of Sync) errors to occur in multiplayer; therefore, they have been excluded by default. 

You can switch between these and the default MP-safe maps by copying the RMF folder found in "bin", renaming it something else (e.g., RMF-MP), and pasting the singleplayer-only RMF folder into "bin". 
Then if you need MP-compatible maps again, rename RMF to something like "RMF-SP", and rename your MP-safe folder ("RMF-MP" in my example) to just "RMF."
Finally, in "bin->Data", remove or rename "resources.xml".

Installation instructions: 
Drag the included "bin" folder over your AoE3's "bin" folder. Overwrite when prompted (unless you want to preserve the MP-compatible files, in which case do as written above, and re-add or rename "resources.xml" to Data).