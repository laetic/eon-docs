Overview
================

Components
----------------

Telesis Laser Marker
~~~~~~~~~~~~~~~~~~~~~~~
The :hoverxref:`laser marker <laser-marker-1>` creates the black laser mark on the aligners. The laser marking head must be placed at the proper distance and calibrated to the proper zero location. See :doc:`calibration`. Once calibrated, the marks are created exactly according to the pattern, and the placement is provided by the :hoverxref:`Cognex camera <cognex-camera-1>`

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

The :hoverxref:`Cognex camera <cognex-1>` provides the X, Y, and angle of the data matrix and logo. To do this is uses a job file ``TO BE INCLUDED`` which takes a picture of the aligners and finds the appropriate locations to mark. The job must be loaded onto the camera after a power cycle (configurable). The camera must also be placed online. This is done in :hoverxref:`Insight Explorer <insight-1>`, the control software for the Cognex camera. The job file follows this basic logic:

- :abbr:`Recall (The camera should remain fixed at all times and reduces drift compared to a found fixture)` a fixed zero point.
- Find 4 edge points, roughly around the molars, for the aligner near the zero point. 
- Find the middle of these 4 edge points
- Calculate the X, Y and rotation of this middle point in real world units
- Send the X, Y and rotation to the laser marker
- Find the center of the opposite of the aligner for the logo position
- Wait for the laser marker to ask for the logo position
- Send the X and Y of the logo position

Lighting 
~~~~~~~~~~~~~

An :hoverxref:`LED panel light <led-1>` light provides uniform under lighting to the aligners. It is diffused so that the entire lighting box is roughly the same light intensity. If not diffused or at :hoverxref:`too high of an intensity <led-3>`, the light will be much brighter than the surrounding panels. The recommended :hoverxref:`control voltage is 2.5V<led-2>`. If adjusted make sure to adjust the :hoverxref:`exposure time <insight-2>` in Insight Explorer. 


Laser Enclosure
~~~~~~~~~~~~~~~~~

The laser enclosure makes sure no laser radiation or harmful reflections escape. The door is connected to an interlock switch which closes the :hoverxref:`laser shutter <laser-marker-2>` if the door is open. The laser marker will only operate when the door is closed. 

Picture catalog

- laser-1 overall laser marker
- laser-2 laser shutter controls and enable controls and aiming
- cognex-1 cognex camera
- merlin-1 merlin II general
- insight-1 insight explorer general
- insight-2 insight explorer exposure time
- led-1 LED panel light
- led-2 LED panel control knob
- led-3 LED too high intensity
