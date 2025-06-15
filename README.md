# Bento

![A photo of Bento, a computer in a keyboard](https://github.com/user-attachments/assets/d9bac3c8-aa03-4546-88ae-747c9bedbc12)

# What is Bento?

Bento is a computer. Its name come from it's distinctly bento box look, and it takes inspiration from the Comodore 64, and the many creations on r/cyberdeck.

It fit perfectly underneath a keyboard, which acts as a lid! Giving you easy access to the internals, as well as a compartment to store various small peripherals.

![Inside bento](https://github.com/user-attachments/assets/4a38fb38-fbdb-43cf-b44e-4cf81801ce72)

## There is no display

This is key. Bento is meant to be used with an external display, particularly spatial displays like the XREAL One’s, but obviously it still works with any external monitor with USB-C.

The reason for this is to eliminate redundancy. As I find myself using XREAL more and more, the built in display for my laptop or my steam deck goes unused and is simply added weight. Bento removes all that is non-essential, cutting back on weight and making it even more portable.

## What’s inside?

![a look under the hood](https://github.com/user-attachments/assets/3f0a9b38-8294-42f1-bb01-9b6f2e007e9c)

This version is powered by the main board of a Steam Deck OLED. It uses the same cooler and battery as well. I chose this board because it was the thinnest and most powerful available. But it can easily fit other SBCs that are more readily available. 

## Why build this

Primarily out of frustration. The dominant players in XR keep promoting their hardware as “computers”, when really they’re an iPad for your face. The most you can do is browse the web, play games, and consume content. They’re overweight and over constrained. 

If you want to do any _real_ work, the best you can do is mirror your screen from a _real_ computer. This is one of the most popular use cases outside of gaming. 

If this is true, then we should lean into it! Create a spatial display and ship a computer explicitly designed for it. 

This is why I built Bento, a computer designed to be used with spatial displays. I propose to you that it is closer to a “spatial computer” than anything else we’ve seen.

## What you'll find in this repo

All the STEP, 3MF, and STL files for bento, as well as a few periperhals like a Magic Trackpad tray.

![A screenshot of Bento in Shapr3D](https://github.com/user-attachments/assets/d634d455-5398-438e-89d9-d4f9e7b7ca3c)

## Request for Contribution

I intend to keep working on this project, but I’m open sourcing it because I can only do so much on my own. I’m currently working on a “pro” version with a switch 2 like mounting system to support modules. But here are some things I could use help with:

* **Support for other keyboard**: I picked the Magic Keyboard due to how ubiquitous it is, but there are better keyboards out there.
* **Raspberry Pi 5 variant**: this is crucial, but I can’t find a _good_ battery solution (i.e. a HAT of some kind.)
* **A framework variant**:  This may require a larger base keyboard and will likely eliminate storage (physical, not digital.)
* Support for other SBCs in general.
* **Peripherals**: I have some sketches for a gamepad and a mouse that could fit perfectly in the compartment, but I would happily acquiesce to someone else with board design skills.

If you do decide to create your own variant, all I ask is that you **make a PR back to this repository**, so that other’s might benefit from your work.
