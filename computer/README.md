The distance to stop sign and traffic light is measured by using a single Pi camera, camera calibration is needed. 

For more detail in camera calibration, please refer to [OpenCv-Python Tutorial](http://opencv-python-tutroals.readthedocs.org/en/latest/py_tutorials/py_calib3d/py_calibration/py_calibration.html)

For more detail in calculating distance using monocular vision, please refer to [Vehicle Distance Measurement based on Monocular Vision - Xu Guoyan, Wang Chuanrong, Gao feng, & Wang Jiangfeng (September, 2009)](http://www.paper.edu.cn/download/downPaper/200909-748)

Thanks @ryangmolina use the link to download xml files for left arrow sign https://github.com/ryangmolina/rpi-car-arrow-detection-using-cascade-classifier/tree/master/haar_trained_xml
Use a left arrow image to turn the car left side similar can be done for right

Use rc_driver.py & rc_driver_helper.py (OR) if you want the car to turn left to left arrow sign use rc_driver3.py & rc_driver_helper3.py

Save the xml files in  "haar_trained_xml/left/cascade.xml" the correct directory after downloading them from above link also don't hesitate to change the threshold values of all objects(stop sign,arrow sign) available.
