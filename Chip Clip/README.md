# Chip Clip Journey

I eat an unhealthy amount of chips and wanted to make something to seal the them.

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

I decided to embrace the unclipping method by pushing one side below, and made it easier to do so. I solved the bowing issue by making the clip slightly larger, and changing the geometry of the clip to resist bowing.

One of the unseen changes here is the organization of the Fusion360 CAD file. The last CAD file was a complete mess and changing any parameter was difficult. I made sure every parameter was easy and simple to adjust and everything was defined.

