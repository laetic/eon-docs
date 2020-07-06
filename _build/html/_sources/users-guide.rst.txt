User's Guide
=================

Aligner Preparation
-------------------------------

Aligners should be printed as usual. For CNC cutting the aligners will have to be processed with the Rhino scipt. 

Placement in the thermoformer should be within 3mm of the porous pad, while also maximizing separation between the aligners. Rotation of the aligners should be kept within 30 degrees. 

Laser Cabinet Preparation
------------------------------
Power on all components. The laser source, temperature controller, fumex ventilation and laser marking PC. The laser source and laser marking PC have a physical lock and key which prevents power up if not unlocked. 

Enable the laser on the laser source, open the shutter and enable the aiming diode if desired. 

Start Merlin II on the laser marking PC. Load the latest pattern with the appropriate logo to be marked. 

Make sure that the homing location has not changed, and home the machine by going Online. After going Online, Park the machine and it will move to the working height. Check that the current position of the laser aiming diode is slightly off of the zero post. The laser marker is ready for marking. 

Start Insight Explorer on the laser marking PC. Load the latest job file onto the Cognex camera. Make sure that the camera is set to Online and that when the trigger is manually pressed a new image is acquired. The cognex camera is ready to compute positions for the laser marker. 

Make sure that the ventilation hood is close to the marking position but not blocking the laser. 

Operation
---------------------
Place the aligner onto the marking platform. The best marking position is where the right side of the back right molar is next to the zeroing pin, the larger of the two pins. It is not necessary to exactly place the aligner in this position because the camera can adjust the marking position. As long as the aligner is close (within 5mm) the camera will provide a good marking position. 

The camera can be manually triggered to inspect the marking position. The red dot will move to the first marking position. Triggering happens automatically when the merlin pattern is run as well. 

Close the cabinet door. The shutter for the laser will not open until the laser cabinet door is closed. It will also disable the laser if the door is opened while the laser is running. 

Run the merlin pattern by pressing F2 or pressing the Go button. This opens a window for counts. Mark 1 count by pressing Enter. The laser should mark the data matrix, backup code, and logo within 12 seconds. 

When the mark is complete, open the cabinet door and remove the aligner. The opposite side or next aligner can be loaded next by repeating the operation steps. 

