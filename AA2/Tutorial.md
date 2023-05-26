Change the Contrast of the Image
=================================
In this activity, you will learn to change the contrast of the images.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10485511/pasted-from-clipboard.png" width = "480" height = "320">

Follow the given steps to complete this activity:
1. Change the contrast

* Open the main.py file.

* Change contrast of the image using convertScaleAbs() function.

    `contrastAdjustedImage = cv2.convertScaleAbs(rotatedImage, alpha=1.5, beta=-120)`

* Display the converted image.

    `cv2.imshow('Contrast Adjusted Image', contrastAdjustedImage) cv2.waitKey(0)`

* Save and run the code to check the output.
