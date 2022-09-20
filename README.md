# LaserProjector
An Arduino driven Laser Projector using real galvos.

Building the project is explained here:

http://www.instructables.com/id/Arduino-Laser-Show-With-Real-Galvos/

Have a look at this video to see the filmed laser show:

https://youtu.be/JCon-suqPEE

# Unexpected Maker RGB Laser Controller

This fork includes updated code **(for the LaserShow demo only)** to support an RGB laser, running off the Unexpected Maker Laser Controller
https://unexpectedmaker.com/shop/laser-controller

The code will automatically detect if you have a TinyPICO, TinyS2 or TinyS3 connected to your controller board, and select the correct IO for controlling the RGB laser.

The library has also been switched over to use the MCP48xx DAC library by Steve Gkountouvas from the Library Manager

## What Galvo and RGB Laser can I pair with the Unexpected Maker RGB Laser Controller?

The RGB Laser I use and designed this board to control is the LaserLand RGB 12V laser on Ali Express

https://s.click.aliexpress.com/e/_DF5OacT

The Galvo I use is the 20K Galvo Kit from Room Escape Prop Store on Ali Express

https://s.click.aliexpress.com/e/_DdwJPjd

*Note:** Both of these links above are affiliate links. If you purchase either of these products, I may earn a small about of $ as an affiliate.