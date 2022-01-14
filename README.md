Date | Semester Milestone | Project Milestone
---|---|---|
*Sun, 09 12* | **Deliverable 1:** New Learning | Pick a project on what you want to do with specifics. These specifics being to pick the type of project I want to do, how I'm planning on doing it with a time line and learning plan that I took some time to make, look for and research different courses and sources for my project whether it's to either gather information or to start learning, then finally, start working on my project after picking my API. I'm planning on doing a mask detection robot which gives a certain command based on if someone is or isn't wearing a mask then putting a warning on a message board. Other part of the plan is for when I finish the first part.
*Sun, 09 26* | **Deliverable 2:** New Learning | Start learning and developing some scraps of different coding languages after finding a suitable course to learn the language that I intend to do the project in. (In this case it's Python). Then finally start working on and developing my skills in Python and finalize my choice for the API and commit to the learning.
*Sun, 10 12* | **Deliverable 3:** Project Foundation | For this deliverable I have decided finally how to do everything and had built a base foundation of this using some knowledge I acquired after I was granted permission to use CodeHS for learning python. As a reminder, I want to make a facial/mask detection robot that uses an API to be able to see whether someone is wearing a mask or not and give an appropriate response. Since this is only the base, I started working on CodeHS to learn about everything and the screencast is on the third deliverable in the repo.
*Sun, 10 26* | **Deliverable 4/5:** Building my Project | In this deliverable, make sure you have solid evidence with some good work to back it up at the end of the day so that you can go back and continue working on the project. At this point have something that works for your code so that you have something for feedback. This can mean something simple like a function in the project that just does something or get the entire code up and running for feedback. Point is, have something for feedback.
*Sun, 11 16* | **Deliverable 6:** Project Code and Feedback Plan | After completing a large portion of your project, make sure to have someone or some people give you feedback. Whether it's on bugs you must fix, the user interface people aren't happy with, or anything that equates to what criticism is. You may take these as feedback and change your code, note the ideas down so you can consider them, OR if you don't like some of the feedback given to you, simply forget about it.
*Sun, 12 9* | **Deliverable 7:** Project Code and Feedback Plan | After completing a large portion of your project, make sure to have someone or some people give you feedback. Whether it's on bugs you must fix, the user interface people aren't happy with, or anything that equates to what criticism is. You may take these as feedback and change your code, note the ideas down so you can consider them, OR if you don't like some of the feedback given to you, simply forget about it. This time get some more feedback from more people. It's the same song and dance, eh?
*Sun, 1 13* | **Deliverable 8:** Final Project | Complete the final project to the best of my ability.

---

# Deliverable 8: Final Project

As this is my final project for the entirety of the semester, I tried my best to get things to work. Unfortunately, the stack overflow code that I use for python was abondened as a project and was impossible for me to get the picture to work however, I brought my A material today! I found out how to work with tkinter on python as a GUI for CodeHS (because it's the only IDE that worked) and got to an acceptable level. Thank you for sticking with me this entire process!

*Project Title:* Face Mask Detector 

*Project Description:* This Project was supposed to use a camera and use face detection technology to see if it can detect if someone is either wearing a mask, wearing a mask incorrectly, or not wearing one at all using a trained A.I. that can tell the difference between those 3 and will display a message for the appropriate charge. I had bigger plans for a camera to be mounted on a robot to patrol the first floor of the school and warn people in that way but God knows how long it'd take me eh?

Mask on: "Thank you for wearing your mask!"
Mask off: "Please wear your mask!"
Mask on (incorrectly): "Please wear your mask correctly!"

*Project Motivation:* I guess other than saying that it was used for safety, one of my main motivations was to have fun and learn a new language since I thought that it'd be cool. It would also serve as a good challange for me to make which is all the more reason to have fun with it!

*Demo:* There not too much to show to be completely honest except these:

*Technologies Used:* For this project, I mainly used CodeHS to learn the new language from scratch while also developing both a GUI and a randomizer like how the masks work also in CodeHS

*References:* 
1. https://stackoverflow.com/questions/604749/how-do-i-access-my-webcam-in-python
2. https://github.com/sheldonsebastian/face_mask_detector
3. https://codehs.com

*Limitation:* I had a lot of limitations here. One of them is not having a working IDE, the second is that I accidentally spent more time learning the language than actually typing something in for a code because of the fact that for the longest time, I didn't know where to start. Some others are the fact that the CV code for stackoverflow probably only works for microsoft because it didn't work on my camera even after hours of trying. Also, make sure to compile all the code together and work on it at once so that you know what is what.

*Installation:* This is very simple. All you have to do is have a valid python and tkinter IDE to set up the GUI and the actual code then make sure they merge using an API of sorts so that both codes run at once. Make sure to keep indentation the same and make sure everything is working. Have a camera set up so that it can access the webcam and in this case, you can complete the code for me. Documentation is on the previous deliverable by the way.

*Reflections and all:* All the reflections below are timed so that you can see my process and the timetable on the very top shows what deliverable was done on what days.

---

# Deliverable 7: Project Code and Feedback Plan

For the second to last deliverable, I stupidly decided to keep the goal the same thing even though it's not very relevant now is it? Well anyway, as I was saying, I started looking into more tkinter things and graphical knowledge about python so it is unfortunate but I had to get off track to do this so my goal was not achieved this time around. However, I will be able to fix this by getting back on schedule once I know that I did a good job or at least a considerable amount of work before going back into the final project. The documentation will serve as a great way to get back on track once I've done the deed and learned everything I should've. This means that next CC2 class will be me asking a bunch of questions to Mr. Bowman about my experiences.

### Reflection So Far

1. In this session, I did some research on websites and videos that were recommended to me by Mr. Bowman as well as added some comments that will soon be relevant to the code as I get used to and learn tkinter. By the end of it all, I wish to have learned more about graphics than I generally did know but for now, I will continue to reasearch graphics and clickable/interactive graphics.

``` 
# This program is for my facial detection files and code.
# This is a hard project but fun to do.

# On stands for if the mask is on
# Off stands for if the mask is off
# Incorrect means that they're wearing the mask wrong
# The response can be the same every now and again but I assure you it's random chance.
# These are replacement or temporary variables until the real ones can be made

pic_one  = "On"
pic_two = "Incorrect"
pic_three = "Off"
pic_four = "Incorrect"
pic_five = "On"
pic_six = "Off"
pic_seven = "Incorrect"
pic_eight = "Incorrect"
pic_nine = "Off"
pic_ten = "On"
pic_eleven = "On"
pic_twelve = "Incorrect"

# This is supposed to randomise what picture it chooses every time it runs
# Use tkinter for user interface
# Make sure to have something as simple as buttons to change interface
# Buttons add a layer of complexity for the code

import random
vars = [pic_one,pic_two,pic_three,pic_four,pic_five,pic_six,pic_seven,pic_eight,pic_nine,pic_ten,pic_eleven,pic_twelve]
print (random.sample(vars, 1))

# This if function is to decide the next course of action once an answer is found
# This function is to take the output of the RNG function and give the appropriate response to the output
# Else function was not included because at the time it would be useless but good to have just in case an error emerges

"""
if random_pic() == "On":
    print("Thank you for wearing your mask!")
elif random_pic() == "Off":
    print("Please wear your mask while you're in a public area.")
elif random_pic() == "Incorrect":
    print("Please wear your mask correctly")
"""
```
2. Feedback:
- Use tkinter to further imrpove and complicate the code
- Make a GUI which is servicable to people and user-friendly
- Figue out how to work graphics and clickable graphics for the code
- Make sure to do this before the deadline
- Research upon tkinter more before starting like videos and websites like W2Schoools

This last portion of the deliverable is reserved for the final project documentation from now 'till the end of the semester of computer coding 2...

3. Final Project Documentation:
-Researched tkinter and how to install only to be told that the CV I was given doesn't work on apple
-Started fiddling around with CodeHS and fianlly learned how to make an interactive GUI
-Continue with trial and error until I got it right
-I have finally done it! I was able to make a GUI!:

```
# Imports all graphic file to GUI
# Import is used mainly to get the contents from the library
import tkinter as tk   

# This text is the output of clicking an interactive box
# Output will be the print line below as write_text
def write_text():
    print("Taking Picture...")

# Makes frame for canvas and generates it
# Generates in the sense that you have to run the code to get it to work and it turns off automatically after a set time.
parent = tk.Tk()
frame = tk.Frame(parent)
frame.pack()

# This function actually makes the button interactable with
# All the functions underneath are the same but shifted to the right and left
text_disp = tk.Button(frame, 
                    text="Take Pic", 
                    command=write_text
                    )

text_disp.pack(side=tk.LEFT)

exit_button = tk.Button(frame,
                    text="Finish",
                    fg="blue",
                    command=quit)
exit_button.pack(side=tk.RIGHT)

finish_button = tk.Button(frame,
                    text="Analyze",
                    fg="green",
                    command=quit)
finish_button.pack(side=tk.RIGHT)

parent.mainloop()
``` 
---

# Deliverable 6: Project Code and Feedback Plan

For this part of the assignment, I was told to get feedback from someone and I got some from the man, the myth, the legend: Mr. Bowman! I'm happy to say that I got some very good feedback for my project. The goal for this deliverable is true to its name so my entire plan was to get some feedback, which I did and I found it really helpful. See, I had the right idea of what I should do regarding several elements to the project but then also realizing I don't know where to start. My goal was getting feedback and I did! All I have to do is remember the advice I was given by Mr. Bowman to continue working on this and hopefully I can get somewhere with it.

### Reflection So Far

1. This time, I didn't really do much in terms of learning and making some large changes to my code but that's quite alright. Instead, I got an MIT license for my source code, learned about knowing how to use GUIs (mainly tkinter), and knowing what to do with the user interface so nothing really special to think about but I finllty learned about tkinter I guess.

``` 
# This program is for my facial detection files and code.
# This is a hard project but fun to do.

# On stands for if the mask is on
# Off stands for if the mask is off
# Incorrect means that they're wearing the mask wrong
# I hope that all the things are randomized and not set

pic_one  = "On"
pic_two = "Incorrect"
pic_three = "Off"
pic_four = "Incorrect"
pic_five = "On"
pic_six = "Off"
pic_seven = "Incorrect"
pic_eight = "Incorrect"
pic_nine = "Off"
pic_ten = "On"
pic_eleven = "On"
pic_twelve = "Incorrect"

# This is supposed to randomise what picture it chooses every time it runs
# Use tkinter for user interface
# Make sure to have something as simple as buttons to change interface
# Buttons add a layer of complexity for the code

import random
vars = [pic_one,pic_two,pic_three,pic_four,pic_five,pic_six,pic_seven,pic_eight,pic_nine,pic_ten,pic_eleven,pic_twelve]
print (random.sample(vars, 1))

# This if function is to decide the next course of action once an anser is found

"""
if random_pic() == "On":
    print("Thank you for wearing your mask!")
elif random_pic() == "Off":
    print("Please wear your mask while you're in a public area.")
elif random_pic() == "Incorrect":
    print("Please wear your mask correctly")
"""
```
2. Link to Video:

https://watch.screencastify.com/v/fyMc8CJuC9qniFTfAwev

---

# Deliverable 4/5: Building my Project

For this part of the assignment, I was told to show my project build from the 12th to the 26th of October. I'm happy to say that I actually built and made good commits and stuff to my project! I was able to divise and make my own random answer generator for my code which was a huge stepping stone as to what my knowledge of python equates to as well as building the project itself. The only thing I need to now is get feedback but I believe the best feedback is from Mr. Bowman himself so why not ask him? From then on, as long as I have faith as to what I'm doing and keep trying, I'll burnout a lot later than before as long as I have the motivation for it.

### Reflection So Far

1. The learning I've acquired so far is frankly, a terrifying amount... To be honest, I was beating myself up a bit with this project because I told myself I was procrastinating and not getting any work done and "I'm useless" but I didn't let that get to me. This piece of code below is a random answer generator so it takes all the variable in the area and gives a random output of sorts. I'll explain more in the video:

``` 
# This program is for my facial detection files and code.
# This is a hard project but fun to do.

# On stands for if the mask is on
# Off stands for if the mask is off
# Incorrect means that they're wearing the mask wrong
# I hope that all the things are randomized and not set

pic_one  = "On"
pic_two = "Incorrect"
pic_three = "Off"
pic_four = "Incorrect"
pic_five = "On"
pic_six = "Off"
pic_seven = "Incorrect"
pic_eight = "Incorrect"
pic_nine = "Off"
pic_ten = "On"
pic_eleven = "On"
pic_twelve = "Incorrect"

# This is supposed to randomise what picture it chooses every time it runs

import random
vars = [pic_one,pic_two,pic_three,pic_four,pic_five,pic_six,pic_seven,pic_eight,pic_nine,pic_ten,pic_eleven,pic_twelve]
print (random.sample(vars, 1))

# This if function is to decide the next course of action once an anser is found

"""
if random_pic() == "On":
    print("Thank you for wearing your mask!")
elif random_pic() == "Off":
    print("Please wear your mask while you're in a public area.")
elif random_pic() == "Incorrect":
    print("Please wear your mask correctly")
"""
```
2. Link to Video:

https://watch.screencastify.com/v/60iOyW50r4Ty7cPbTaRR

---

# Deliverible 3: Project Foundation

For this assignment, I'm told to show what I have learned so far as new learning since the 26th of September all the way 'till the 12th of October which I'm proud to say that I came accross to finally working on it! I was given a grant and a recommendation to start working on this using CodeHS with 12 or more units that can help although I was told to work on units 3-7. On the very first week of the actual grant, I was able to make it a good way through Unit 3 but feel like I can definitely do more. Here's why:

### Reflection So Far
1. Originally, I had an entire table of different dates with different goals but I changed them up completely for the sake of becoming more specific with project and being able to be more clear with it all and to have better set goals for myself to better understand what direction I am and should be going in for this big project in the first place. As opposed to the other 2 deliverables, I actually went on and started doing some more work and went a good way through the units of CodeHS. Although there are some things I want to improve:
- I want to be able to work more on my CodeHS practice daily and get through units quickly before I can get to my final project, more realistically, I want to get through unit 5 by the end of November.
- I want to start learning how to make the API and the code communicate to each other to make the project successful in most places.
- I want to set a schedule for me to be able to learn code at a good level every day and retain that information for later.
- Finally put in some code for the Repo so that Mr. Bowman can know where I am on track.

2. I'd like to think that I met my goal after some adjustments to a certain degree. To explain, yes I did start a python course so I'm trying to go through and understand the units but hopefully not at a snail's pace so I have come and finally set a schedule for myself to learn CodeHS and the rest will be history from here on out. Here are some things I'm looking to do for the highest chance of the project's success:
- Take certain precautions in order to not distract myself.
- Work daily for at least 45 minutes
- Never hesitate to ask questions
- Have a lot of fun while working!

3.  I believe that, to stay on schedule, I have to get some help from Mr. Bowman as well as help from the other Computer Coding 2 students, start researching more about my project and learn some programming for the language that I decided to use at home for at least 45 minutes a day and maybe more during the weekend, and finally, make all the adjustments necessary to fix up my plan and change it up along the way just in case. I had also thought about asking outside sources for help on a public forum and getting well thought-out answers will drive me to become more motivated and responsible. I have changed my entire calender to be able to move at the same pace as it while also getting everything done on time.

4.  Here's what I did for the learning:

https://watch.screencastify.com/v/6DWQ1J2wUiZarW7XQTR7

---

# Deliverible 2: New Learning

For ths assignment, I'm told to show what I have learned so far as "new" learning since September 12th all the way 'till the 26th of September. Frankly though, I don't feel like I've learned a lot but I think not learning helps me learn more. Let me explain:

### Reflection So Far
1. My second goal for this specific deliverable is to show any kind of new learning up until the 26th from the 12th of September. However, there was a small problem. Along with the API, it took me a long time to find a free course for Python. As it may seem, there were many Python courses but they were either behind paywalls or didn't have the units I needed so in short, I did not meet my goal this time though I hope to do so later. My learning plan is very vague so I decided to take the previous feedback and reformat the timeline with more specific examples and goals. This is the feedback that I got in between the 12th and 26th:
- Start exploring more options and researching different websites and courses then compile them and decide.
- Compare and contrast the sites on different units of learning and such.
- Use certain sources and comments to tell the legitimacy of a website.

2. I'd like to think that even if I was nowhere near my initial goal achievement, I learned a lot. It's true that this may sound like I'm contradicting myself but hear me out. Through the time I've been in this class, I've noticed that I procrastinate a lot and make excuses but I feel like I finally learned my lesson to certain extents. Not learning and realizing my mishaps and failures made me learn even more than ever because of my inaction. My goal wasn't met but I learned a lot about how I both function and work at certain times and began to adapt myself to this new change I'm seeing. Here's how:
- I started taking notes about different things that distracted me.
- Made a schedule on the times that I predict I can and can't work from distractions or not being able to sit in one place for too long.
- Take certain precautions in order to not distract myself.
- Limit free time I have as 5 minutes between 30 minutes of work.
- Don't take anything too seriously as it would act as extra work for me in the long run.
- Have a lot of fun while working!

3.  I believe that, to stay on schedule, I have to get some help from Mr. Bowman as well as help from the other Computer Coding 2 students, start researching more about my project and learn some programming for the language that I decided to use at home for at least 45 minutes a day and maybe more during the weekend, and finally, make all the adjustments necessary to fix up my plan and change it up along the way just in case. I had also thought about asking outside sources for help on a public forum and getting well thought-out answers will drive me to become more motivated and responsible.

4.  What I did for new learning is learned more about myself and how I finish tasks at certain intervals along with how I pace myself. Later on, I'd like to talk to Mr. Bowman about learning and Python course options if they ever arise soon. Since I learned how to fix up my schedule, I can surmise that I can start getting to work as soon as possible, after reading up on some facts, I would be way more productive if I work 30-35 minutes then take breas at different 5 minute intervals after the productive time, I will be able to get a lot done.

---

# Deliverible 1: Repo

For ths assignment, I'm told to show what I had worked on since the first day in class as a deliverable to present. I called this file "Deliverable One" but I'm not sure if we will use this same file for the other deliverables that we are tasked with. This is what I have so far.

### Reflection So Far
1. My first goal for the deliverable was that I wanted to show my initial knowledge of the programming language that I will most likely use for my programming project. At first, Mr. Bowman thought it was vague which, when brought up to me, concured with after I was given an example of what I should do better and was given this feedback:
- Be more specific on which language I want to learn while doing the project.
- Instead of jumping straight to languages and learning programming, I should do some research on the face recognition API.
- Don't just think about languages but instead, also think of deadlines and if I will have time to learn the language.
- Make my project a bit smaller and better to view as something that isn't so complicated and outlandish so it doesn't take more time than the semester I signed up for.
- Finish one thing THEN think about the other without overthinking ideas or underestimating their difficulty.
- Have fun with it!

2. I'd like to think that even if I was nowhere near my initial goal achievement, I still got amazing feedback. The reason I wasn't able to achieve my goal was because it was too general and didn't make too much sense after reading it out loud and thinking about it. From the feedback above, I would like to improve and work on all of these before the next deliverable by makinga plan and getting some more criticism from peers so I can finally organize myself well enough.

3.  I believe that, to stay on schedule, I have to get some help from Mr. Bowman as well as help from the other Computer Coding 2 students, start researching more about my project and learn some programming for the language that I decided to use at home for at least 45 minutes a day and maybe more during the weekend, and finally, make all the adjustments necessary to fix up my plan and change it up along the way just in case.

4.   Here are some websites that I found to help me out with my research:

- [RapidAPI](https://rapidapi.com/cloudpronouncer/api/face-mask-detection-api-maskerizer) 
- [Microsoft](https://appsource.microsoft.com/en-us/product/web-apps/devissoftware.maskerizer)
- [Github](https://sheldonsebastian.github.io/face_mask_detector/)
- [INVIXIUM](https://www.invixium.com/face-recognition-mask-detection-system/)
