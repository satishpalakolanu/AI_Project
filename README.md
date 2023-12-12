# AI_Project
DETECTING THE COLOR USING ARTIFICIAL INTELLIGENCE
In this color detection project, we will create an application that will allow you to retrieve the name of a color by just clicking on it.

So, we'll have a data ﬁle with the color name and values for this. Then we'll compute the distance between each color and select the one with the least distance.


Deliverables :
Colors are composed of three main colors: red, green, and blue. Each color value in a computer is deﬁned as a number between 0 and 255. So, how many different ways can we deﬁne a color? The solution is 16,581,375 divided by 256*256*256. A color may be represented in around 16.5 million distinct ways. In our dataset, we must associate the values of each color with their respective names. But we don't have to map every value. We'll be using a dataset containing RGB values and their related names.

Conclusion : 
The given code creates a color detection application OpenCV and PIL libraries. User can identify the name of the color in a image by double clicking on a specific pixel. The script reads the color from a CSV file and employs K means algorithms to find the closest color match  based on the RGB values. It calculates the minimum distance from the clicked pixel to predefined color in the dataset, determining the most matching color. The script then overlays a rectangle and text on the image, providing a visual representation of the detected color including its name and RGB values.

Youtube Link:-
https://www.youtube.com/watch?v=3eZatBDELKo
