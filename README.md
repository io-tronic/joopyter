# JOOPYTER
Design Files for the Joopyter Personal Terminal

This project was envisioned when I found a [mini thermal printer](https://www.adafruit.com/product/597) sitting in one of the parts piles in my local makerspace. Apparently some particularly persnickety person demanded receipts for their 3d printer usage and then promptly left and nobody bothered to implement anything with the receipt printers that they had bought. Me, the Io of ***Io Mechatronics***, being fascinated with disused and interesting things, tried to implement the receipt printer for an upcoming art project. Seeing the printer hooked up to a Raspberry Pi got me all inspired and after a long break and some hard thinking, I went to implement those inspirations.

---------

## Advertisments

Went for something a little more solarpunk than cyberpunk :)

![image](https://github.com/gian-tronic/joopyter/blob/main/PortableMusic.png?raw=true)

![image](https://github.com/gian-tronic/joopyter/blob/main/EcoFriendly.png?raw=true)

-----------

## Parts

  - Raspberry Pi Zero W (a Zero 2 W is on its way)
  - 2.8in piTFT display from Adafruit (out of stock now, but similar is available)
  - A2 Micro Panel Thermal Printer
  - 2x Random male USB cables
  - Various JST connectors
  - Anker PowerCore 15600 battery
  - HARDWARE:
    - 10" x 5/16 Aluminum Rod (x2)
    - 1/4-20 x 3.25 Socket-Head Screws
    - A bag of tiny thread-forming 2.5mm screws
    - 3mm cap-head screws x4
    - 3mm socket-head screws x4
    - 2.5mm flat-head screws x4
    - #4-32 x 1" screws x2



## Process

#### Step 1: Design

Made mockups of all the parts in cad, arranged them, put a case around them, super ez....

![image](https://github.com/gian-tronic/joopyter/blob/main/img/cad.jpg?raw=true)

The hinge design is from [Yarh.io](https://yarh.io/). The design files are not currently released, and were only given to me as binaries, so I'm not going to post my modified version here without Mx.Yarh.io's permission. The keeb design is also loosely based on another design from Yarh.io, but very heavily modified.


#### Step 2: Printing

(forgot to take a picture on the bed)

![image](https://github.com/gian-tronic/joopyter/blob/main/img/print.jpg?raw=true)

Everything Fits!

![image](https://github.com/gian-tronic/joopyter/blob/main/img/everythingfits.jpg?raw=true)

#### Step 4: Electronics (round 1)

At this point, I wanted to get the electronics worked out to see if my plans were actually going to work.

![image](https://github.com/gian-tronic/joopyter/blob/main/img/electronics1.jpg?raw=true)

Chopped and required a ribbon cable in the middle. Serial and power for the printer connect here, as well as the battery. Simple rails. Would have been better with strip-board instead of cheapo perf-board.

![image](https://github.com/gian-tronic/joopyter/blob/main/img/electronics2.jpg?raw=true)

Wired both outputs from the battery together to get the current (did not know this was a bad idea at the time)

#### Step 4: Keeb

I do like me some handwired Keebs, and I do like me some Circuitpython KMK

![image](https://github.com/gian-tronic/joopyter/blob/main/img/keeb1.jpg?raw=true)

So satisfying.

![image](https://github.com/gian-tronic/joopyter/blob/main/img/keeb2.jpg?raw=true)

Finished Keeb (I returned these keycaps later cuz they sucked)

![image](https://github.com/gian-tronic/joopyter/blob/main/img/keeb3.jpg?raw=true)

#### Step 5: Hinge

I did not take a lot of pictures of the hinge cuz it really sucked to put together. I made about 4 different iterations of the hinge before I settled on something with the right ID and wall thickness. I should have just printed it at 100% from the get-go.

![image](https://github.com/gian-tronic/joopyter/blob/main/img/hinge.jpg?raw=true)

#### Step 6: Assembly

Kind of a mess inside, but hopefully heatshrink and electrical tape will keep everything from shorting out. The Printer is fixed in with some clamp-y T-shaped thingies and a bunch of hot glue. I could have designed that better.

![image](https://github.com/gian-tronic/joopyter/blob/main/img/assembly.jpg?raw=true)

#### Step 7: Keyboard Broke 😢

![image](https://github.com/gian-tronic/joopyter/blob/main/img/keyboardbroke.jpg?raw=true)

The pi pico randomly stopped working. It was intermittent at first, but now its flash isn't recognized by the computer, and it isn't sending any input when keys are pressed. When I plugged it into my other computer and open dmesg, it gives me this error:

![image](https://github.com/gian-tronic/joopyter/blob/main/img/errormsg.jpg?raw=true)

I didn't have a lot of time to troubleshoot it because I was flying out for spring break the morning after it broke. Had to swap it out and threw in a capacitor to smooth out any current spikes. Hope that holds...

-----------

## Final Product

I'm really happy with the way this came out! It's super clean, super portable, and super *Aesthetic*.

![image](https://github.com/gian-tronic/joopyter/blob/main/img/finished.jpg?raw=true)

The thing is really rugged, I've been carrying this around school and around town, stuffed it in my luggage. Very happy.

![image](https://github.com/gian-tronic/joopyter/blob/main/img/finishedlunchbox.jpg?raw=true)

Some extra images from the advertisement photoshoot
![image](https://github.com/gian-tronic/joopyter/blob/main/img/photoshoot%20extras/jamming.jpg?raw=true)
![image](https://github.com/gian-tronic/joopyter/blob/main/img/photoshoot%20extras/flamingo.jpg?raw=true)
![image](https://github.com/gian-tronic/joopyter/blob/main/img/photoshoot%20extras/frustrated.jpg?raw=true)
![image](https://github.com/gian-tronic/joopyter/blob/main/img/photoshoot%20extras/jamming2.jpg?raw=true)


---------

![image](https://github.com/gian-tronic/joopyter/blob/main/img/IO.png?raw=true)


