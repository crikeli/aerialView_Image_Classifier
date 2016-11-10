# Using TensorFlow to classify aerial views of images using deep learning.

The Last Layer of the [Inception Model](https://research.googleblog.com/2016/03/train-your-own-image-classifier-with.html) by Google is trained on hundreds of images of aerial views of major US Cities.

### Seattle
![el](aerial_photos/Seattle/pic_001.jpg)

### San-Francisco
![el](aerial_photos/San-Francisco/pic_001.jpg)

### New-York
![el](aerial_photos/New-York/pic_001.jpg)

### Chicago
![el](aerial_photos/Chicago/pic_001.jpg)

### After creating bottlenecks of all the images in each city folder, I obtained a test data accuracy of 56.4%
![el](test_photos/ss1.png)

### Upon feeding novel images of each city to the network, the network predicted the correct city 3 out of 4 times. (EXCITING!!!)

###### The network predicted Seattle incorrectly (~ 14.5% confidence)
![el](test_photos/seattle/img_001.jpg)

###### The network predicted San-Francisco correctly (~91% confidence)
![el](test_photos/san-francisco/img_001.jpg)

###### The network predicted New-York correctly (~88% confidence)
![el](test_photos/new-york/img_001.jpg)

###### The network predicted Chicago correctly (~91% confidence)
![el](test_photos/chicago/img_001.jpg)


### Here are the raw results.
![el](test_photos/results.png)
