# Mechanical and machine design

💡 Group assignment (part 1 of 2) - Mechanical design

* Design a [machine](http://machines.fabcloud.io/) that includes mechanism + actuation + automation + application
* Build the mechanical parts and operate it manually
* Document the group project

***

💡 Group assignment (part 2 of 2) - Machine design

* Actuate and automate your machine
* Document the group project

***

### About this week <a href="#id-19caf66e-e64e-8057-8ecc-ddd585390c2c" id="id-19caf66e-e64e-8057-8ecc-ddd585390c2c"></a>

For mechanical and machine design our group will be designing and building a rotocasting machine from upcycled 3D printer components.

Rotocasting, is a process where a mould is partially filled with a self casting material and rotated about 2 axis so as to create a hollow part, ideally with an even wall thickness

***

### Key roles and responsibility for the project:

* Diarmuid Kelly - Mechanical Design Lead
* Carl McAteer - Fabrication Lead
* Thom Conaty - Electronic Design Lead

While these are our areas of responsibility there is significant areas of overlap throughout the project.

***

### Tools and materials used <a href="#id-19caf66e-e64e-8066-9139-ccc89444c8ba" id="id-19caf66e-e64e-8066-9139-ccc89444c8ba"></a>

> _Autodesk Fusion_
>
> _Onshape_
>
> _Prusa Slicer_
>
> _Ultimaker 2 (used for parts)_
>
> _Makerbot Replicator 2 (used for parts)_

***

### Process and methodology <a href="#id-19caf66e-e64e-805f-9104-c8b7ba0a1c3f" id="id-19caf66e-e64e-805f-9104-c8b7ba0a1c3f"></a>

### **Mechanical Design (part 1 of 2)** <a href="#id-19caf66e-e64e-806f-a181-fb94fbc4acda" id="id-19caf66e-e64e-806f-a181-fb94fbc4acda"></a>

We set out to design a rotational casting/moulding machine. We started with the initial sketches we had in our notebooks and digital sketching tools.

<figure><img src="docs/img/w12/w12-1.jpeg" alt=""><figcaption><p>Some concept sketches Diarmuid's notebook.</p></figcaption></figure>

This development through sketches was where we came up with our overall structure or having 3D printed components being sandwiched between laser cut ones

<figure><img src="docs/img/w12/w12-2.jpeg" alt=""><figcaption><p>Carl doing some development sketches.</p></figcaption></figure>

Diarmuid took Carl's concept sketches and worked up an initial CAD model in Autodesk Fusion

He also took the time to set up a shared fusion 360 workspace so that all our files for the project were in one place.

<figure><img src="docs/img/w12/w12-3.jpeg" alt=""><figcaption><p>Using Sketch as Canvase in Autodesk Fusion</p></figcaption></figure>

We used the Canvas feature in Autodesk Fusion to insert one of the selected concept sketches. This was calibrated to size so we could sketch to actual size. To do this, right-click on the canvas in the Fusion Br0wser and click calibrate. Select two points of known dimension and enter the desired dimension. Your canvas will now resize.

<figure><img src="docs/img/w12/w12-4.jpeg" alt=""><figcaption><p>MakerBot Replicator 2 - disacembled</p></figcaption></figure>

Diarmuid took apart the Makerbot Replicator 2 and Carl took apart the Ultimaker 2. Both of these printers were donated machines - the replicator from South West College and the Ultimaker from Stweart Lawn from Manerhamilton Fab Lab - thank you to both for donating the printers.

<figure><img src="docs/img/w12/w12-5.jpeg" alt=""><figcaption></figcaption></figure>

We wanted to keep the design simple so as to reduce gears and drive shafts needed we wondered if it would be possible to bend the belt around the corner. Constrained by the belt sizes we had salvaged from the Makerbot and Ultimaker printers, we decided to pick the longest - the Replicator X axis belt. To confirm the size, we printed a ¼ section that was using the belt to drive around the corner. This initial test piece was too small.

<figure><img src=".gitbook/assets/12_pic_01 - 4.jpeg" alt=""><figcaption><p>First Laser Cut Size Test</p></figcaption></figure>

We measured the belt a bit more accurately the second time and got something that moved. This would need to be refined and would also need a way of tensioning the belt. But we were happy to use this as a drive mechanism.

<figure><img src=".gitbook/assets/12_pic_01 - 5.jpeg" alt=""><figcaption></figcaption></figure>

<figure><img src="docs/img/w12/w12-8.jpeg" alt=""><figcaption></figcaption></figure>

Once we were happy that the dimensions of the outside ring would accommodate the belts we were using we started to build of the full cad model for manufacture.

* Base - Carl - CNC'd bottom and lasercut uprights taken from the ultimaker 2 side panels
* Outer Ring - Diarmuid - This is the most complex assembly as it contains the structure that holds the inner ring, but also all the gearing and the belt tensioning system.
* Inner Ring - Carl - This is the piece that will hold the mold so needs to be robus and light weight as this is the fastest part of the product due to the 4:1 gearing.
* Electronics and programing - Thom - Thom

Think we need to add images here of the test laser cuts

We laser cut ¼ of the arm that was going to be used

The Inner ring consists of 8 identical 3D printed parts that are sandwiched between 2 MDF rings.

As all the parts are identical they needed to be multifunctional

So they could each hold:

* 2 skateboard bearings
* 1 belt pulley from the ultimaker to retain the drive axis
* 2 mounting points for the mould assembly

<figure><img src="docs/img/w12/w12-6.jpeg" alt=""><figcaption></figcaption></figure>

The full assembly was created in fusion 360

<figure><img src="docs/img/w12/w12-7.jpeg" alt=""><figcaption></figcaption></figure>

And using 'insert component' it was brought into Diarmuid design so we had a complete CAD model

<figure><img src="docs/img/w12/w12-9.jpeg" alt=""><figcaption></figcaption></figure>

And the full set were printed on Carls Bambu Lab P1s -

{% embed url="https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/video/w12-printer.mp4" %}

Where possible we designed parts around press fits as this is a relibably assembly method with 3D printed parts - such as the skateboard bearings in these 3d printed idlers.

<figure><img src="docs/img/w12/w12-11.jpeg" alt=""><figcaption></figcaption></figure>

Full assembly for outer ring showen below

<figure><img src="docs/img/w12/w12-12.jpeg" alt=""><figcaption></figcaption></figure>

While Carl and Diarmud worked on the mecinacial design Thom created the electronic design for the project, here he is de soldering power supply components from the Ultimaker main board.

<figure><img src="docs/img/w12/w12-13.jpeg" alt=""><figcaption></figcaption></figure>

The linear rods from the Ultimaker were cut into sections using an angle grinder and used as the axles for the rotocasting machine.

<figure><img src="docs/img/w12/w12-14.jpeg" alt=""><figcaption></figcaption></figure>

The angle grinder can leave a shap edge so all pieces were finished on the bench grinder

<figure><img src="docs/img/w12/w12-15.jpeg" alt=""><figcaption></figcaption></figure>

This shows how we transmitted drive through the axles, the pulley from the ultimaker motion system was captured in between the 2 halves of the print and the grub screw was used to hold the axle in place.

<figure><img src="docs/img/w12/w12-16.jpeg" alt=""><figcaption></figcaption></figure>

The assembly of the outer ring

<figure><img src="docs/img/w12/w12-17.jpeg" alt=""><figcaption></figcaption></figure>

The longer linear rails from the makerbot were used to align the printed components.

<figure><img src="docs/img/w12/w12-18.jpeg" alt=""><figcaption></figcaption></figure>

We just had to be careful not to knock them together to hard!

<figure><img src="docs/img/w12/w12-19.jpeg" alt=""><figcaption></figcaption></figure>

Same process was used for the inner ring, it used a captured pulley on one end and a set of skateboard bearings on the other.

<figure><img src="docs/img/w12/w12-20.jpeg" alt=""><figcaption></figcaption></figure>

Giving it a spin!

<figure><img src="docs/img/w12/w12-22.jpeg" alt=""><figcaption></figcaption></figure>

The completed ring assembly with belts attached. The critical element of this is the 4:1 gearing, so each time the big ring spins once the inner ring spins 4 times. This allows the contents of the mold to be spread evenly, assuming a relatively evenly proportioned mold.

<figure><img src="docs/img/w12/w12-23.jpeg" alt=""><figcaption></figcaption></figure>

The side panels were lasercut from the acrylic panels from the ultimaker

<figure><img src="docs/img/w12/w12-24.jpeg" alt=""><figcaption></figcaption></figure>

And the parts were dry fit together

<figure><img src="docs/img/w12/w12-25.jpeg" alt=""><figcaption></figcaption></figure>

{% embed url="https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/video/w12-cnc.mp4" %}

The base was cut out of 24mm plywood as we wanted something heavy to keep the machine from rocking in operation

<figure><img src="docs/img/w12/w12-26.jpeg" alt=""><figcaption></figcaption></figure>

Removing the piece from the CNC

### **Machine Design (part 2 of 2)** <a href="#id-19caf66e-e64e-802f-bbba-fe4c9e5ba9f0" id="id-19caf66e-e64e-802f-bbba-fe4c9e5ba9f0"></a>

<figure><img src="docs/img/w12/w12-02-2.jpeg" alt=""><figcaption></figcaption></figure>

TODO - this is a thing from carl

<figure><img src="docs/img/w12/w12-02-3.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-4.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-5.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-6.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-7.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-8.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-9.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-10.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-11.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-12.jpeg" alt=""><figcaption></figcaption></figure>

TODO

<figure><img src="docs/img/w12/w12-02-13.jpeg" alt=""><figcaption></figcaption></figure>

We used some spare parts to decided how much weight we needed to add to the other side of the wheel in order to balance it with the load on the stepper.

<figure><img src="docs/img/w12/w12-02-14.jpeg" alt=""><figcaption></figcaption></figure>

While we reassembled the machine we took the opportunity to loosen the belt tension.

<figure><img src="docs/img/w12/w12-02-15.jpeg" alt=""><figcaption></figcaption></figure>

We took inspiration from how the panels were connected on the Ultimaker 2 to connect the machine to the base

<figure><img src="docs/img/w12/w12-02-16.jpeg" alt=""><figcaption></figcaption></figure>

Our final system integration jobs were to add the enclosure and the fan for the electronics.

{% embed url="https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/video/w12-video-3.mp4" %}

***

### Group conclusions <a href="#id-19caf66e-e64e-80af-bf32-f202965a9eaf" id="id-19caf66e-e64e-80af-bf32-f202965a9eaf"></a>

> **Findings:** \[What did you learn from the process?]
>
> * **There is no MKII** - we made decisions thinking that we would revised them later but due to time constraints were not realize this was a mistake. For example we should have made the rings out of plywood as it would have been stronger, the MDF was only ment to be temporary.

> **Challenges:** \[What issues did you encounter?]

> **Solutions:** \[How did you solve them?]

Type here

***

### Files <a href="#id-19caf66e-e64e-8056-aa8f-ff906f2f0f5b" id="id-19caf66e-e64e-8056-aa8f-ff906f2f0f5b"></a>

> Add all files created for this group assignment

See below link to to files created this week:
