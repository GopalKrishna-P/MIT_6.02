# Introduction to EECS II

## Course Information
This repository contains summary of the my coursework for [**MIT 6.02: Introduction to Electrical Engineering and Computer Science II**](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/index.htm).

This course teaches introduced in the [**MIT 6.01**](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/index.htm) like abstraction, probabilistic analysis, superposition, time and frequency-domain representations, system design principles and trade-offs, and centralized and distributed algorithms.

The course is divided into 3 units:
- Bits
- Signals
- Packets

### Resources

- Lecture Slides : [link](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/lecture-slides/).
- Video lectures : ["MIT 6.02, Fall 2012"](https://www.youtube.com/playlist?list=PL9B24A6A9D5754E70Q).
- Readings : [6.02 course notes by Hari Balakrishnan, Christopher Terman, and George Verghese](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/).

## Assignments

All the assignments are in python and the following are some required [packages](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/syllabus/software/) needed.

Since, the assignments are using python 2.7 and we'll be going with the 32-bit versions as some of the math libraries we use aren't yet available as 64-bit versions.

We can use anaconda in creating a virtual env with all the required packages so that it would cause trouble with existing installs of the same packages. Make sure you have installed latest [anaconda](https://www.anaconda.com/) and run the following.

```
$ conda create --name MIT_602 python=2.7
$ conda activate MIT_602
$ pip install numpy==1.5.1
$ pip install matplotlib==1.0.1
$ pip install wxPython==2.8
```
