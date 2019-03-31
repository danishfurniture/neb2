# neb2
Code for the Qu-Bit Nebulae 2 eurorack module

Read.me

This readme file accompanies the Neb2 firmware (v 2.1.1.01) file uploaded on 30 March 2019. 

The firmware file is named: neb_update.zip

That is the name that the Neb2 module requires in order to be recognized as a firmware update file.

This firmware is not an official firmware from Qu-Bit. Please use at your own risk.

If you choose to use this firmware file, please install it according to the instructions available on the Qu-Bit website.

This firmware file is based on the firmware 2.1.1 from Qu-Bit. Two changes have been made to the Qu-Bit firmware:

a) The code has been changed so that the module will now boot up correctly after it was shut down while an instrument from the user bank was loaded and playing. 

b) The fifth instrument (rightmost button) in the factory bank has been replaced with a new instrument. The fifth instrument in the official 2.1.1 firmware is a test instrument. (You can get the test instrument from Qu-Bit's website.) The new instrument file on this firmware is named, "e_newsize01.instr". It is a clone of the main instrument of the Neb2 module (a_granularloop.instr) with a change to the way that the 'start' and 'size' functions interact. In the original instrument (which is still on this firmware, in the same place), changing the 'start' control also changes the size of the loop. In the new version, changing the 'start' control has no effect on the size of the loop. This allows one to sweep through their loop without changing the size of the loop length and speed at which the loop plays.

It is possible that this firmware file will be updated as changes and/or improvements are made.

If you have trouble with this firmware file, please reinstall the official firmware from Qu-Bit to restore the previous functionality to your module.
