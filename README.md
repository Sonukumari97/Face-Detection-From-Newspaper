# Face-Detection-From-Newspaper Cutting 
Object Detection is a a new trend these days related to computer vision, image processing, and deep learning that deals with detecting objects in images and newspaper etc.
Most popular method these days for object detection is using Haar feature based cascade classifiers .It is a approach where a cascade function is pre trained from a lot of true and false images, using this we can detect objects in other images that is our testing data.

Our project deals with object detection in some of the newspaper cuttings that we have collected manually and applying harr cascade calssifier.

The detection phase of the proposed system is that, mainly a window of the target size is moved over the input image, and for each subsection of the image the Haar-like feature is calculated.This difference is then compared to a learned threshold that separates non-objects from objects .The next step involved detection of objects which was accomplished by the detectMultiScale parameter of this command is the scaling factor which plays an important role inavoiding false detection and miss detection. Various values of scaling factor were tried and the most suitable one was chosen and after that we create a contact sheet in which we store all faces which detected from newspaper cutting in a particular scale.
