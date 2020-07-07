User's Guide
=================

Aligner Preparation
-------------------------------

Aligners should be printed :hoverxref:`as usual <aligner-1>`. For CNC cutting the aligners will have to be processed with the Rhino script. 

Placement in the thermoformer should be within 3mm of the :hoverxref:`porous pad <aligner-2>`, while also :hoverxref:`maximizing separation <aligner-3>` between the aligners. Rotation of the aligners should be kept :hoverxref:`within 30 degrees <aligner-4>`. 

Laser Cabinet Preparation
------------------------------
Power on all components. :hoverxref:`The laser source <laser-marker-3>`, :hoverxref:`temperature controller <laser-marker-4>`, :hoverxref:`fumex ventilation <cabinet-2>`and laser :hoverxref:`marking PC <laser-marker-6>`. The laser source and laser marking PC have a physical lock and key which prevents power up if not unlocked. 

Start :hoverxref:`Merlin II <merlin-1>` on the laser marking PC. Load the latest pattern with the appropriate logo to be marked. 

Make sure that the homing location has not changed, and home the machine by :hoverxref:`going Online <merlin-2>`. After going Online, :hoverxref:`Park the machine <merlin-3>` and it will move to the working height. Check that the current position of the laser aiming diode is :hoverxref:`slightly off of the zero post <laser-marker-9>`. 

Finally, :hoverxref:`Enable the laser <laser-marker-2>` on the laser source, open the :hoverxref:`shutter <laser-marker-2>` and enable the :hoverxref:`aiming diode <laser-marker-2>` if desired. The laser marker is ready for marking. 

Start :hoverxref:`Insight Explorer <insight-1>` on the laser marking PC. Load the latest job file onto the Cognex camera. Make sure that the camera is set to :hoverxref:`Online <insight-3>` and that when the trigger is :hoverxref:`manually pressed <insight-4>` a new image is acquired. The cognex camera is ready to :hoverxref:`compute positions <insight-5>` for the laser marker. 

Make sure that the :hoverxref:`ventilation hood <cabinet-1>` is close to the marking position but not blocking the laser. 

Operation
---------------------
Place the aligner onto the marking platform. The best marking position is where the right side of the back right molar is next to the zeroing pin, the larger of the two pins. It is not necessary to exactly place the aligner in this position because the camera can adjust the marking position. As long as the aligner is close (within 5mm) the camera will provide a good marking position. 

The camera can be manually triggered to inspect the marking position. The red dot will move to the first marking position. Triggering happens automatically when the merlin pattern is run as well. 

Close the cabinet door. The shutter for the laser will not open until the laser cabinet door is closed. It will also disable the laser if the door is opened while the laser is running. 

Run the merlin pattern by pressing F2 or pressing the Go button. This opens a window for counts. Mark 1 count by pressing Enter. The laser should mark the data matrix, backup code, and logo within 12 seconds. 

When the mark is complete, open the cabinet door and remove the aligner. The opposite side or next aligner can be loaded next by repeating the operation steps. 

Picture List

- aligner-1, general aligner Picture
- aligner-2 3mm of porous pad
- aligner-3 highlight separation between aligners
- aligner-4 example of Rotation
- laser-marker-3 laser source box
- laser-marker-4 temperature controller
- laser-marker-6 marking PC
- merlin-2 online button for merlin
- merlin-3 park button for merlin
- laser-marker-9 laser diode position when parked
- insight-3 online mode for camera
- insight-4 trigger is manually pressed
- insight-5 connection output signal
- cabinet-1 ventilation hood inside cabinet
- cabinet-2 fumex box