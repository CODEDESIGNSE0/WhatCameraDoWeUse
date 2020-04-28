# WhatCameraDoWeUse
**What cameras do we use?**


*Well*, a bunch, and they all have their positives and negatives.

There are many choices, it depends on how much you are willing to spend in hardware for support.

**Phone Camera** - Starting to be used more, as these cameras can actually look great! Under the correct lighting conditions..

  *Pros - Easiest, everyone has one.*
  
  *Cons - Need phone in a good place with good lighting, and something to hold it, audio is also not very good most of the time.*
  

**USB** -  We started here, simple usb webcams, and found our way to a pair of c920's and c920 Pro's.

  *Pros - Simple, plug and play, cheap, quick.*
  
  *Cons - USB Bandwidth can be exceeded causing issues, camera settings with Logitech had a retaining issue, dark and bright/high
 contrast can be an issue with visibility between colors in high exposure areas (pool ball colors on table).*
  
  **POE** - Power Over Ethernet.  These are great for a large number of cameras but are kind of hard to search for because everything comes sold as a security camera.
  
  *Pros - Data and Power over single ethernet wire. Already sending RTSP feed.*
  
  *Cons - a lot come with fisheye lens, all have a natural delay, and older cameras may have deprecated system configuration pages.*
    
    
  **HD/ SDI** - Our future. With an expensive camera you can send data over HDMI or SDI cable, but for that much data, we must talk about how this all works in the next chapter:
  
  
-----------

***hardware/software.***

-----------

**OBS** - Open Broadcast Software

Free and Open Source, OBS is our go to broadcast software.  With OBS you have a plethora of options, settings, plugins, and tutorials.  From options that can specify OBS to utilize your CPU or your GPU and how much of each, to scene switching and overlays.


For hardware you need power!  The better the cpu and/or gpu, the more you can do.  The more cameras you can process independently, the higher bitrate/quality you can stream, or perhaps if you are trying to stream and record at the same time.  Everything takes a little(sometimes a lot) more power.  By power I mean spend the extra 200 for the better cpu with more cores.  or maybe you think you can run it on an old spare laptop.. maybe one camera, at 720p, maybe more maybe less.  It's hard to tell from here.

You only have a phone?  Well you aren't working with much, but it can do a lot in the right situation.  I recommend getting a PC to stream with.  However, I am developing a web based streaming platform so people can easily versus others and everyone can watch.  

-----------

***Extras***

-----------

**SCOREBOARD??**

Looking into how to build a scoreboard?  Definitely something i'm working on with the phone stream, but there are MANY methods for importing a scoreboard into OBS.  The easiest is to find/edit/create a background with some gradients, borders, shadows, and fill in the text with a text object in OBS that you can edit on the fly.  My own method involves a flutter android app and python server communicating via websockets to display the scores automatically on a browser which is imported into my obs, so the scoreboard next to the table is live on the stream.

I am looking into the new raspberry pi and 2 usb cameras bundled up with a nice stream now button

Also building a website for 1v1 stream battles, shareable to facebook.

More to come!
