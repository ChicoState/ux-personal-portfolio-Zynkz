# Auto Stacking with Autostakkert
I decided to try out Autostakkert, which is an image-stacking software for astrophotography. It's essentially a type of photoshop for hobby telescoping rather than a method for scientific research. I decided to see what it can do because I'm making a similar software for my capstone and thought it would be a good idea to have a base-level understanding of the market.

When stacking, it's common to have a reference image that you'll use to align all your images together and be able to remove any images that deviate too much in quality relative to the reference image. The goal is to reduce noise in the system that was used to take the pictures. This can be things like jet streams, an unstable mount, clouds, or inaccurate tracking.

When setting up your image set to be processed, you'll select your reference image and place points in notable areas called alignment points. These points are to assign an area within all images that hold important and notable features. For the moon, this could be something like a crater or a sea that has a lot of detail. We want to make sure we have them as aligned as possible so that when we stack the image, that detail isn't lost.

For Autostakkert,
when selecting a folder/file to open in a program, it's **common convention** that you're given a window to navigate to the folder/file you want to select and either double-click the file or click the "Open" button when selecting the folder. In their case, if you navigate to the folder where your images are, the button to open the folder is faded and you can't click on it but the **error was recoverable** by selecting the folder just above the folder I wanted and selecting the folder I wanted in the separate display area at the bottom.

<img src="./open_wrong.JPG" width = "50%" height="50%">
<img src="./open_right.JPG" width = "50%" height="50%">

When assigning my alignment points, before knowing how to, I figured the left click must be how to place them and I figured Ctrl-click, Alt-click, Shift-click, or Right-click would be how to remove them. Any one of those would meet my expectations for how the software should work. In this case, my **mental model** (how I think it should work) matched the **conceptual model** (how it actually works). You find which image you want to use and then you can add alignment points by left-clicking and remove them by right-clicking.

<img src="./alignment_points.JPG" width = "50%" height="50%">

