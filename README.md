# Painting-Style-Transfer
 Painting Style transfer is a computer vision/optimization technique that takes two images:- a content image and a style reference image—and blends them together so that the resulting output image retains the core elements of the content image, but appears to be “painted” in the style of the style reference image.
# A Neural Algorithm of Artistic Style”
 In this approach we used a VGG network with function to combine both the style and content loss and then by optimizing this loss in one iteration we will reduce the style and content loss thus making the produced image better.
Link to Research paper: ​https://arxiv.org/pdf/1508.06576.pdf

#Major Disadvantage:
 The overall process is very slow and takes too much time for a single image thus creating real time applications is not possible using this approach. ● For processing a single image on non gpu accelerated systems it take 4 to 5 hours. On my system it took 5 hours. ● For processing a single image on gpu accelerated systems it takes 1-2 minutes. On Google colab it took 1 minute. Even on gpu accelerated system the results are not real time thus implementing this approach in real-time applications (webcams) is not a good idea.
 
 #Steps For Execution:
 #Using Google Colab (Recommended because fast and simple):
 
 1.Open https://colab.research.google.com/drive/1dyNIUmj98xy5TSW9cgzzTv7mPyvSahpO#scr ollTo=o86SxoacBs_z​ in your browser.

2.Upload your Style and Content Image by clicking the upload button in the console.

3.Change the name of content image from “night.jpg” to your Content image name (Second Cell)

4.Change the Name of Style image from “starry_night.jpg” to your style Image name (Third Cell)

5.Click on Runtime dropdown and chose run all button.

6.Scroll Down to the bottom of the page and see the result image

Note: Google Colab ​ is a free cloud service which now supports free GPU, Programmers use it to improve Python programming language coding skills. develop deep learning applications using popular libraries such as Keras, TensorFlow, PyTorch, and OpenCV.
