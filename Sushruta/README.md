Brief
=====

I started on this design to help organize various Medical equipment on
a toddler's crib.

The Target crib is (Baby r Us : Chalet made by Delta):
http://www.toysrus.com/product/index.jsp?productId=58732006

This Crib has a ledge like top which makes it a little hard for a
simple holder solution. - This mostly impacts the CribHolder-Top block

I have tried to make things modular, hopefully allowing custom crib
configuration to be supported as needed.

Here are the major components:

CribLatch: This is the basic latch, the male end fits on the crib, and
the female portion fits on to the solution of choice (med tray/ feed
holder/ neb holder etc..) - Hopefully a standardized latch will allow
major reuse.
	- This uses a baseline of 3.5mm thick base.

CribHolder-Top : This fits on to the crib top - This embeds a nut from
http://www.thingiverse.com/thing:193647 -> allowing to be fastened to
the crib as required. (we have a nut\_6x9.stl embedded into things
here)
	- Use of support is recommended (unfortunately a bit of overhang) and brim as needed.
	- See Utils/NutJob for details
	- Use atleast 50% fill for the Nut print (they dont seem to handle the
	  stress else). I used 30% fill for the top.

MedTray: This was derived out of a simple need: How to ensure that
Nurses can maintain the venting syringe, Med cup (with medication
in syringes), nebulizer cups, neb tubing and compressor tubing not
touching stuff they are not supposed to?

FeedHolder: (infinity Pump) For Children with G-tube, there is the
Kangroo ( http://www.kangarooepump.com/ ) and the infinity feeding
pump ( http://www.infinityfeedingpump.com/ ) Most of these pumps are
held up using a big feeding pole. Here is a crib side Feedholder
solution for inifinity pumps. This is designed to work with the
CribHolder-Top.

