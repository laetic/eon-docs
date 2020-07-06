Calibration
==================

The camera and laser marker are calibrated to 15.2mm above the table surface. This is the average height of the molars and provides a good focus range for all marks. The calibration is not extremely precise, +/- 0.5 millimeters or within 20 thousandth of an inch. However, both systems must be well calibrated because they depend on each other's accuracy. 

Reminder that the zero point for all later procedures is the intersection of the centerline of the zeroing pin and the 15.2mm plane. 

Camera Calibration
------------------------

The cognex provides a built in calibration procedure in Insight Explorer. Go to Set Up Image and press the calibrate button. The recommended settings are, 3.0 mm grid, no fiducial. The calibration procedure asks the user to pick a zero point out of the grid points when there is no fiducial. 

To do this, first align the laser aiming diode so that it is on top of the zero point. Again, this point is not on the surface of the pin but 15.2mm above the table surface. 

Once the laser aiming diode is properly positioned, align the 3mm grid so that one of the grid points is at the laser aiming dot. Make sure that the camera can view as many of the other points as possible. 

Keep track of which grid intersection is used for the zero, because the aiming laser must be turned off to get a calibration image. Once the calibration image is captured, Insight Explorer will ask for a zero position. Click on the intersection that was used for zero, and provide X (left and right) and Y (up and down) directions. 

