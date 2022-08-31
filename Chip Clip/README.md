# Chip Clip Journey

I eat an unhealthy amount of chips and wanted to make something to seal the them.
** This was done using Fusion360 using a combination of solid and surface modeling **

## Version 1
The following is the first version of a chip clip design. It includes a pushing locking mechanism, inner ridges for sealing the bag, and a rotational joint. The CAD was designed to be print in place without any supports. 

### Flaws

Although it was successful in sealing chip bag, the locking mechanism was too difficult to take apart and the part itself unecessarily large in terms of width and thickness. This consequently increased the printing time. 

I wanted a design that was sleek, took less material, and was faster to print.

<img src = "https://user-images.githubusercontent.com/108013840/187483845-ae895758-8f64-4ee8-a5e5-723418891220.png" width = 400 height = 267>

## Version 2

I came up with a new version which greatly reduced its size and in my opinion, looks far better. 

<img src = "https://user-images.githubusercontent.com/108013840/187485803-31b7a5cf-2d6d-4125-9f1e-db95a4d069f2.png" width = 500>

For this design, I thought it would be easy to just slide the chip bag between the two sides for clamping and have some sort of clipping mechanism to hold the chip clip closed. And so, I added a circular relief cut in place of the pivot joint to improve fatigue life by reducing crack propogation, and to allow for slight expansion of the clip. Male and female ridges are placed on the inner face of the two sides to allow for sealing of the bag as well.

The clipping mechanism is shown below. A "pin" and relief cut on one end to allow for movement, and a slot on the other to hold the "pin" in place. The height of the poin is increased to allow someone to push and unclip the mechanism. Edges are rounded to ensure a smoother transition when closing. Although the pin is very small with a diameter of 1.5 mm, it is surprisingly sturdy. There is also a satisfying click when pushing the two sides together.

<img src = "https://user-images.githubusercontent.com/108013840/187488950-6b31c4c1-be0a-464c-b4f2-0f1536b6c2c0.png" height = 300>

### Flaws

The pin was too difficult to push to unnclip the mechanism. Instead of using the pin, I ended up forcing one side down until it unclipped. A general visualization is provided below.

<img src = "https://user-images.githubusercontent.com/108013840/187490995-35c709bd-0420-467e-b2a5-d48da458cf77.png" height = 300>

The clip also plastically deformed over time. As chip bags were clamped and unclamped, the inner edges of the clip started to bow outwards, reducing its clamping capabilities. 

Additionally, the inner ridges added were fairly useless in sealing the bag.

## Version 3

![image](https://user-images.githubusercontent.com/108013840/187759906-b54890bc-bc8d-4d25-89fa-659de788773a.png)

For this iteration I wanted to improve a few things:

- Sealing properties
- Flexture resistance
- Length
- Clipping feature

### Sealing Properties

Because of the small dimensions, the sealing ridges of the previous design were ineffeective. I decided that the seal should take up the entire height of the component to both emphasize the sealing properties and increase rigidity

The following section analysis shows how it was implemented.

![image](https://user-images.githubusercontent.com/108013840/187761185-48ce9549-491d-45df-b340-daa80dc79541.png)

### Flexture Resistance

The inner side of the clip is given a slight curve to improve bowing resistance. The last iteration bowed like closed parenthesis as seen here: (). This left a large gap in the middle which reduced clamping pressure and eliminated sealing properties. This was caused from clamping things that were too large, causing the inside to expand when clamped.

I changed the design to follow an unmatched parenthesis like curve as shown here: )(. This hopefully reduces the bowing done to the component when clamping thicker objects. 

![image](https://user-images.githubusercontent.com/108013840/187762613-27805371-1f13-42a8-968e-7d0d02a9ff26.png)

I also changed the geometry/profile of the sealing mechanism to further reduce the bowing.

### Length

The previous design was too small to easily seal even the thinner chip bags. I increased the length by 50 mm (45 mm in sealing) to fix this.

### Clipping Feature

Although the side pushing mechanism was easy, it would cause fatigue and surface wear at the clip. I made it easier for a person to unclip the mechanism using a lever arm. One push on the side and it comes apart.

![image](https://user-images.githubusercontent.com/108013840/187764378-4da11af6-7739-496b-a6a6-32ce39da7e15.png)

### Unseen Changes

One of the unseen changes here is the organization of the Fusion360 CAD file. The last CAD file was a complete mess and changing any parameter was difficult. I made sure every parameter was easy and simple to adjust with everything defined.

## Overall Thoughts

I am very happy with how this design turned out, but I have yet to test out if the bowing resistance design decisions are enough to keep the chip clip from bowing. I think I'll move on to something else, spent way too much time on designing a chip clip.

An STL of the final design will be provided and if you click on it, you can view the 3D model.
