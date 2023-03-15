# Jasleen Chahal
A Graduate student pursuing MS in Data Science from the University of Michigan (graduating in April 2023) with three years of experience in Software Development and looking forward to full-time job opportunities in the field of Data Science, Front-end or Full-stack Development.

# Educational History
MS in Data Science, University of Michigan (GPA: 3.87)          Sept 2021 - Apr. 2023
BE in Computer Science, Chikara University (GPA: 3.87)      	July 2016 - July 2020


# Experience

## 1. Magna International Inc. (Auburn Hills, MI), Software Engineering Intern   Sep 2022-Present
•	Developing Object-oriented software for multi-core embedded systems (ADAS)
•       Supporting testing, verification, and integration for embedded hardware systems.
•      Developing  automated analysis/reporting methods using Python/MATLAB scripting/Batch.
•      Debugging, DDR testing, MIPI Analysis and verification of ECU using CANalyzer tool.
•      Flashing the latest software on ECU using Lauterbach, vFlash and Vector CAN Box.
•      Updating code on Jenkins, Gitlab and PTC.

## 2. BlueStamp Engineering (Palo Alto, Remote), Engineering Instructor             June 2022 - Aug 2022
•      Developed Microcontrollers and Python programming projects.
•      Circuit design, Firmware development and IoT project development.
•      Mentored six classes of students to complete their engineering prototypes.
•      Taught design process, debugging, troubleshooting and proper tool use to students.
•      Led project development presentations and engineering documentation.

## 3.   Graduate Student     
        Master’s in Data Science (UofM), 
        (Sep 2021 - Present)
                •      Built Sales Marketing Prediction Project using regression analysis, clustering, classification.
                •      Developing Big Data,Deep Learning, AI, Data security/Privacy, MOR & Google Cloud projects.

## 4. GeekyAnts Pvt Ltd, Software Developer 
(June 2020 - Aug 2021)
•      Developed mobile applications using React Native and Flutter.
•      Led the technical presentations of the project with clients. 
•      Designed UI, API integration, and State management for application development.
•      Performed Unit testing for applications.

## 5. GeekyAnts Pvt Ltd, Software Developer Intern                                             Mar 2019 - May 2020
•      Developed several client projects like Taxi App, Music, Food Delivery Apps.
•      Coded for React, Flutter, React Native projects.
•      Developed apps using Redux, GraphQL, MobX, MobX state tree, Firebase, AWS
•      Led project management through GitLab, Github, JiraBoard and client meetings.


# Project Experience

1. Visual Abductive Reasoning | (Current) 
        A data science project for Deep Learning based on Computer Vision and Pattern Recognition. 
        Spatio-Temporal Trajectory Similarity Learning in Road Networks (Current)  - Implementation of data Mining project using Machine learning model.
2. MCE and ECE MIAShield implementation on Location-30 dataset (Dec 2022): 
        Implementing MIAShield against MIA
3. Dating App | (April 2022) – 
        A react native app for finding people around the campus. The app uses google cloud services from Google Cloud like storage, App Engine, Google Cloud                 functions, BigTable and firebase.
4. Sales Market Prediction Project I (December 2021)
        A project for predicting sales of a supermarket using Big Data analytics & Visualization, python, regression, clustering, and classification.
5. Music App | (May 2021)
        React native app for showing music tracks as carousels and log-in flows. This app  contains features like in-app purchases, selecting tracks, profile,               settings, log-in, and sign-up flow. This app also uses Zustand and AWS for the backend.
6. Restaurant App | (March 2021)
        React Native app UI for a Restaurant chain having features like selecting from the menu,adding in the cart, and order booking flow.
7. Banking App | (July 2020) 
        A React Native app for all banking problems, making investments, and following upon the savings. This app also uses Kotlin.
8. Taxi App | (Jan 2020) 
        An app for booking taxis along with features of Instagram like adding posts and searching for people to follow. This app was built using React Native.
9. An app for following celebrities and posting about their life events I (Sep 2019) 
        A Mobile app using React-Native and Mobx State Tree for state management. The app is based on the interaction of Fans with Stars through Live Streaming and           uses Firebase and Rest-API calls.
10. App for watching wrestling matches and to follow athletes | (May 2019)
        A React-Native app using Redux Thunk for state management. The app uses Firebase and API calls.
11. Instagram Clone I (March 2019)
        Instagram clone app using React Native with MobX.
12. PG-Finder I (January 2019)
        A website for finding accommodation in a region. A user can book the accommodation and edit various options while choosing one. Technologies used - Node,             MongoDB, EIS, HTML, and JS.
