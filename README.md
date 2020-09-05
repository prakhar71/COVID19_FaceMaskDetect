
<h1>Covid19 Face Mask Detection</h1><br>

The following are the details of the Project for building a model for detecting face with a mask and without a face mask.<br>
1. first the webcam captures the images/video frames of the face.
2. then it is passed to a cascade classifier 
3. the cascade classifier gives the region of interest(ROI) it gives X, Y, Width, and Height of the face with marks the region of interest
4. the ROI is then resized into a 100 by 100 image 
5. then it is passed through a pre-trained convolutional neural network (CNN)
6. the CNN will give the probabilities with mask and without mask 


in this Project i am going to use a data set originally created by [Prajna Bhandary](https://www.linkedin.com/in/prajna-bhandary-0b03a416a/)


<p style="text-align:right">

due to Covid-19, there is no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety.the COVID-19 mask detector could potentially be used to help ensure your safety.

I am building a Face Mask Detector using Convolutional Neural Networks (CNN) Python, Keras, Tensorflow and OpenCV. With further improvements these types of models could be integrated with CCTV or other types cameras to detect and identify people without masks. With the prevailing worldwide situation due to COVID-19 pandemic, these types of systems would be very supportive for many kind of institutions around the world. 

<img src="https://user-images.githubusercontent.com/25726075/92301204-25a9ee00-ef7f-11ea-8157-5c253d1158bb.gif" style="text-align:right">

</p>



