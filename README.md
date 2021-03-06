# Diagnose 
## Top 12 at Hack36 2018 at MNNIT Allahabad ##

Changing lives by making recommendations about problems that you face.

If you're worried that you might need braces, but dread the thought of going to the dentist.

What could be invaluable is that you have an approximate diagnosis of what's wrong, and that's where our solution comes in. From within a robust web application, you can take a photograph (or upload one) using the webcam, and thanks to our deep learning algorithms, receive a diagnosis that can help you pinpoint the right problem you might be facing. This can help you go to the right practitioner and can save you some considerable amount of confusion.

## What did we set out to achieve? ##

To build a web application that could accept photographs through the webcam and predict the following:
* Crooked or diseased teeth that might require dental care

## Tech used: ##
We used tensorflow for image classification using the inception v3 architecture, that allowed us to perform Deep Learning on datasets that we got from using a selenium web driver based crawler that extracted images from Google Images. 

We also embedded a webcam window into our app that users can use to take photographs to be categorized. 

## Stack: ##
* Tensorflow
* flask for the web app
* Selenium for web crawling
* bash for some automation tasks
* Javascript (AJAX) for webcam connections
