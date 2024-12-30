# FTC-CenterStage-ScoringAlgorithm
A scoring algorithm I made a few years ago for the CenterStage FTC season. It is supposed to determine the optimal place for a "pixel" on the "backdrop" based on that pixel's color and the current setup of the "backdrop." I did not get to test it during the season as we had trouble with the cameras. 

Keep in mind the pixel's are hexagonal, allowing for six neighbors at most, and pixels can only be stacked in the backdrop in an alternating fashion of "short rows" and "long rows," with the short rows allowing for one less pixel than the long rows. 

For scoring, the color of the pixel by itself does not matter (at least in the teleop period), but if it is in a group of three pixels of the same color or of all different colors, it is in a "mosaic" that earns additional points. 

I will periodically update it for fun as it would be a shame to leave this mass of code to rot.

