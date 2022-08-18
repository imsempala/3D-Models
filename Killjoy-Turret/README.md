# Valorant Turret Model

***Currently the STL file view is messed up, but you get most of the model when viewing the STL.***

<img src="https://user-images.githubusercontent.com/108013840/185503422-6c17da37-9259-4d99-a8bd-6f9ba1c482e1.png" width="500" height="500">


I decided to try and make a 3D printer friendly assembly for one of the models in the game Valorant. The model is a turret that the character Killjoy can place. This was done using Fusion 360.

This is my first attempt at making a complicated model for 3D printing and the print is very unoptimized. I recently purchased a 3D printer so I do not know what it is fully capable of, so I designed the components in a way to minimize print failure. Many of the parts are split so a flat surface can be used for printing.

## Joint Rotation

<img src="https://user-images.githubusercontent.com/108013840/185502880-2a0fa105-575b-490a-a646-625c073d16f7.png" width="500" height="500">

For all of the leg joints, I allowed 15 degrees of movement in both direction using the design above. This may not translate well with 3D printing and may require much post-processing to work correctly. This is depended on the resolution of the printer used and the scale at which the design is printed.

## Turret-Head Rotation

The turret head is given a full 360 degrees of motion, although in game the turret can only see 180 degrees in front. I overengineered the pivot point to ensure stability with the turret-head. I am not familiar with the strength and weight properties of the printing material, so I ensured a strong pivot joint.

## Snap-on Details

<img src="https://user-images.githubusercontent.com/108013840/185503945-a3c720ac-0122-43f9-9742-4cb99173de3e.png" width="500" height="500"/>

There are riveted points on the feet of the turret. I thought that these details would be hard to 3D print accurately so I decided to print them as a different component. I utilized a tapered and cut snap joint for easy assembly. 

I realized later on that these details could have been printed with the feet and not have been seperate componenents due to its small size and > 45 degree angle overhang.

## Other Details

I used dove-tail joints or modifications of dovetail joints to lock components together. The gun barrel and turret head will be slid on using dovetail joints. There are also a few aligning components to ensure rotational alignment.

I avoided the use of screws as I wanted to keep the piece 100% 3D printed, and I wasn't familiar with printing threads using my printer. 

There's still a lot of work and testing that needs to be done with this model. I wouldn't recommend printing it.
