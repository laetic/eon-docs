Overview
================

Components
----------------

Telesis Laser Marker
~~~~~~~~~~~~~~~~~~~~~~~
The laser marker creates the black laser mark on the aligners. The laser marking head must be placed at the proper distance and calibrated to the proper zero location. See calibration. The laser is now aligned and should mark any patterns in the proper location. Merlin II is the control software for the Telesis laser marker. The pattern used is (pattern file name). This pattern contains the data matrix, letters, and the logo. It follows this basic logic: 

- Go to the calibrated laser marking height (currently -1.00 inches from home)
- Trigger the camera
- Ask for the contents of the data matrix and client code.
- Ask for the X, Y and angle of the data matrix and client code.
- Mark the data matrix and client code
- Ask for the X, Y of the logo
- Mark the logo

This will :hoverxref:`show a tooltip <hoverxref:hover1>` in the linked words to ``fdfdf``.

This will :hoverxref:`<hoverxref:hover1>` in the linked words to ``fdfdf``.

This will :hoverxref:`<hover1>` in the linked words to ``fdfdf``.

This will :hoverxref:`show a tooltip <hover2>` in the linked words to ``fdfd``.

This will :hoverxref:`show a tooltip <hover1>` in the linked words to ``fdfd``.

Other one :doc:`this is a doc <hover>`



Cognex Computer Vision
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The cognex camera provides the X, Y, and angle of the data matrix and logo. To do this is uses a job file (job file name) which takes a picture of the aligners and finds the appropriate locations to mark. The job must be loaded onto the camera after a power cycle (configurable). The camera must also be placed online. This is done in Insight Explorer, the control software for the Cognex camera. 

Lighting 
~~~~~~~~~~~~~

An LED panel light provides uniform under lighting to the aligners. It is diffused so that the entire lighting box is roughly the same light intensity. If not diffused or at too high of an intensity, the light will be much brighter than the surrounding panels. The recommended control voltage is 2.5V. If adjusted make sure to adjust the exposure time in Insight Explorer. 


Laser Enclosure
~~~~~~~~~~~~~~~~~

The laser enclosure makes sure no laser radiation or harmful reflections escape. The door is connected to an interlock switch which closes the laser shutter if the door is open. 

