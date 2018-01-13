---
layout: default
theme: jekyll-theme-midnight
title: My Python work
permalink: /python/
---
<a href="https://raniaspant.github.io/">Home</a> | <a href="https://raniaspant.github.io/python/">Python</a> | 
<a href="https://raniaspant.github.io/c/">C</a>| <a href="https://raniaspant.github.io/unity3d/">Unity3d</a> | 
<a href="https://raniaspant.github.io/about/">About me</a>

## ![](http://www.analyticskhoj.com/wp-content/uploads/2015/10/xPython_logo.png.pagespeed.ic.lnG8EbA9-q.png)

### [](#header-2)Neural Networks related

Python scripts I developed on Neural Networks, i.e. architecture, training, testing.

* ### [](#header-3)[AND, OR, XOR gates using offline and online learning](https://github.com/raniaspant/NNgates)

Running the scripts will produce error and weights plots.
The scripts contain the architecture of the networks with all the layers (2 for XOR and single layer for AND and OR) without the usage of auxiliary libraries.

Developed in PyCharm.

* ### [](#header-3)[Hopfield network simulation in asynchronous and synchronous mode](https://github.com/raniaspant/HopfieldNN)

Developed for my Neural Networks course. The custom vectors used are described in the repository's README file.
The exercise was asking the implementation of synchronous mode for the first 2 vectors and then with all 6 vectors, and the same for asynchronous mode. Of course they can be replaced with custom vectors. The software was implemented in Octave. In each file (synch.m and asynch.m) user can change the initStates variable to define if the program should run with 2 vectors or 6 vectors. Each .m file is printing the results to a synch.txt or asynch.txt file.

Developed in PyCharm.

* ### [](#header-3)[Simulation of Kohonen Network in 1D and 2D](https://github.com/raniaspant/KohonenNN)

Mapping in (0,0) – (1,0) – (0,1) triangle
Using η0 = 0.1, d0 = 3, T = 1000
Weights are initialized randomly in a custom defined rectangle within the triangle.

Both scripts produce plots throughout the iterations to show the changes in the weights' coordinates.

Developed in PyCharm.

* ### [](#header-3)[Predicting current season’s NBA match outcomes using Feedforward Neural Networks](https://github.com/raniaspant/NBApredictions)

Multiple scripts developed for this one! Not just network architecture this time, but also HTML parsing was needed in order to gather statistics from online websites. This was our final project for the Neural Network course, and you can read more thoroughly our implementation thoughts and progress in [this report](https://github.com/raniaspant/NBApredictions/blob/master/ECE%20572%20Neural%20Networks%20Term%20Project%20Report.pdf). It is basically a simple feed forward NN architecture using Keras deep learning library in Python. 

Developed in PyCharm.

### [](#header-2)Other work

* ### [](#header-3)[Parse statistics from online sources](https://github.com/raniaspant/stats-scraping)

If you want to get data from basketball-reference.com, then this is your script to go. I developed it to save myself a lot of time and trouble by manually gathering statistics for another project I needed. Couldn't find anything similar online, so I decided to build a script on my own.

Developed in PyCharm.


* ### [](#header-3)[CHORD P2P network simulation](https://github.com/raniaspant/CHORD-simulation)

Simulation of the lookup algorithm in a CHORD P2P network for my Advanced Computer Networks course.

The active nodes are generated using the Linear Congruential Generator.

You can read the pdf included in the repository for instructions on how to run and how it is executed.

I tried implementing a GUI using Tkinter instead of just printing everything in the console. ~~It didn't work that good.~~ But it was worth a shot. Hopefully my Tkinter skills will grow over time, or replaced with other better GUI Python techniques.

There are default values for the Generator if you don't enter any. The path the lookup algorithm followed is also shown in a table after you enter the key value you want to look up.

Developed in PyCharm.
