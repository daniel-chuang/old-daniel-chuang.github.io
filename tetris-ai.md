---
title: Tetris A.I Process Journal
filename: tetris-ai.md
theme: jekyll-theme-slate
layout: default
published: true
order: 1
---
# Tetris A.I Process Journal
#### March 23 - March 25
##### To-do List:
- [X] Learn About OpenCV and Image Recognition
- [X] Learn About Numpy 
- [X] Complete some type of image recognition basic program by end of week.
- [X] Learn About Programs interacting with games through GUI.
- [ ] Make some type of GUI automated random gameplay.
- [X] If time allows: learn about AI theory.
##### Notes:
I learned about OpenCV and Image Recognition. Here's the breakdown on the different things that I learned/did:

1. Learn about Numpy. I learned about Numpy through this website: [https://www.pythonlikeyoumeanit.com/module_3.html](https://www.pythonlikeyoumeanit.com/module_3.html).
I read through every page in that module, meaning I know about different array attributes, functions, iterations, operations, slicing, and indexing. This is particularly important for my ventures into OpenCV, since OpenCV is quite reliant on Numpy concepts.
2. Importing OpenCV (which was suprisingly difficult, since I had some installation issues and Anaconda environment problems).
3. Loading images and understanding the data structure for those images.
4. Image indexing, slicing, and channels. I learned that 3-channel images are three dimensional arrays, where the three axis are width, height, and channels (RGB, or BGR as OpenCV likes to have it).
5. Image Thresholding. I learned how to use image thresholding to isolate certain values given channel parameters. This will be useful for my Tetris AI program, since all the colored blocks will be colored, and everything empty will be black, so this is really applicable. I learned about all the different types of threshold (such as binary, binary inverse, truncated, toZero, toZero inverse, adaptive gaussian, adaptive mean).
![Thresholding Blue Example](images/opencv1.png)
![Thresholding Intensity Example](images/opencv2.png)
6. Bitwise Image Operations and Masking. This is important for actually masking the mask over the original image once you hold the threshold.
7. I learned a ton of other things about OpenCV, but the most important concept that I learned for my game (since edge detection, hough transforms, SIFT and SUFT aren't really needed for my program) was template matching. I can potentially just apply a picture of a block and use that to template match through images of the Tetris gamescreen if I don't decide to use a threshold.
8. I learned about how graphs and weighted edges work. I learned about the basics of different Tree traversals, such as BFT, DFT, and Uniform Search. 

#### March 15 - March 22
##### To-do List:
- [ ] Learn About OpenCV and Image Recognition
- [ ] Complete some type of image recognition basic program by end of week.
- [ ] Learn About Programs interacting with games through GUI.
- [ ] Make some type of GUI automated random gameplay.
- [ ] If time allows: learn about AI.

##### Notes:
I didn't complete any of the above, because I ended up taking a very different course of learning! I learned how to version projects using Git (Command Line Interface, because it's cooler) and Github. Here are three deliverables to prove that I did that:

###### [learngitbranching.js](https://learngitbranching.js.org/)
![Learn Git Branching](images/learngitbranching.png)

###### Git-it
![Git-it](images/git-it.png)
![Git-it Completion](images/git-it-completion.png)

###### Github Pages Website
You are currently on a website that I made using Github Pages and version control! I will constantly be using the concepts that I learned about version control not only for my actual project but also for this process journal. Therefore, this website is another example of my learning in source control that will continue to evolve as I progress in my project.