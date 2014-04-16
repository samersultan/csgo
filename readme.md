# Counter Strike Global Offensive Custom Configuration #

### By Samer Sultan ###
[http://www.sultansolutions.com](http://www.sultansolutions.com)

[samer@sultansolutions.com](mailto:samer@sultansolutions.com)

[@sultansol](https://twitter.com/sultansol)




**Last Updated: 04 / 17 / 2014**

---

### Introduction ###

---

The following is my custom configuration for Counter Strike Global Offensive, having spent a considerable amount of time researching and compiling what I have found to be a solid foundation for a autoexec.  I typically update this configuration configuration weekly, so check back for the latest. 



View this autoexec as a good "frame work" and build upon it, feel free to tweak these settings to your liking, and be sure to contact me with any issues or bugs. 

The video.txt file is optimized for the highest fps performance and viability, feel free to modify it to your personal preferences. 

**Things you will need to change:**

* Adjust the senativty on line 291
* Select to enable or disable rawinput on line 293 



---

### Notes ###

---

**Rates:**

Rates are configured for 128 tick rate servers however will scale down for lower tick rate. 
<br />

**Raw Input and Mouse Acceleration:**

Based on my research and first-hand experience, the in game rawinput 'm_rawinput 0' has been disabled. You can read more about it [here](http://www.reddit.com/r/GlobalOffensive/comments/1f8km4/csgo_raw_input_faulty/), I recommend you set up the [The MarkC Windows 8 + 7 Mouse Acceleration Fix](http://donewmouseaccel.blogspot.com/2010/03/markc-windows-7-mouse-acceleration-fix.html) to get a true 1:1 pointer response. 

**Crosshair Customization:**

I have included my basic crosshair however you can replace it with your own. 



---

### Installation ###

---


<br />

<ol>
<li>The autoexec.cfg file will need to be uploaded to the following location on your local drive: 
<br />
'Program Files (x86)\Steam\SteamApps\common\Counter-Strike Global Offensive\csgo\cfg'
</li>

<br />
<li>Launch game and open the developer console by hitting the ~ button </li>
<br />
<li>Input the following command on game start up: exec autoexec </li>
<br />
<li>Restart game, make modifications to options and autoexec.cfg as you like. </li>
<br />
</ol>



---

### Support ###

---

Please forward all bugs, customization, ideas and support requests to the [issues](https://github.com/samersultan/csgo/issues) page: https://github.com/samersultan/csgo/issues

I would be interested to see how you customize / use this autoexec, check http://www.csgo.co for further discussion  and ideas. 


---

### Personal Settings ###

Mouse: Zowie Gear EC2 CL

Mousepad: Puretrak Talent

Monitor: 144hz Asus 27" VG series

In game resolution: 4:3 (1024x768)

Launch Options: 

**-w 1024 -h 768 -freq 144 -refresh 144 -processheap -novid -nojoy -noforcemparms -noforcemaccel -high -tickrate 128 -threads 4 +mat_queue_mode 2 +exec autoexec +mat_vignette_enable 0**


---

### Changelog ###

---

**April 04, 2014**

* Added print damage to top left corner of screen (displays damage on screen for faster reference, thanks to r/globaloffensive user [r/maddada](https://ssl.reddit.com/user/maddada/).
* Added volume and voice commands to binds that also display on top left corner of screen they are: 
  * "=" to cycle volume 
  * "-" to cycle voice_enable 0/1
  * "kp_plus" and "kp_minus" to cycle voice_scale
* Changed client port to 27006 line 61 (more [info](http://www.reddit.com/r/GlobalOffensive/comments/22x6z7/i_found_a_miracle_fix_for_my_server_browser/)) 
* Added "spec_usenumberkeys_nobinds 1" 
* Added radar zoom bound to "E" key (thanks to r/globaloffensive user [r/maddada](https://ssl.reddit.com/user/maddada/)).
* Added grenade knife fast binds to numpad 2-4, lines 311 to 314 (more [info](http://www.reddit.com/r/GlobalOffensive/comments/1ruxn8/how_to_throw_fast_nades_in_cs_go/cdrca06)).
* Added clear decals to walk and crouch, lines 135 + 136.

  

**December 16, 2013**

* Removed crosshair binds and replaced with single crosshair 
* Add ignorerad and clear console binds
* Highlight damage taken and damage given in console 


**September 16, 2013**

* Updated crosshairs (new screenshots will be posted soon)
* Updated buy binds.
* Added voice scale controls to the "-" "+" buttons on the numpad. 
* Added video.txt
* Added Launch Options


**June 18, 2013**

* Fixed errors in code
* Commented out jump + crouch bind. Remove // if you want to use it. 

**June 17, 2013**

* Disabled FPS max (found settings no limit made the game run smoother)
* Changed view model to left hand


**May 30, 2013**

* Disabled rawinput (see notes)
* Crosshair Modifications 
* Spelling Corrections 



**May 11, 2013**

* Removed hud files, the hud I use was updated so its no longer necessary to host the files here. You can download the updated hud here: http://myhyper.de/competitive-hud/
* updated the autoexec, cleaned up some of the titles. 



**April 26, 2013**

* Added "flash folder" contains customized Competitive Hud 1.2 Files that work with the update pushed yesterday. 


**April 25, 2013**

* Added Mag 7 to F11 bind. 

**March 28, 2013**

* Fine-tuned crosshairs, removed volume binds (as per user requests). 

**March 23, 2013**

* Modded two crosshairs, fixed error. 

**March 03, 2013**

* Added jump bind to mouse wheel

**January 30, 2013**

* Add key bind to buy guns + changes crosshairs 

**January 05, 2013**

* Added 8 Crosshairs + Weapon Binds