13. Book Tracking App I (December 2018)
        A book tracking app using ReactJS where a user can search a book   as well as place it on one of the shelves - currently reading, wish to read, and finished         reading. Technology used - ReactJS.
14. Snake Game | (September 2018)
        Developed using arrays in C++ and Data Structures. The snake’s size increases as it consumes food and game ends when it forms any closed loop.
15. Maze Game I (March 2018) - C++ and Data Structures project
16. Arduino Based Walkie Talkie Coding | (April 2016) 
        Arduino-based Walkie Talkie and Intercom for inter- communication during university events covering a range of about 10 m, as a cheaper                               alternative for original Walkie Talkies.
17. Website-Top Universities Around the Globe | (June 2016)
        A website designed using HTML, CSS, and JavaScript depicting the best universities in the world.


<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/K3BvrV7_TUk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/3oQrefB0k7c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

```
def __init__(self):
        # Initialise our Bot with our access token, prefix and a list of channels to join on boot...
        super().__init__(token='oauth:a47vhfexb2e2roryfpoh01c51iax0o', prefix='!', initial_channels=['hypercoolness30'])
        s = sched.scheduler(time.time, time.sleep)
        def likeSub(sc): 
            print("Remember to drop a sub and like!")
            sc.enter(2, 1, likeSub, (sc,))

        s.enter(2, 1, likeSub, (s,))
        s.run() 
        self.msg()
```

```
from twitchio.ext import commands
import random
import sched, time


class Bot(commands.Bot):
    def __init__(self):
        # Initialise our Bot with our access token, prefix and a list of channels to join on boot...
        super().__init__(token='oauth:a47vhfexb2e2roryfpoh01c51iax0o', prefix='!', initial_channels=['hypercoolness30'])
        s = sched.scheduler(time.time, time.sleep)
        def likeSub(sc): 
            print("Remember to drop a sub and like!")
            sc.enter(2, 1, likeSub, (sc,))

        s.enter(2, 1, likeSub, (s,))
        s.run() 
        self.msg()
            

    async def event_ready(self):
        # We are logged in and ready to chat and use commands...
        print(f'Logged in as | {self.nick}')
        print(f'User id is | {self.user_id}')
    async def event_message(self, message):
            # Messages with echo set to True are messages sent by the bot...
            # For now we just want to ignore them...
            if message.echo:
                return

            # Print the contents of our message to console...
            print(message.content)

            # Since we have commands and are overriding the default `event_message`
            # We must let the bot know we want to handle and invoke our commands...
            await self.handle_commands(message)

    @commands.command()
    async def hello(self, ctx: commands.Context):
        # Send a hello back!
        await ctx.send(f'Hello {ctx.author.name}!')
    @commands.command()
    async def randomNum(self, ctx: commands.Context):
        num = random.randint(0, 10)
        print(num)
        #send a random number between 1-10
        await ctx.send(f'random #: {num}!')
        
    @commands.command()
    async def msg(self, ctx: commands.Context):
        print("222")
        await ctx.send(f'222')
        
        #ctx.send(f'Remember to drop a sub and like!')
            # do your stuff
        #sc.enter(2, 1, likeSub, (sc,))

    #s.enter(2, 1, likeSub, (s,))
    #s.run()

bot = Bot()
bot.run()

```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Firstname Lastname | Current Highschool | Electrical Engineering | Incoming Senior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)

![AURDINO Image](https://m.media-amazon.com/images/I/71z22cRPeeL._AC_SL1000_.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint.

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  

My first milestone was setting up and hooking up the Raspberry Pi and all the necessary components onto my tv. The heatsinks, the sd card, and the controller were all added to ensure that the Raspberry Pi was working. Instead of the Raspberry Pi Os software, I had to first download a different software called Retro Pie. With Retro Pie, I needed to download an Imager for Raspberry Pi. Raspberry Pi Imager automatically downloads a list of the latest versions of Raspbian supported by the Raspberry Pi. Raspbian is the typical Raspberry Pi Os software, the one I needed on the Raspberry Pi was Retro Pi. With the included SD card, I plugged in the SD into my computer and launched the Imager. The imager allowed me to set the Operating System to Retro Pi instead of Raspbian onto the SD card. With the OS imaged onto the SD, I plugged the SD card back into the Raspberry Pi and rebooted the system and Retro Bi booted up.

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |


```
# include<stdio.h>
```

<a href="https://ibb.co/zGdwbRW"><img src="https://i.ibb.co/Pwk84hs/IMG-4680-1.jpg" alt="IMG-4680-1" border="0"></a><br /><a target='_blank' href='https://emoticoncentral.com/category/dansu'>dansu smileys</a><br />


