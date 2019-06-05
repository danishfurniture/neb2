This folder is for instr files for the Qu-Bit Neb2 eurorack module.


#### NOTE: As of 04 Jun 2019, the instrument in this folder has NOT yet been updated to take advantage of the new firmware.

#### windowAltSwap.instr
This instrument is identical to the Qu-Bit granular looper instrument, except that the 'window' and window_alt' functions have been swapped. For this instrument, the default behavior for the window control is:
* Stochastic grain masking.
* Increasing this control will mute random grains.
* The stochastic masking is calculated for left and right channels separately. When set fully counter-clockwise, no grains will be muted.
* When set to the middle, half of all grains will be muted.
* When set fully clockwise, 99% of all grains will be muted.
