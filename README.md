# Spin Turtnable System

Find all the design files for building your own Spin turntable (http://spin.media.mit.edu/) here.

## Arduino

This folder contains the SoftModem library needed for the spin.ino Arduino sketch.  The spin sketch should be uploaded to the Arduino UNO running Spin.

## CAD

The CAD folder contains three subfolders: _3D Print_, _Laser Cut_, and _Solidworks_.  Building your own Spin turntable requires laser cutting parts in 3/16" and 1/8" acrylic, which can be found in the _Laser Cut_ folder in Illustrator, Corel Draw, and DXF formats.  Additionally, you'll need to 3D print a gear (motor_gear.STL), which can be found in the _3D print_ folder.  Optionally, you can 3D print your own iPhone dock (sized for an iPhone 4/4S or 5/5S), and the iPhone 6 Adapter sized for an iPhone 6/6S, both of which can be found in the 3D print folder.  If you're using an iPad, here's a simple LEGO stand you can build: http://spin.media.mit.edu/sets/731

If you're interested in modifying any of the components in CAD, all of the files are located in the _Solidworks_ folder.

## MAT

This is an optional placemat used for lining up the center of the turntable with your iPhone.  It is 25"x25" and can be printed on 8.5x11 and taped together.

![Spin Placemat]
(https://s3.amazonaws.com/spin360-production/build/mat.png)

## PCB

The Eagle files and libraries for the Spin shield are located here.  You can purchase the shield directly from OSH Park: https://oshpark.com/profiles/scientiffic

## Processing

This is an optional Processing sketch for controlling the Spin turntable with your computer via a USB connection to the Uno.  You can use this to debug your turntable or to just control it without using an iOS device.



