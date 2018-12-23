I've created a small test image data file for MNIST from a 150 by 150 pixels image, using Preview app on Mac OS.  
It exists equivalent app for Windows (Paint) and Linux (GIMP) as well.
The original image of the eight number was taken from the blog post by Ole Kroger http://opensourc.es/blog/tensorflow-mnist but 
I've found his/her method to transform the image too much complicated, so I've simplified it for the only purpose of a short demo.
You can take a photo with your smartphone and convert it to .png format wich is more convenient. I know, it's doable with .jpeg too.
First, you resize the image to 28 by 28 pixels using the resizing tool, 
Second you invert the image from black on white background to white on a black background using the color tool in the Preview app. 
