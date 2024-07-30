This is ReadME file for Part 4

### Flowchart for the algorithm used

Start by loading the template picture.

Take the template image's coordinates for the black pixels.

Use PCA (Principal Component Analysis) to identify the first eigen vector (reference line) using the coordinates.

Open the picture input.

From the input image, extract the locations of the black pixels.

Use PCA to determine the matching eigen vector from the input image coordinates.

Determine the angle between the input vector and the reference vector.

To align the vectors, rotate the input image by the computed angle.

The aligned image can be saved or used.

Carry out steps 4 through 9 for every picture in the KIMIA Dataset.
