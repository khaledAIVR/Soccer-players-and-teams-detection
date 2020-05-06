# Soccer-players-and-teams-detection
Detecting soccer players and their teams using Computer vision technologies

# How it works: 
- Create a Mask using cv2 library in order to discard all people located outside the green playground.
- Use Yolov3 model to detect all people inside of the playground and draw boxes around them.
- Extract all of these boxes and use the dominant color of each box to determine the team of each detected player using the color of his jersey.
- After obtaining all of the dominant colors use colormath lib to determine the differences between colors and cluster the similar colors together. 
