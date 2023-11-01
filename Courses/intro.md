# Introduction to Programming with Scratch

### Intro
Welcome to 8-Bit University's, "Introduction to Programming with Scratch". We're excited to get you started.
This course is meant to be hands-on and will get you familiar with basic programming and computational thinking skills while making games.
Each project you accomplish will be shared with the community for feedback and testing. These experiences will further improve your problem-solving skills and logical thinking.

**Keep in mind the following:**
- Allow yourself to make mistakes and learn from them
- There’s no “one” correct solution for anything
- If you come across a problem, try to figure out how to solve it yourself
- If you really can’t solve it, try asking for help

### Navigation
1. [Lesson 1 -  Into to Scratch](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#lesson-1---into-to-scratch)
- Understanding the GUI
- Understanding game aesthetics 
- Assignment - Create a story game

2. [Lesson 2 - Programming basics](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#lesson-2---programming-basics)
- Understanding inputs, events and outputs
- Basic blocks (forever, if, wait, variables, etc)
- Learning about game mechanics and pseudocode
- Assignment 1 - Clicker game
- Assignment 2 - Chaser game

3. [Lesson 3 - Computational Thinking](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#lesson-3---computational-thinking)
- Abstraction, Pattern recognition, etc
- Understanding flowcharts
- Assignment - Drawing app

4. Lesson 4 - Pong
- Learning how to make pong
- Learning about multi-threaded programming

5. Lesson 5 - Pong+
- Make pong 2 player
- Learn about functions and broadcasting

6. Lesson 6 - Project
- Learn about the project lifecycle
- Collect feedback
- Presentation

## Lesson 1 - Into to Scratch

**Navigation**
- [Create an account](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#create-an-account)
- [Stage area](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#stage-area)
- [Coordinates](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#coordinates)
- [Sprite info](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#sprite-info)
- [Assignment - Create a story animation](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#assignment---create-a-story-animation)

We’re going to take a look at Scratch and use it to learn about programming
Why Scratch? Isn’t it for Kids?
- It's suitable for all ages and backgrounds
- Scratch is quite powerful with a huge community, shoutout to [Griffpatch](https://www.youtube.com/@griffpatch)!
- It’s easy to learn and user-friendly
- It has a block-based interface, where you can drag and drop blocks for programming

### Create an account

- Navigate to [Scratch](https://scratch.mit.edu/)
- Click the “Join Scratch” button to sign up

![join](https://i.imgur.com/BJ9hJVI.jpg)

- Once you've logged in, click on "Create".

![create](https://i.imgur.com/NxWyM2z.png)

- You will see the GUI.

![Scratch GUI](https://i.imgur.com/flJSnWv.png)

### Stage area

Let's take a moment to understand what's going on

![Scratch areas](https://i.imgur.com/pR7ZUht.jpg)

**Blocks menu**
- Click on any colored circle in the blocks menu
- This is a shortcut that will take you to what you're looking for

**Blocks list**
- This is where you can find the blocks of code

**Script area**
- This is where you can drag the blocks to combine them

**Start/Stop**
- This is how you can start and stop your program

**Stage**
- This is how the program will look like to users
- There is a maximize button that you can use if it's too small
- The cat in the middle of the stage is Scratch

**Sprite zones**
- This will be where all your sprites are shown

### Coordinates
- Click the button on the bottom right.
- if you hover over it, it will show "Choose a backdrop"

![backdrop](https://i.imgur.com/pHeggnl.jpg)

- Scroll all the way to the bottom and choose the "Xy-grid"

![xygrid](https://i.imgur.com/TwjkdU5.png)

- You will see the XY grid backdrop under Scratch.

![coords](https://i.imgur.com/L74obwR.jpg)

- This is how you'll know where Scratch is moving

### Sprite info

Let's take a look at the area below the stage

![sprite info](https://i.imgur.com/usGTEd6.jpg)

- You'll notice that Scratch is currently labeled as "Sprite1"
- Scratch is currently located at: x is 0 and y is 0
- You can also see the size and direction
- Try moving scratch around to see what's reflected in this area

### Assignment - Create a story animation

Choose the following
- 2 sprites
- A background
- A sound effect

What to do
- Get the sprites to interact with each other
- The sprites can move or change size

You can take a look at the tutorial, [Create a story](https://scratch.mit.edu/story)

![create a story](https://i.imgur.com/E5LkuVI.jpg)

## Lesson 2 - Programming basics
**Navigation**
- [Forever](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#forever)
- [Repeat n](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#repeat-n)
- [Wait](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#wait)
- [If](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#if)
- [Variables](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#variables)
- [Assignment 1 - Clicker game](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#assignment-1---clicker-game)
- [Assignment 2 - Clicker game](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#assignment-2---chaser-game)

### Forever

Let’s consider this statement. Let’s say you’re waiting for your bus, we'll call it 123

**Forever keep checking for my bus to arrive**

1. You wait at the bus stop
2. You check what bus has arrived
3. You see that it’s not your bus
4. Return to step 1

How many times do you think you’ll need to go through this loop?
You don’t know how many buses will come until your bus does. So you need to keep checking each time until your bus comes then you can board it.

- Here is one way we can represent this on scratch

![forever](https://i.imgur.com/pZXqYzR.jpg)

### Repeat n
Instead of repeating something forever, you can repeat something a number a certain number of times.
Let’s say you’re waiting in line to collect your food.

**There are 3 people ahead of you in a queue**

1. You wait for person one to collect their food
2. You wait for person two to collect their food
3. You wait for person three to collect their food
4. You can finally collect your food

You can clearly see 3 people ahead of you which makes it easy

![repeat n](https://i.imgur.com/DMed52g.jpg)

### Wait
Programming happens very fast.
- The previous program ran 3 times, we just didn’t have a chance to see it
- Let’s give us some time to read
- By giving time, we can add the Wait block

![wait](https://i.imgur.com/Nkb5P1R.jpg)

### If
Let’s consider this statement:

![if](https://i.imgur.com/QHKRRuQ.jpg)

**If no apple (blue), say I’m hungry (red)**

**Else, say Yum (red)**

Blue is the condition, Red is the action.
- What’s missing from the above?
- Scratch might not be hungry

![if in scratch](https://i.imgur.com/SZ4033r.jpg)

### Variables
You can think of a variable like a cardboard box.
- This box can store information (word, number)
- It can only store one piece of info at a time
- Consider if you want this variable to change or stay the same
- It is good practice to give your variable a meaningful name

![variables](https://i.imgur.com/4jebr48.jpg)

Take a look at the image below, what’s the difference between these two blocks?
- Set would be the default number of the variable
- Change would be the number you want to change the variable to
- You can change this number a lot of times, for example
- You can increase the health of a player to 3

![set and change](https://i.imgur.com/bjvaa98.jpg)

### Assignment 1 - Clicker game
Let’s make a clicker game.
- Choose a sprite
- Choose a background
- Add a sound effect when sprite is clicked
- Add a score to keep track of the clicks
- How can you make the game more exciting?

You can take a look at the tutorial, [Make a clicker Game](https://scratch.mit.edu/clicker)

![clicker game](https://i.imgur.com/JXPxvdo.jpg)

### Assignment 2 - Chaser game
Let’s make a chaser game.
- Choose 2 sprites
- Choose a background
- Create a score
- Move one sprite
- Enhance game!

You can take a look at the tutorial, [Make a chase Game](https://scratch.mit.edu/chase)

![chaser game](https://i.imgur.com/uDU38wr.jpg)

## Lesson 3 - Computational Thinking
- Problem-solving approach inspired by computer science
- Involves breaking down complex problems
- Identifies patterns and recurring elements
- Designs step-by-step solutions
- Promotes systematic, logical, and organized thinking
- Enhances problem-solving efficiency in various domains

**Navigation**
- [Abstraction](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#abstraction)
- [Decomposition](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#decomposition)
- [Pattern Recognition](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#pattern-recognition)
- [Algorithmic thinking](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#algorithmic-thinking)
- [Pseudocode](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#pseudocode)
- [Assignment 1 - Give examples of these tools IRL](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#assignment-1---give-examples-of-these-tools-irl)
- [Assignment 2 - Drawing app](https://github.com/8bituniversity/8bituni/blob/main/Courses/intro.md#assignment-2---drawing-app)


### Abstraction
Using emoji is one example
- A heart emoji to represent love, affection, or appreciation without needing to show an actual heart
- A thumbs-up emoji as a symbol of approval or agreement without needing to explain why you approve of something
- A crying emoji to express sadness or disappointment without necessarily expressing sad feelings
- Abstraction allows you to zoom in and focus on the necessary details

### Decomposition
Let’s break down a complex problem, like planning a trip, into smaller tasks
- Decide where you want to go
- Plan how you'll get there? Car, plane, train, etc
- Booking accommodations
- List the things you want to do and see at the destination
- Set a budget for the trip
The key is to break down the problem into smaller, more manageable components so you can do either of these tasks in any order

### Pattern Recognition
We can find patterns in the weather
- Are there certain times of year when it's more likely to rain?
- When is it hot season?
- Are there certain times when rain is more likely to happen? For example, it might tend to rain at night and get very hot in the midday
By looking for patterns in the weather, you can start to see if there's a regularity when it rains, which can help you plan accordingly (and maybe pack an umbrella more often!)

### Algorithmic thinking
It’s all about breaking down a complex problem into smaller steps, like making a peanut butter sandwich!
1. Grab some bread, peanut butter and butter knife
2. Open the jar of the peanut butter
3. Dip the butter knife into the peanut butter
4. Spread the peanut butter on the bread
And now we’ve got ourselves a peanut butter sandwich!

Here's a hilarious video on [Exact Instructions](https://www.youtube.com/watch?v=Ct-lOOUqmyY) (You can stop at 1:06)

### Pseudocode
- Pseudocode is an important part of algorithmic thinking 
- It is something you can do before you write down actual code
- That way you can translate it from human language to a programming language for the computer
- The previous sandwich example is one way you can approach this but pseudocode suggests simplifying it further
- Learning to write in pseudocode can help you in the future if you’re faced with bugs
- Here’s an example of how we can use pseudocode

```
While true, grab:
	Bread
	peanut butter jar
	butter knife
If knife has peanut butter = True:
	Spread peanut butter on bread
Else:
	Open peanut butter jar
	Dip butter knife in jar
	Knife has peanut butter = True
```

### Assignment 1 - Give examples of these tools IRL
- Now it’s your turn!
- Let’s go back and take a look at the tools
- What examples can you give?
- Try to give a real-life example for each of the tools we've mentioned above

### Assignment 2 - Drawing app
Let’s say we were to make a drawing app. The feature of the drawing app is this:

**When the mouse is clicked, we can draw something (black and white)**

How would you implement this drawing app? Write the psuedocode and explain the steps in simple English.
- What are the things we need?
- How we can make the drawing app?

Here are the things we need:
- A pen/pencil to draw
- A canvas
- A way to erase the drawing

How we can create a drawing app?
- Recognise when the mouse is clicked
- When we click the mouse, we will start to draw
- When we stop clicking, we will stop to draw

Hints!
- You'll need to add an extension "Pen" for this to work. Navigate to extensions at the bottom right

![Extension](https://i.imgur.com/Bcurmmv.jpg)

- Click on "Pen"

![pen](https://i.imgur.com/hCiMRNP.jpg)

- Click on the costume of your pen/pencil sprite to edit it

![costume](https://i.imgur.com/mtjnjsO.png)

- Drag the area of your pen/pencil sprite to move it

![drag](https://i.imgur.com/vwKnejc.png)

- You'll need to move the tip of your pen/pencil sprite to the "crosshair"

![crosshair](https://i.imgur.com/ZJWVmQG.png)

- You can try this code if you're stuck

![drawing app](https://i.imgur.com/FAS9c69.jpg)

- Try to see how you can improve on this drawing app
