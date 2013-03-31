# B1nUrt Client

B1nUrt-Client v4.1.1 (ioquake3 svn 2306)

* This is a customized version of ioUrbanTerror forked from the (UrTDevs Client)[https://github.com/urtdevs/UrTDevs-Client]. Its goal is to combine a large set of useful and or required cvars/additions to ioQ3.

## Features and Improvements:
  
### Added cvars:
  - `com_nosplash [0|1]` enables/disables splash screen on client start (set this in your autoexec.cfg)
  - New Networking settings for better performance and more hits:
   * `*net_maxpackets [30-125]` (default 62) relates directly to frame rate if you get framerates BELOW, this value adjust it accordingly else if you get a consistent 90/125FPS you may increase it.
   * `*net_packetdup [0-3]` (default 1) setting it to 0 has been reported to improve things, but only if you have an extremely stable connection and ping less then 50ms
   * `*net_rate [25000-125000]` (Bits persecond) (default 125000) has no effect on bandwith usage, bandwith usage IS directly related to net_maxpackets and net_packetdup
  - Backported multiple script-addons from Segfault (custom tremulous build)
   * `if <variable1> <operator> <variable2> <variablethen> (<variableelse>)` Compares the first two variables and executes <variablethen> if true, <variableelse> if false
   * `strcmp <string1> <operator> <string22> <cmdthen> (<cmdelse>)` Compares the first two strings and executes <cmdthen> if true, <cmdelse> if false
   * `math` Multiple operators for cvars.
   * `concat <variableToSet> <variable1> <variable2>` Concatenates variable1 and variable2 and sets the result to variableToSet
   
### dmaHD
dmaHD greatly enhances sound quality and precision, and also adds doppler effect to moving entities and projectiles.

### Re: SoundHax
Yes they are in there. No you dont **have** to use them. I am not responsible for you getting your ass banned after using sound-hax in league play.

## Respect!
  - strata for his original work on the client
  - dmaHD: p5ych0runn3r of apd 
  