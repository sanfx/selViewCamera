selViewCamera
=============

This code creates camera from selected view. A feature that exist in 3DS max. in Create Camera options.

notes:
=============
        Simple run you create camera from existing camera view transformations or press "ALT" to frame the newly created camera with existing camera.
Info:
======
In both cases newly created camera is selected.
   I tested that code should work any of maya version 8 and after.
   Did not check for earlier versions.

usage : 
========
1.source selViewCamera.mel
2.drag and drop "selViewCamera" to your Shelf to run fro shelf or run "selViewCamera" everytime to create camera from selected camera view
        if pressed alt , the new camera is FrameSelected,
        if pressed Ctrl, the you see through newly created camera
        if pressed Ctrl+Alt you see through newly created camera & Attribute additor is displayed (only choose this option Attribute Editor is not open or else script will hide it.$

