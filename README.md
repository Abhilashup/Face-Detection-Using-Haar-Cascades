# Face-Detection-Using-Haar-Cascades

# About

This is a small project that shows how faces can be detected in an image using Haar Cascades in OpenCV. I have used an image of the Barcelona Football Team in order to detect the faces of the players.

# Screenshots

When minNeighbors was set to 5, there were many False Positives and here is an image of it, 
![neigh_5](https://user-images.githubusercontent.com/66258607/115353023-ab5c7000-a1d5-11eb-8b3d-67fe28d83871.PNG)

But when it was changed to 10, I was able to detect all the faces correctly and here is an image of the result,
![neigh_full](https://user-images.githubusercontent.com/66258607/115353226-e52d7680-a1d5-11eb-931b-0b3fcf7b400e.PNG)

The minNeighbors parameter eliminates the False Positives. This approach basically determines how much neighborhood is required to pass it as a face rectangle.




