# Caesar
Caesar is an object detection application created for TomTom Sourcing Operations with the intention of identifying traffic signs
in dash cam video footage, correlate the detected sign with a latitude & longitude, and print the results to a csv file. The 
purpose is to automate the process of verifying that TomTom digital maps have the correct signage in the correct locations.

Caesar uses <a href="https://pjreddie.com/darknet/">Darknet</a>, <a href="https://pjreddie.com/darknet/yolo/">YOLOv3</a>,
and <a href="https://github.com/tesseract-ocr/tesseract">Tesseract</a> to train its model using an open source convulusional neural network,
run object detection on dash cam footage, and read the text on each sign detected.

I have uploaded a sample python script that identifies speed limit signs from a video input.

![Alt text](speedlimitdetectesd.png) 


