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

NebHolder: Many very young children on ventilator support use in-line
nebulizer support. These nebulizers are not held to the face, instead
are inlined through the ventilator tubing port. The Nebulizers
unfortunately come with support for hand held/mask supply - which
makes business sense since majority of the users are of that age
group. However for infants who are scared already of all the medical
equipment, a little bit of a distraction is useful. Further, trying to
keep these nebulizers stable with a kicking and active child is even
more hard. Hence.. the Nebulizer Holder :). This uses the Utils/Nutjob
(http://www.thingiverse.com/thing:193647) nut\_6x9.stl embedded into
the carraige and needs a washer and an additional nut\_6x9.stl jack
to hold things together. TBD: I wish i had changed the smokestack to
be a little wider to fit in the tip of the neb tube when changing,
but it can be stuck up in the carriage way as well. I also think this
design can be modified with a small motor and AA battery holder in
carraige way to give periodic shake to the neb cup to help the meds
move along. This print also requires support (unfortunately for the
open carraige...) i used 15% for support, 20% infill. Overall, please
be careful NOT to pinch the tubing when Neb is pushed in.
