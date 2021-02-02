Copyright (c) 2021 Robert Eveleigh
and Copyright (c) 2017 Jake Wright

# docker-testing-part1

This is a docker setup and testing if docker is setup and going part 1

The following  information is based on a youtube video ..

In this 12 minute video, I introduce Docker and show you how to build and image and run a container.

[Watch Learn Docker in 12 Minutes](https://youtu.be/YFl2mCHdv24)

<img align="right" src="http://i.giphy.com/QHE5gWI0QjqF2.gif" width="260 "/>

This repository contains the source code from the YouTube tutorials at http://youtube.com/jaketvee

The Diferance is that I am adding timeline and links to all files and screen shots as needed

0.00 - 2.40     saying what is docker and how to use it
2.41 - 2.58     installing Docker

I have added some screen shots for the installing docker ..
But I don't like how he shows you ..
Here is the link to  (http://testting.docker.eveleigh.ca/part1.html)

2.59 - 3.25     adding the scr directory and adding index.php these are in the directory here...
3.26 - 6.37     installing Dockerfile not in the scr directory
6.38 - 6.41     Next we need to build the image by going to the main directory of the site I.E cd docker-testing-part1 you should have the scr and the Dockerfile in it.
6.42 - 7.17     This how you  build it by typing I.E (docker build -t hello-world .)
7.18 - 7.50     Now you can run your image by typing
I.E (docker run -p 80:80 hello-world)
7.51 - 7.59     You can now test it buy going to you bowser typing I.E (localhost). you should be able to see hello world on the page.
8.00 - 9.52     IF you want to make changes you will need to rebuild the image or add this part to your site as stated by him this will depend on your computer..
9.53 - 10.10    This part remines you need to rebuild the image again..
10.11 - 12.01   Doing a recap of the video..

This is the end of my README.md   ...

Thank You
Robert Eveleigh
