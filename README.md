# Spin Turntable System

Find all the design files for building your own Spin turntable (http://spin.media.mit.edu/) here.

## Arduino

This folder contains the SoftModem library needed for the spin.ino Arduino sketch.  The spin sketch should be uploaded to the Arduino Uno running Spin.

## CAD

If you are building a turntable and have access to a laser cutter with a bed larger than 12", build the DEFAULT turntable.  If you have a smaller laser cutter that cannot cut material larger than 12", build the Modified 12-inch turntable design.  Both designs have the same exact footprint (13"), but the modified 12-inch turntable has smaller laser cut parts and has an additional set of three 3D printed feet.

Each contains three subfolders: _3D Print_, _Laser Cut_, and _Solidworks_.  Building your own Spin turntable requires laser cutting parts in 3/16" and 1/8" acrylic, which can be found in the _Laser Cut_ folder in Illustrator, Corel Draw, and DXF formats.  Additionally, you'll need to 3D print a gear (motor_gear.STL), which can be found in the _3D print_ folder.  Optionally, you can 3D print your own iOS device dock (which can be used with an iPhone 4/5/6 or iPad/iPad mini).  If you are building the modified turntable, you will also need to 3D print three feet.  

You can find all the original CAD files in the _Solidworks_ folder.

## PCB

The Eagle files and libraries for the Spin shield are located here.  You can purchase the shield directly from OSH Park: https://oshpark.com/profiles/scientiffic

## Processing

This is an optional Processing sketch for controlling the Spin turntable with your computer via a USB connection to the Uno.  You can use this to debug your turntable or to just control it without using an iOS device.
