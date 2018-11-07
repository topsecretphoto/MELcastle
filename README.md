# MELcastle
MEL script for Castle Grayskull


This castle model was constructed to resemble Castle Grayskull from He-Man/Masters of the Universe in Maya using MEL script for the purposes of being 3D printed.
The basic frame work is constructed of an individual brick, duplicated and repeated, and held together my a single piece of masonry (a cube for each straight wall, a pipe for each tower) to ensure a solid print. 
The skull face on the front of the castle was created by storing each pixel value of the grayscale 100 x 100 skull image below in an array, and then using those values to set the height of the corresponding vertices in the plane that forms the face in Maya. 

To run the code, download the castle data file then simply copy and paste the script into the Maya's script editor, update the location of the data file in line 20, and run it!
