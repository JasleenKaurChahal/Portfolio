# Robot Arm
This will serve as a brief description of your project. Limit this to three sentences because it can become overly long at that point. This copy should draw the user in and make she/him want to read more.

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

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}

# Bill of Materials 

This is a table containing all the items needed for milestone one and the robotic arm. It contains the item, quantity, price, and where to buy the item.

| Item | Qty | Price | Where to Buy |
| ------------- | ------------- | ------------- | ------------- |
| Breadboard  | 1 |  $6.75  | https://www.amazon.com/BB400-Solderless-Plug-BreadBoard-tie-points/dp/B0040Z1ERO |
| Potentiometer  | 1 | $1.85  |  https://www.tubesandmore.com/products/potentiometer-alpha-linear-38-bushing  |
| Jumper Wires  | 6 | 10¢/wire  |  https://www.amazon.com/Breadboard-Jumper-Wire-75pcs-pack/dp/B0040DEI9M |
| Arduino Uno Board  | 1  | $27.60  | https://store-usa.arduino.cc/products/arduino-uno-rev3?selectedStore=us  |
| Arduino IDE  | 1  | $0  | https://www.arduino.cc/en/software/ |

<a href="https://ibb.co/zGdwbRW"><img src="https://i.ibb.co/Pwk84hs/IMG-4680-1.jpg" alt="IMG-4680-1" border="0"></a><br /><a target='_blank' href='https://emoticoncentral.com/category/dansu'>dansu smileys</a><br />

# Code for Processing

``` 
#inkjnljk
kjsdkjfdl
dnskhjdf
```

| Item | Qty | Price | Where to Buy |
| ------------- | ------------- | ------------- | ------------- |
| Breadboard  | 1 |  $6.75  | https://www.amazon.com/BB400-Solderless-Plug-BreadBoard-tie-points/dp/B0040Z1ERO |
| Jumper Wires  | 6 | 10¢/wire  |  https://www.amazon.com/Breadboard-Jumper-Wire-75pcs-pack/dp/B0040DEI9M |
| Arduino Uno Board  | 1  | $27.60  | https://store-usa.arduino.cc/products/arduino-uno-rev3?selectedStore=us  |
| Arduino IDE  | 1  | $0  | https://www.arduino.cc/en/software/ |
| LED | 5 | $3.05 |https://www.amazon.com/DiCUNO-450pcs-Colors-Emitting-Assorted/dp/B073QMYKDM/ref=sr_1_3?crid=6LJDAI89J5SQ&keywords=LED+kit&qid=1653586560&sprefix=led+kit%2Caps%2C175&sr=8-3 |
| UltraSonic | 1 | 3.95 | https://www.digikey.com/en/products/detail/adafruit-industries-llc/3942/9658069?utm_adgroup=Temperature%20Sensors%20-%20NTC%20Thermistors&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Sensors%2C%20Transducers_NEW&utm_term=&utm_content=Temperature%20Sensors%20-%20NTC%20Thermistors&gclid=Cj0KCQjw8uOWBhDXARIsAOxKJ2GRJr-YuEC5TYBnVz52mJ3fxJ0dQcGTH9WjiTcOlsTtiYiEeHZa5gUaAh4VEALw_wcB |
