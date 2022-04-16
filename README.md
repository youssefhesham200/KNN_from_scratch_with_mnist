# KNN_from_scratch_with_mnist

I worked on mnist dataset (image classification) from scratch
i splited each image into -> 16 block each of them represented by -> 7 * 7 pixels
I will use center of mass of each block in image that return (x,y) coordinates for each block
centroid function calculate and return center of mass of each block
input -> small pic output -> (x,y) coordinates of block and if pic is all black return (3.5, 3.5) because pic is 7 * 7

4 blocks in width and 4 blocks in hight then we have 16 small pics

crop_image function split image into 16 small pics then call centroid function calculate (x,y) coordinates of block then add all centroids into one vector and return it for each image

then implement KNN classifier from scratch to classy it then test accuracy 
