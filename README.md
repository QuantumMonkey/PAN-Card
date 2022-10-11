# PAN-Card
A Computer Vision based project to process a PAN Card image to check its authenticity.

We use the structural_integrity module from the skimage package to check the provided image data against a generic template of a valid PAN Card. After checking and validating, it is recommended to run the PAN though the Income Tax database to check for fraud.

We can say that the image provided by the user is fake or genuine based on the Structural Similarity Index calculated by comparing the two images. We visualized the differences and similarities between the images used by displaying the images with contours, difference and threshold.

#
