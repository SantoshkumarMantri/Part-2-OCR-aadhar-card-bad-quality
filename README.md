# Part-2-OCR-aadhar-card-bad-quality
First importing the required libraries.
Defining a function which calculates the angle (skewness) and returns the value.
Defining another function with imagename, blur radius and threshold as arguments. It blurs the image using Gaussian blur, binarizes the image using threshold and extracts text.
defining another function which extracts number by running loops (on threshold and blur) and deskewing the image if required.
Finally, calculating accuracy using difflib library.
