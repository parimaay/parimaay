---
layout: post
title: Unity & Vuforia First Impression
date: 2018-07-30 00:00:00 +0300
description: How it went my Hello World project with Unity and Vuforia
img: ar.jpg # Add image post (optional)
tags: [Augmented Reality, Vuforia, Unity, Programming, Learn] # add tag
---
It was a long time that I wanted to give Augmented Reality a "test drive" to see how it works and let's be honest, it's one of the coolest current technologies.
I started by following [this tutorial](HTTPS://youtu.be/Wqbg9mB84V4) on Youtube which was almost enough for a "Hello World" project. Basically, it's starts with setting up a new project following by a database on Vuforia website (The free version) in order to add a target image. Later on, this target image is used for the image tracking part. It also provides all the used images for the print purpose which saved me a good amount of time instead of searching for a good one by myself. As a matter of fact, Vuforia creates some "features" on the target image and uses those parts in the image recognition/targeting time and generates a database to be used by Unity.

Next step is to install Unity itself and setting it up with AR/VR and what else you would need. I personally, downloaded the integrated one from [Vuforia Downloads](HTTPS://developer.vuforia.com/downloads/sdk) section. The installation itself, takes a lot of time, so I had to leave it while installing and come back to it later. Following the tutorial, it explains how to create a new project and to add the provided assets such as the target image and actions, animations. I had some problems at this point because either the target image was not showing correctly or the embedded 3D object wasn't appearing even on the workspace. In addition to that, Unity app was crashing every time I was trying to import the Assets folder. I also tried to submit the crash reports using built-in wizard but it crashed as well.

Finally, I realized the best way to add the new Asset is to just drag and drop the whole folder instead of using the Unity Add New Asset button. Any ways, as soon as I setup everything as said during the tutorial, wanted to run the demo and see how it would work, but the camera wasn't starting on my Mac. Actually, I could see the green light next to the camera when I hit play, but I kept showing the black screen. Searching for the same error in Google, I realized I had to modify the webcamprofiles.xml file in default setting of Unity which, people keep complaining about it since last year as it is actually a bug and should be fixed by Unity but so far no fix. The funny thing is instead of *FaceTime HD Camera (Built-in)* should be written *FaceTime HD Camera*.

After all these dark parts and unsuccessful attends, I finally made it to work and I could check the result using my Mac camera which was pretty cool to see.

As the next step, I'm goanna test with some self-created target images, and try to show different content such as video or text. Apart from that, for a further jump, would be nice trying to write some scripts by myself to at least get my hands dirty a bit with C#. To be mention that, I have no prior knowledge upon C# and 3D rendering. Let's see.

I also need to mention that, Unity has a very active community supported either by developers and also creators as well. After registering, almost every Friday I am receiving an email with new tutorial and some examples to start with the tool and how to go deeper which to me is a huge plus.

I will continue writing on my next experiences and impressions on Unity and Vuforia and share my knowledge and difficulties as well.

Happy coding!

