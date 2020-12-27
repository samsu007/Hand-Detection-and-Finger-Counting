"# Hand-Detection-and-Finger-Counting" 

step by step

1. import libraries
2. read the image
3. convert image to HSV
4. give lower and upper range of skin color in HSV
5. detect skin on the range of lower and upper pixel values in color spaces
6. blurring image to improve masking
7. apply thresholding
8. find contour of the image
9. find the convexity defects
10. base on convexity defects value calculate the angle using cosine theorem
11. count the no of fingers and display into the image 
12. finally show the image using imshow()