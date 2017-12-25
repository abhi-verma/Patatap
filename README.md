# Patatap

The only html elements are div to display the message and a canvas with black background.

The meat of the website is in PaperScript (using PaperJS) library. An object is created for each keypress and a color and sound is added to each alphabet key in the object.

onKeyDown function in PaperJS listens to keypress events. The function creates a new circle at random coordinates and assigns a color and sound to the circle. The created circles are added to an array.

Another function onFrame(), loops through the circles array and assigns a hue and scale to every circle which is responsible for the color gradient effect and the decreasing size animation of the circles.

The disappearing circles are removed from the array to avoid over population of the array.
