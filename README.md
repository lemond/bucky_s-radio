bucky_s-radio
=============

Well known free radio channel changer script with Shoutcast/Icecast song titles


********
********
********

README

********
********
********

Bucky's Radio - the free version 2.6.4

Please see the notecard "Use of Diane's Radio" for OPEN SOURCE terms.

This radio script drops into your favorite object.  It provides dialog & chat interfaces, and you can throw a lot of stations at it!

Configuration

* As shipped, the radio looks for the notecard "stations-short"

* each line of the notecard takes the format:

<station description> = <url>

example:

Secret Agent = http://somafm-sc.streamguys.com:8082

* if you want to change the chat channel or notecard name, see the top of the "radio script" file.  I ship it with channel 77 enabled.

Group Land

* make sure you are currently set to be in the same group as the land you are putting the radio on

* edit the radio object, under "General": set the group to be that of the land.   Share the radio with the group, and Deed it.

Commands & Notes -- Dialog

* station descriptions are in a list, click the number of the station to change the channel

* the "Next" and "Prev" buttons will take you forwards and backwards through the list.  They wrap around.

* "List" will echo the current chunk of stations to your chat history

* The currently selected station is preceded with a '*'

Commands -- Chat

As shipped,  commands take the form of "/77 <command>"

* <number> - change the station - example: "/77 3" to change to channel 3 (without quotes...)

* "ls", "list"  - same as "List" in dialog - echo current chunk of stations

* "la", "listall" - dump all stations to chat history

* "<<", "prev" - go backwards in station listing

* ">>", "next" - go forwards in station listing

This radio is derived from the one done by Dianne Mechanique & sky Honey.

***
***
***
README Lemond Updates
***
***
***

This includes the wiki deed tools ("masked" as tools group) in case the object is deeded to group and you can't return it.  Kill it instead.

As it says in other notecards, once deeded, you're unlike to be able to update the stations or scripts.

The radio rezzes a song title announcer known to work for most legacy shoutcast stations on one hand and icecast 2 stations on the other.  These die if the stream changes from what it is when these objects are first rezzed.

The naming isn't perfectly clear.  Bucky's is a radio switcher and Kiti's "radios" are actually radio stream song announcers in floating text.

My particular work is released as a free cultural work with license Attribution-ShareAlike 3.0 United States (CC BY-SA 3.0 US), https://creativecommons.org/licenses/by-sa/3.0/us/

Note previous work is released under various licenses that say similar things.  If a license or notice was accidentally erased during my development,, sincere apologies to the author(s) whose generous contribution made this version of the radio possible.  Please consider all necessary notices are intact either here or elsewhere.  Advise find original versions for reference if you are planning to do more development.

Lemonodo Oh 2013-09-13

***
***
***
RESERVE2stations-short
***
***
***

lounge-radio swiss ambient chillout=http://swisslounge.net:8030/lounge-radio
synthetronica radio ambient=http://synthetronica.com:8000/ambient.ogg
thierry morati ambient=http://streaming201.radionomy.com:80/Thierry-Morati-dotcom
uzic house tech techno=http://stream.uzic.ch:9010/
psyradio progressive house=http://81.88.36.42:8010/
rsr detroit chicago=http://94.255.251.102:8080/
party vibes techno house trance=http://partyviberadio.com:8006/

***
***
***
RESERVEstations-short
***
***
***

