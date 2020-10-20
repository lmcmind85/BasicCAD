# BasicCAD

We are creating a caster.

---
## Table of Contents
* [Table of Contents](#Table-of-Contents)
* [Base](#Base)
* [Mount](#Mount)
* [Fork](#Fork)
* [Tire](#Tire)
* [Wheel](#Wheel)
* [AxleCollarBearings](#AxleCollarBearings)
* [Wheel/Tire/Bearing,Axle,Sub-Assembly](#Wheel/Tire/Bearing,Axle,Sub-Assembly)
* [CasterAssembly](#CasterAssembly)

## Base

### Description

The first assignment is to create the Base. The Base's dimensions are 200 mm x 120 mm and 8 mm thick.  It has 6 holes 10 mm wide and 20 mm from the edge equally spaced along the edges. 25mm wide center hole.

### Evidence
[The Base in Onshape](https://cvilleschools.onshape.com/documents/220e283b758f19cc0b5e016e/w/b99eaa03907efb32ba77c17f/e/48e37ca861b914e94113693a)

### Image

<img src="https://github.com/OneCHSEngr/BasicCAD/blob/master/images/Base.jpg" width="400">

### Reflection

This was my first Onshape part and [following along with Dr. Shields made it super easy.](https://www.youtube.com/watch?v=93BFUD-HAG8&feature=emb_title&scrlybrkr=5670f0b4) To be honest,I don't feel that I learned any new things. On the other hand I feel basic familiarity and sense of fluidity increase (shortcut keys)
Onshape is really nice and renaming sketches is very helpful. 

---


## Mount

### Description

The Second part is a mount to attach to the base for the next part. The dimensions are 100mm x 100mm and 8mm thick. There are 4 10mm wide holes 20mm from edge in each corner and a 25mm wide center hole

### Evidence

[The Mount in Onshape](https://cvilleschools.onshape.com/documents/220e283b758f19cc0b5e016e/w/b99eaa03907efb32ba77c17f/e/48e37ca861b914e94113693a)

### Image

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-09-29%20at%2012.50.58%20PM.png?raw=true" width="400">


### Reflection

This part was very similar the part prior and took little time. While creating the first extrude selecting *new* will make it as whole new part in the same Onshape document. I almost missed this and it would have caused furture problems for me.

---


## Fork

### Description

The third part is the Fork to be attached to the Mount and hold the Wheel. The Main Circle is 80mm and 8mm thick. The Arms are a 40mm by 5mm rectangle 15 mm from the origin extruded 75 mm. Add 15mm fillets on top edges of arms extrude. Add 1mm fillets on edges of the prior fillet. Add a 5mm fillet on the bottom edges of Arms extrude. Arm is mirrored over the Front Plane. 10mm hole 15mm from top of arm through all. Fork Pole is made by a 20mm and a 5mm circle on the other side of the Main Circle concentric to origin,then extruded. Chamfer the Main circle edges and top edge of Pole by 1mm.

### Evidence

[The Fork in Onshape](https://cvilleschools.onshape.com/documents/220e283b758f19cc0b5e016e/w/b99eaa03907efb32ba77c17f/e/48e37ca861b914e94113693a)

### Image

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-05%20at%207.10.36%20PM.png?raw=true" width="400">

### Reflection

First uses of Fillet (shift-f), Chamfer (None), and mirror (none). I had to rename Extrudes to refer to in description.

---


## Tire

### Description

The fourth part is a Tire that will be attached to the Rim which will be attached to the Fork. The dimensions of the Wheel sketch is a trapezoid with a 20mm bottom side, with 10 degree angle sides from the vertical construction line. The inner open space of the wheel is 80mm meanwhile the complete diameter edge to edge is 110mm. Revolve the Wheel sketch to create the wheel. Fillet top outer edge of Wheel revolve 8 mm.

### Evidence

[The Tire in Onshape](https://cvilleschools.onshape.com/documents/0dfb53462fa7bac6dd9b1cba/w/e64599195b87f42e072fdcdf/e/33baf676d790845be69aecf8)

### Image

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-06%20at%2010.59.43%20AM.png?raw=true" width="400">

### Reflection

This part is fairly simple yet introduces some important information to learn. This is the first use of the Revolve tool (none) and  [in Dr. Shields video](https://www.youtube.com/watch?time_continue=181&v=ReEGioIYSus&feature=emb_title) he explains when creating dimensions that going over the centerline will change the dimension value from radius to diameter.
 
---


## Wheel

### Description

This part is what the Tire will go around and will be attached to the Fork. The Wheel sketch for the main revolve looks like this <img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-13%20at%2011.01.46%20AM.png?raw=true" width="125"> (10mm inner diameter and 80mm outer diameter) and is symmetric with the origin and the outer vertical lines are concentric. Revolving this sketch over the horizontal construction line will give you the basis of the Wheel. To create the spokes create a sketch on the face of the Wheel Revolve and cut the highlighted area. <img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-13%20at%2011.39.52%20AM.png?raw=true" width="125">  Add a 2 mm fillet on the 4 inner edges of Spoke extrude. Create a circular feature pattern of the spoke and prior fillet on the face of the Wheel revolve with 5 repetitions. Add 1 mm fillet to either side of the face of the Wheel revolve.

### Evidence

[The Wheel in Onshape](https://cvilleschools.onshape.com/documents/220e283b758f19cc0b5e016e/w/b99eaa03907efb32ba77c17f/e/48e37ca861b914e94113693a)


### Image

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-13%20at%2012.22.32%20PM.png?raw=true" width="400">

### Reflection

This part was similar to the last part with some more steps and details. Having a "multi-shape" sketch to revolve and was helpful to understand the more possibilities with this feature. 

---


## AxleCollarBearings

### Description

The Axle is a 60mm long hollow pipe with an outer diameter of 10mm and inner diameter of 6mm. There is a 10mm deep cut in the axle 4.5mm above the origin on the face of Axle extrude. Reflect the cut to the other side of the Axle.

The collar is a 10mm long cylinder that has an outer diameter of 15mm and an inner diameter of 10mm with a 3mm hole on the middle of the side.

The bearing is a 5mm long cylinder with an inner diameter of 10mm and an outer diameter of 25mm.

The big bearing is 5mma long cylinder with an inner diameter of 20mm and an outer diameter of 30mm 

### Evidence

[The Axle/Collar in Onshape](https://cvilleschools.onshape.com/documents/c3a00428daa468fdb8e3f18b/w/d9df69bce4a86d874c626f3c/e/0de462f5f931bcde25d04d97)

[The Bearing in Onshape](https://cvilleschools.onshape.com/documents/0dfb53462fa7bac6dd9b1cba/w/e64599195b87f42e072fdcdf/e/33baf676d790845be69aecf8)

[The Big Bearing in Onshape](https://cvilleschools.onshape.com/documents/220e283b758f19cc0b5e016e/w/b99eaa03907efb32ba77c17f/e/48e37ca861b914e94113693a)

### Image

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-14%20at%2010.01.53%20PM.png?raw=true" width=400">

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-14%20at%2010.02.46%20PM.png?raw=true" width="400">

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-14%20at%2010.56.50%20PM.png?raw=true" width="400">

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-14%20at%2011.01.30%20PM.png?raw=true" width="400">

### Reflection

All of these parts are fairly simple and quick. They are important for the assembly of the Castetr.

## Wheel/Tire/Bearing,Axle,Sub-Assembly

### Description

This is a sub-assembly of the Wheel, Tire, Bearing, and Axle. Use a fasten mate to mate the origin to the origin to the Wheel. Same with the tire. Use a revolute mate to mate the origin to the origin of the Axle. Use a revolve mate to the outer origin of the bearing to the outer origin of the Wheel. There should be one Bearing on either side.

### Evidence
 
 [The Wheel/Tire/Bearing,Axle,Sub-Assembly in Onshape](https://cvilleschools.onshape.com/documents/d1f10378bda4e6ea6e95967c/w/c72b11adb012fe213c5d8f52/e/f5cd81fbbfff954b6dd66dbb)

 
### Image

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-15%20at%2010.37.30%20AM.png?raw=true" width="400">


### Reflection

This sub-assembly will make our final assembly easier and it reflects how a caster would be assembled in real life. Due to having many multi-part studios finding all the parts to put in the assembly is easier.

## CasterAssembly

### Description

This is the full Caster Assembly. Use the fasten mate to mate the origin to the origin of the Base. Use the fasten mate to mate the outer origin of the Base to an outer origin of the Mount. Use the revolute mate to mate the outer origin of the Big Bearing to an outer origin of the Mount. Use the revolute mate to mate the outer origin of the Big Bearing to the origin of the Base plate on the Fork. Use a revolute mate to mate the inner edge of the fork to the outer edge of the Bearing connected to the Wheel/Tire/Bearing,Axle,Sub-Assembly. Use a revelute mate to mate the outer edge of the Collar to the outer edge of the Fork around the Axle. There should be one on either side. Use a parallel mate to mate the flat edge of the axle to the hole in the Collar on both sides. Add Hex Socket Head Cap (reference images for measurements) to the 4 holes on the Base/Mount. Add Hex Nuts (reference images for measurements) to the underside of the 4 holes on the Base/Mount. Add a Hex Thin Nut (reference image for measurements) to the top middle hole around the Fork pole. Add pins to the holes on the collar (reference image for measurements. Offset the Z direction of the pin by 3mm.
<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-15%20at%2011.56.08%20AM.png?raw=true" width="400">
<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-15%20at%2012.12.15%20PM.png?raw=true" width="400">
<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-15%20at%2012.16.15%20PM.png?raw=true" width="400">
<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-15%20at%2012.32.06%20PM.png?raw=true" width="400">

### Evidence

[The Assembly in Onshape](https://cvilleschools.onshape.com/documents/9766daa676d68de30736d7e4/w/e23d86762ac7771e7f8680e1/e/a2996bd6a1a5485c24c1923f)

### Image

<img src="https://github.com/lmcmind85/BasicCAD/blob/master/Images/Screenshot%202020-10-15%20at%2012.57.16%20PM.png?raw=true" width="400">

### Reflection

This the End of building the Caster. While assembling I noticed a couple issues in some of my parts. Example my Fork Arms were 15mm from the orgin fromthe center of the rectange and not the bottom line. The Engineering notebook and being organized in Onshape (Multi-Part Studios) made it very easy to go back a reveiw, make changes, see what those chnages do, and then either see you've fixed it or if you need revert and continue to fix the problem. 

---

We are making a picture frame

* [Dowel Pins](#Dowel Pins)
* [Frame](#Frame)

## Dowel Pins

### Description

The dowel pins are a cylander with diameter of 1/4 inch and length configurations of 1 inch and 2 inches. Add 1mm champfer.

### Evidence 

[DowelPins]([The Dowel Pins in Onshape](https://cvilleschools.onshape.com/documents/9766daa676d68de30736d7e4/w/e23d86762ac7771e7f8680e1/e/a2996bd6a1a5485c24c1923f)

### Image

<img src="" width="400">

### Reflection

This was the first use of using configuartions. The Table is a easy way to label and manipulate all of your configuations. 

## Frames
### Description

The Frame is a Trapezoid with bottom edge configurations of 10 inches and 8 inches and top edge configurations of 7 inches and 5 inches. The sides have bottom inner angles of 45 degrees. The Trapezoid is 1 inch thick. On the angled side sketch two 1/4 inch circles along equally distanced apart and formthe edges along the middle of the face. The cicle close to the longer side will become a 1/2 hole. The other will be a 1 inch whole. Mirror these extrudes across the trapezoid to the other angled side. 

### Evidence 

[Frame]([The Frame in Onshape](https://cvilleschools.onshape.com/documents/513c736eeaf84316ef617998/w/71fc22c66cf539e02283b72a/e/353294065242f174c2099881?configuration=List_9toj3fyKdqvYnN%3D_7%3BList_hXtXZTxRAFW7fi%3D_5_inch)


### Image

<img src="" width="400">

### Reflection

There are multiple configuraton tables: One for the top side and te other for the bottom sides. 

## Picture Frame Assembly

### Description

The assmebly is done by adding 2 Frames with 10 inch top sides and 7 inch bottom sides and 2 other frames with 8 inch top side and 5 inch bottom side. Add 4 Dowel pins that are 1 inch long and 4 other Dowel Pins that are 2 inches long. Use revolute mates to mate the middle of the pin to edge of the whole. 1 inch pins go in 1/2 inch holes and the 2 inch pins go into the 1 inch wholes. Mate together all parts to for pricture frame

### Evidence 

[Picture Frame]([The Picture Frame in Onshape](https://cvilleschools.onshape.com/documents/513c736eeaf84316ef617998/w/71fc22c66cf539e02283b72a/e/353294065242f174c2099881?configuration=List_9toj3fyKdqvYnN%3D_7%3BList_hXtXZTxRAFW7fi%3D_5_inch)


### Image

<img src="" width="400">

### Reflection

Makeing the parts translucent made it easier to click the right areas for the the mates.
