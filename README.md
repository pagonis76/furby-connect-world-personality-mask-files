# furby connect world personality mask files
these are personality mask transitions found in a decompile of the Furby connect world
this also has a link to all the compiled personality files too, they have color palletes, sprites, motor movements, audio, sequences, actions, everything, and it can be found [here](https://github.com/Furby-ReConnect/Furby/tree/master/Furby-Files/Furby-NAND/Personalities)

# unused voicelines in the toy actually line up perfectly with these newly found files!
a set throwing/catching voicelines line up perfectly with the "ballminigame" file, and the personality dreams line up perfectly with the mask transitions

# instructions!
1. download the files (only the ones you want, not all of them if you don't want to, if you do, go ahead.
2. open the mask files with notepad or a text editor, there will be code that shows up.

# there is no known way to trigger these personalities... or is there?
there are codes that seem to be hex codes hidden in the mask files, what do they do? how do they work? we have no clue... YET.
the furby connect actually works off of BLE (bluetooth low energy) and people have figured out how to reverse engineer the furby connect, doing so, they've found the way to change varibles (mood, wellness, etc, about everything in the debug screen) the way to change them is to send certain hex codes to the furby (through NRF connect or a modded version of fluffd/bluefluff or even a modded version of furBLE). these hex codes in those files may have just unlocked something... something HUGE.

# there is no way to trigger the minigame in the furby connect world without a custom mod
yes, the minigame is compiled, it's in version 1.2.2 of the furby connect world app, it just can't be triggered... or can it?

# is it possibly possible to do this stuff? (this is me being silly with my grammer btw)
probably yes AND no.

# what have we found so far?
we've found what seems to be Hex codes in the format the furby connect usually reads, you can find these codes in the "furbymasks" file, then put the file into a hex editor.
i've found out the personalities on the english furby connect can be triggered with a russian sleep mask (the russian mask is wonky and has some sort of resister difference, Kawjer (on youtube) and a russian person (the person who has the russian furby and stuff) are currently documenting this and trying to find ways to trigger the personalities, I'm helping them as well.. well, trying to.
we've found more files inside the furby connect world, and appearently, the totem pole was originally supposed to be the personality changer. if you look at how the text inside those files are written, you can see it has references to a "furblinghub", most likely the main area, hasbro may have planned masks, then scrapped it, then planned the totem pole, but then gave up, scrapping the personalities completely.