BRITISH INVASION The Beatles.=http://64.40.99.2:8080
BeBop Radio = http://213.251.136.72:8800
BeatBlender [SOMAFM] =http://207.200.96.232:8006
Chillout,The Chillout Lounge = http://64.71.145.130:8010
European Trance, Techno, Hi-NRG =http://64.236.34.196:80/stream/1003
DavidByrne = http://www.live365.com/play/321397
Digitally Imported House silky sexy deep house = http://64.236.34.196:80/stream/1007
Frequence3 -- www.Frequence3.org - Une Rafale De Tubes =http://193.251.154.243:8000
Groove Salad - SOMA FM = http://somafm-sc.streamguys.com:8066
Jazz SKY - Absolutely Smooth Jazz 24/7 = http://64.236.34.196:80/stream/1010
Lounge,Digitally Imported Lounge = http://64.236.34.67:80/stream/1009
CLASSICAL =http://64.236.34.196:80/stream/1006
SOMA Groove Salad = http://64.202.98.91:8066
SOMA Illinois Street Lounge = http://207.200.96.231:8014
Salsa = http://194.79.31.246:7180
Secret Agent = http://somafm-sc.streamguys.com:8082
The Chillout Lounge = http://64.71.145.130:8010
TokyoNinja = http://211.9.44.188:8020
dance trance,Music One - Today's Dance = http://64.236.34.97:80/stream/1011
lounge - SmoothLounge.com = http://66.28.209.20:80
psy chillout -Chillout ambient psy chillout = http://64.236.34.67:80/stream/1035

***
***
***
stations-short
***
***
***

lounge-radio swiss ambient chillout=http://swisslounge.net:8030/lounge-radio
synthetronica radio ambient=http://synthetronica.com:8000/ambient.ogg
thierry morati ambient=http://streaming201.radionomy.com:80/Thierry-Morati-dotcom
uzic house tech techno=http://stream.uzic.ch:9010/
dj lemonodo=http://kubus-klub.net:8050/lemonodo
psyradio progressive house=http://81.88.36.42:8010/
rsr detroit chicago=http://94.255.251.102:8080/
party vibes techno house trance=http://partyviberadio.com:8006/

Use of Diane_s radio

******
******
******

Use of Diane_s Radio

******
******
******


March 6th, 2006
=================================
     THIS RADIO IS PROVIDED FREE OF CHARGE TO ALL.   =================================
IF YOU HAVE PAID MONEY FOR THIS RADIO PLEASE 
"ABUSE REPORT" THE SELLER AS THEY HAVE *CHEATED*
YOU ON PURPOSE AND DESERVE TO BE PUNISHED.  

The script is also provided as an OPEN SOURCE script and
is intended to allow you to make your own Radio and to
understand how the Radio and scripting works, NOT to 
provide you with a means to rip-off others by re-using it
in a "closed" COMMERCIAL product.   

IF YOU USE THIS SCRIPT IN ANOTHER RADIO, PLEASE LEAVE 
IT SIMILARLY OPEN SOURCE FOR ALL TO SEE AND TO USE.  

To work effectively, a Land Radio needs to be both copy-
able and transferable, so there is nothing to stop
copying and reselling of products like this except your
own sense of RIGHT and WRONG.  Please use it. :-)
=================================

INSTRUCTIONS:

If you own the land:

- Click on the Radio to get the dialogue box and change stations. 
- Put new stations in by editing the notecard inside

On group land the Radio must be owned by the group so:
- Make sure you have your Group Title showing 
  (the same group as the land you are on)
- Select "Share  with Group" in the Radio properties 
- Select "Deed to Group"  

The Radio is now owned by the group and should be able to 
change the land URL.  

***ONCE THE RADIO IS DEEDED TO THE GROUP YOU CANT GET 
IT BACK NOR ALTER THE STATIONS CARD INSIDE****

If you want to change the list of stations you have to res 
another radio, change the notecard and then deed *that* Radio
to the group as before.  

You can res and delete as many radios as you like.  

Have fun :-)

Dianne Mechanique
sky Honey

***
***
***
Bucky_s Introductory Note
***
***
***

http://forums-archive.secondlife.com/15/d6/129329/1.html
08-11-2006 15:12
This is a free radio, derived from Dianne's Radio. This is my first submission.

- easy configuration
- dialogs with extended station descriptions, prev & next pages
- chat commands (change station, list current chunk, list all, prev & next chunks)

Four files:
radio script
README
stations-short
Use of Dianne's Radio

Enjoy, and let me know of any bugs, custom work you want me to do, etc.

Bucky Barkley

-- radio script:
