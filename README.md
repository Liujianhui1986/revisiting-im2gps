# Revisiting Im2GPS

Code & data for the "Revisiting IM2GPS in the Deep Learning Era" paper
https://www.cc.gatech.edu/~nvo9/revisitingim2gps_iccv2017/

Prerequisites:
- Matlab
- Caffe & its Matlab interface: http://caffe.berkeleyvision.org/
- FLANN & its Matlab interface: http://www.cs.ubc.ca/research/flann/
- Have 3.5GB of free RAM

Test on new images:
- Download reference features from http://www.mediafire.com/file/7l2dqi7f7obzu57/reference_im2gps.zip and unzip the .mat files to "reference" folder
- Download caffe model from http://www.mediafire.com/file/d9hifat6qi4tu2m/7000only__iter_167400.caffemodel
- Run main.m to predict gps coordinate of an example image

Test on im2gps-test-set:
- Download the test set from http://graphics.cs.cmu.edu/projects/im2gps and unzip the images to "query" folder
- Run main_im2gps_test.m
- The numbers might not be exactly the same as reported in the paper because of FLANN randomization or image decoding.

Reference:
- Nam Vo, Nathan Jacobs and James Hays. "Revisiting IM2GPS in the Deep Learning Era". ICCV 2017.

















