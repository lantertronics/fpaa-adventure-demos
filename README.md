# fpaa-adventure-demos
Demos for Prof. Jennifer Hasler's RASP 3.0 FPAA architecture

These demonstrations are for tor the RASP 3.0 FPAA architecture developed by Prof. Jennifer Hasler of Georgia Tech. The run in a Scilab/Xcos-based toolset her team developed. The current publically available tool runs in a VirtualBox Ubuntu image, which you can obtain here: https://hasler.ece.gatech.edu/FPAAtool/index.html

The password for the image is "reverse."

Many of these demos are featured in my "Adventures in Field Programmable Analog Arrays" YouTube series: 

https://www.youtube.com/playlist?list=PLOunECWxELQTCZEqIbHZpRmIEeQR80o3j

I developed these demonstrations using an experimental fork of the tools that uses Scilab 6 instead of the Scilab 5 used in the Ubuntu image. That fork isn't stable enough for me to release into the wild yet, so you're right now you need to use these in the Ubuntu image. Unfortunately, links between blocks disappear when you load a Scilab 6 Xcos design into Scilab 5, so you'll need to relink the blocks yourself. For each Xcos file, I provided a PNG file showing the design so you know what needs connected.

On a few of the designs, Scilab somehow decided to add a massive amount of blank space at the top and the bottom of the designs, so you have to scroll down for a while to find the blocks. I can't figure out how to get rid of the space without recreating the diagram from scratch. 

Don't assume that the parameter settings in any given file are idea or even realistic;n they're likely set to whatever I used in whatever the last simulation I tried was, which may or may not have been harebrained.

WHen I find some time, I will add some notes to this README about what each file does.
