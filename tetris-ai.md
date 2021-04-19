---
title: Tetris A.I Process Journal
filename: tetris-ai.md
theme: jekyll-theme-slate
layout: default
published: true
order: 1
---
# Tetris A.I Process Journal
#### April 9 - April 16
##### Part I: What did you plan to do this week?
I planned to learn more about artificial intelligence concepts, now that I have my basic imaging and tictactoe game set up. This week was more of a "learning" week, since I had just spent a lot of time creating something. 
###### To-do List:
- [X] Learn about artificial intelligence concepts

##### Part II: What did you actually do?
I ended up finding an awesome course called [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2020/).
I watched the entire [first lesson](https://cs50.harvard.edu/ai/2020/weeks/0/), which was 2 hours long. It covered Depth First Searches, Breath First Searches, Greedy Best First Searches (and the heuristics required to run those), A* Searches initially. Then, it covered adversarial searching through the usage of minimax algorithm, with alpha beta pruning and depth limitation.
I completed the courses' quiz and scored a perfect score: ![Week 0 Quiz](images/week0-quiz.png)
I am currently beginning the project homework of this course.
##### Part III: Was what you actually did different than what you planned? If so, describe how and why? How will you adjust your goals going forward so that they fit more closely with what you actually do?
I didn't do anything different than what I planned, because my goals this week were quite loose and exploratory (in comparison to last week).
##### Part IV: What did you learn or discover that you didn't know before this week? What, if anything, surprised you?
I learned a ton about different search algorithms, and I realized that they were applicable not only to artificial intelligence but to programming data structures. Moreover, I learned how programming is a lot easier when ideas are presented well. The presenter in the lectures is very good at explaining concepts, and has an AMAZING slideshow with great visuals showing every single step so that I can follow along with ease.

##### Note
This week's process journal is a lot shorter and simpler than last weeks because I was just exploring a topic, rather than creating something. This week's acquire skills will be shown during the next week, when I complete my tictactoe artificial intelligence opponent.

#### April 2 - April 9
#### Tetris A.I Project
##### Part I: What did you plan to do this week?
I am planning to make a tictactoe artificial intelligence player to get some experience with all the concepts I will need for my tetris project.

###### To-do List:
- [X] Program a tictactoe game in Pygame
- [X] Program an opponent for that tictactoe game.
- [X] Make an imaging program that takes the screenshot of a tictactoe game image whenever "SPACE" or "ARROW KEYS" are pressed.
- [X] Use the images that were recorded in the program to output an numpy array and the coordinates of the cursor in the imaging program.
- [ ] (If time allows) Learn about machine learning.

##### Part II: What did you actually do?
I was able to do all of the goals above except for the last one (which I didn't plan to do anyway, I just wanted to set that goal for the future and in case I finished everything this week already). 

I ended up spending a TON of time this week doing all of the tictactoe game programming (both the game and the opponent), as well as the imaging program. 

I estimate that I spent around 10 hours on all things combined. There were tons of errors that I had to deal with and I had to mess around with the configuration of many different Python imaging packages. I originally used pyautogui and PIL for taking the screenshot, but it was taking screenshots really slow due to the way that MacOS works, so I had to do some really deep digging to find the mss package, which is much faster. I also had to figure out how to do key inputs for my imaging program to detect whenever a key is pressed, which brought me to the process of choosing between polling or broadcasting.

Finally, after I figured everything out, I had to make it so that the OpenCV could read the image pixels and output a numpy array.

Here is a video of everything in action: [https://youtu.be/p3TDLD6Ikd4](https://youtu.be/p3TDLD6Ikd4)

<!-- blank line -->
<figure class="video_container">
  <iframe src="https://youtube.com/embed/p3TDLD6Ikd4" frameborder="0" allowfullscreen="true"> </iframe>
</figure>
<!-- blank line -->

Here is the code: [https://github.com/daniel-chuang/tictactoe-ai](https://github.com/daniel-chuang/tictactoe-ai)

##### Part III: Was what you actually did different than what you planned? If so, describe how and why? How will you adjust your goals going forward so that they fit more closely with what you actually do?
The things that I did this week were the same as what I planned (this week).

##### Part IV: What did you learn or discover that you didn't know before this week? What, if anything, surprised you?
I learned that MacOS has a very weird screenshotting system, meaning that if I use a normal screenshot function from PIL or pyautogui, it will be INCREDIBLY slow.

I also learned that I can run two Python programs simultaneously through terminal using os.system.

I also learned how to use pynput, which broadcasts whenever a key is pressed. I'm pretty sure that pynput uses multithreading, so that's how that works.

I am going to learn how to implement basic machine learning algorithms next week, most likely through the [Harvard CS50 Machine Learning Class](https://cs50.harvard.edu/ai/2020/), or through the [Codecademy](https://www.codecademy.com/).

#### Ethics Project:
##### What did you do to move your project forward with your partner this week?
Final Position Paper Link: [https://docs.google.com/document/d/1VKxIJWV_r6x4_YkmF8lySWUZQmkHd-Vxrp9BFuAKbvg/edit](https://docs.google.com/document/d/1VKxIJWV_r6x4_YkmF8lySWUZQmkHd-Vxrp9BFuAKbvg/edit)

Final Presentation Link: [https://docs.google.com/presentation/d/1qI1vRSgysdN-25U2J6AQAey1-67Kv6D_EJoZkeuDg6Y/edit?usp=sharing](https://docs.google.com/presentation/d/1qI1vRSgysdN-25U2J6AQAey1-67Kv6D_EJoZkeuDg6Y/edit?usp=sharing)

We finished our project this week! We spent a long time making both the slides and the position paper, as well as researching the topic. I certainly learned a lot. I also used a darkweb dataset [https://www.kaggle.com/philipjames11/dark-net-marketplace-drug-data-agora-20142015](https://www.kaggle.com/philipjames11/dark-net-marketplace-drug-data-agora-20142015) to create a chart for our presentation!

![Dark Web Listing Plot](images/darkWebItems.png)

##### What are 1-2 things you can do next week to move the project forward with your partner?
Not applicable, Kai and I already finished! I might keep on using dark web databases for practice making charts in the future though!

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