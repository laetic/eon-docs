Overview
================

Components
----------------

Telesis Laser Marker
~~~~~~~~~~~~~~~~~~~~~~~
The :hoverxref:`laser marker <laser-marker-1>` creates the black laser mark on the aligners. The laser marking head must be placed at the proper distance and calibrated to the proper zero location. See :doc:`calibration`. 

:hoverxref:`Merlin II <merlin-1>` is the control software for the Telesis laser marker. The pattern used is ``TO BE INCLUDED``. This pattern contains the data matrix, letters, and the logo. It follows this basic logic: 

- Go to the calibrated laser marking height (currently -1.00 inches from home)
- Trigger the camera
- Ask for the contents of the data matrix and client code.
- Ask for the X, Y and angle of the data matrix and client code.
- Mark the data matrix and client code
- Ask for the X, Y of the logo
- Mark the logo




Cognex Computer Vision
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The :hoverxref:`cognex camera <cognex-camera-1>` provides the X, Y, and angle of the data matrix and logo. To do this is uses a job file ``TO BE INCLUDED`` which takes a picture of the aligners and finds the appropriate locations to mark. The job must be loaded onto the camera after a power cycle (configurable). The camera must also be placed online. This is done in :hoverxref:`Insight Explorer <insight-1>`, the control software for the Cognex camera. 

Lighting 
~~~~~~~~~~~~~

An :hoverxref:`LED panel light <led-1>` light provides uniform under lighting to the aligners. It is diffused so that the entire lighting box is roughly the same light intensity. If not diffused or at too high of an intensity, the light will be much brighter than the surrounding panels. The recommended :hoverxref:`control voltage is 2.5V<led-2>`. If adjusted make sure to adjust the :hoverxref:`exposure time <insight-2>` in Insight Explorer. 


Laser Enclosure
~~~~~~~~~~~~~~~~~

The laser enclosure makes sure no laser radiation or harmful reflections escape. The door is connected to an interlock switch which closes the :hoverxref:`laser shutter <laser-marker-2>` if the door is open. 

Picture catalog
- overall laser marker
- laser shutter controls
- cognex camera
- merlin II general
- insight explorer general
- insight explorer exposure time
- LED panel light
- LED panel control knob
