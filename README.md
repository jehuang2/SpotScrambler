This is python code meant to scramble particles of binary images. 
Code will produce new images of scrambled particles redrawn as circles. 

Methods from Pournjati et al.
Images were binarized as .tif images, and their respective cell perimeter coordinates were exported as .csv files by ImageJ (NIH). Processed binary images were then analyzed by our SpotScrambler Python program. SpotScrambler first extracts the areas of fluorescent particles in the binary image. SpotScrambler then redraws the fluorescent particles as circles at randomized coordinates within cell perimeter boundaries. SpotScrambler accurately preserves particle number and particle sizes, averaging less than 1% difference in total area of fluorescent particles between pre-SpotScrambler and post-SpotScrambler images. To ensure reliable randomization for each experiment, results were averaged between 3 trials of SpotScrambler.
