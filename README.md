# PiPod
"Upgrading" an Apple iPod Classic using Raspberry Pi internals

## Project Parameters
Improving this [Project](https://hackaday.com/2021/01/27/raspberry-pi-zero-powers-spotify-streaming-ipod/)

Use the Chassis and buttons from an iPod classic as a base.

While the purpose of the project is to bring dead iPods back to the land of the living; there exists custom chassis' and buttons on markets such as AliExpress or Ebay.

You will need these from either a dead iPod or from AliExpress:
- Faceplate
- Back Housing
- Scroll wheel
- Headphone jack
- Battery (Maybe)

### Why only the classic?
Every other iPod model is simply too compact to fit anything other than original hardware without significant R & D.

### What about screens?
While I would love to keep the original screen, I understand that this is about a 20 year old component at this point and may not be completely compatible with the pi sbc. Which is why I've begun looking into possible display replacements / upgrades. Displays using OLED or AMOLED technology would likely be the best option because of the low power draw.

It should be noted that the actual display size for the models are as follows:

- 1st + 2nd + 3rd + 4th
    - 2 inch 5:4 diplay
- 5th + 6th + "7th"
    - 2.5 inch 4:3 display

And thus potential upgrades are as follows:

- 1st + 2nd + 3rd + 4th
    - 2 inch 5:4 diplay
- 5th + 6th + "7th"
    - [2.4 Inch AMOLED](https://www.aliexpress.us/item/3256806453669414.html?src=google&gatewayAdapt=glo2usa#nav-specification)
    - This will be slightly smaller than the view window, alternatives are appreciated.

### Which Pi?
There are a number of possibilities when it comes wo which pi should be used.
To narrow it down, first we need to consider the size limitation, which effectively eliminates every model A and B.
Leaving the possibilities to the Pi Zeros and compute modules.
One more point to consider is battery life.

The pi zero series has proven to use less power, is the smallest in the lineup, and has easily swapable storage. Making it our winner.

However, more recently, a smaller and relatively power efficient has surfaced: the Raspberry Pi CM4. Using the CM$ will allow potential usage of a thin chassis.