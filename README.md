## Intro
This repository is to publish the Matlab code used to generate Convolutional Neural Networks for the purpose of knee cartilage segmentation. The code allows for B-Mode images and inputs into the networks and an algorithm of Local Phase Enhancement using the 2D Log Gabor Filter for enhancing images for input into the network. 
There are example networks linked into Google Drive that average 100 MB for U-Nets and 200 MB for Stacked U-Nets and W-Nets. 
The code used here and the networks were used in the M.S. Defense for Justin Mohabir of Rutgers University.

Example networks are availble at: 
https://drive.google.com/open?id=1pkeEFd90OtYlorwElaVA0fjjA-4HPhdR

## Network Notes
The Networks that are prefaced with "B" or "EN" take B-Mode and Enhanced images of size 256x256x1, while networks with "Both" take a combination of the two, namely a 256x256x2 images.
