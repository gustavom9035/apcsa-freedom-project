# Tool Learning Log

## Tool: **RetroED**

## Project: **Mod** for Sonic CD (2011)

---

### 09/30/24 - 10/21/24 ("Passonate Preperation Zone 1" [Track 1](https://www.youtube.com/watch?v=kAHNlAAuV8E)):
* In order to get this whole thing running you'll need the Sonic CD [decompilation](https://github.com/RSDKModding/RSDKv3-Decompilation).
  * I'd recommend using this [guide](https://gamebanana.com/tuts/14111) or this [video](https://www.youtube.com/watch?v=CO7GpbWuzDI).
  * Both listed above are under the assumption you're on windows so if not just check the readme on the decomp for your OS!
  * As well make sure to follow the setting up the mods part! I'd recommend to use "MegAmi's Additons" as a test of sorts.
* Once you get that sorted we can move onto the actual [tool](https://github.com/RSDKModding/RetroED) :D
  * Likewise you can follow the readme for instructions on how to build but there's also an actual release this time around!
  * I'd recommend to just use the release as its less of a hassle and potential headaches but you do you :p
* Hopefully now you've gotten both working and running properly as now its time to connect the two!
  * First up open up RetroED and you'll be greeted with a "grey screen" and some "clickables" on the top left.
  * Click on options and select game manager. Here you'll be greeted with different RSDK versions but all you need to do is click on RSDKv3. Now it'll ask for you to put the .exe and data folder location of the Sonic CD decomp.
    * The former is simple as its looking for the Sonic CD "launcher" which should be in the folder from the decomp release listed as RSDKv3.exe.
    * However for the ladder if you just used the Data.rsdk for the game you'll need to use the RSDK unpacker on the tools selection. Once here click on select DataPack and find your Data.rsdk. Then after it loads click export DataPack which will make the folder for you and all you need to do is set its location. Find your data folder and copy it into your Sonic CD folder and delete the Data.rsdk already there. Since we're here copy the scripts folder from Sonic CD into the data folder then copy the data folder with scripts now inside of it. After this is all done go back to the game manager and put the data folder location.
  * Go to your mods folder in Sonic CD and make a new folder with your mod name (Can be anything e.g. "test"). Here paste the data folder and make a new .ini file named mod. To make an .ini file create a txt file and open it. Then under file click save as and rename it as mod.ini. Here you can add credits and most importantly make sure to put TxtScripts=TRUE on a new line.
  * If you've done everything correct all you need to do now is go to tools and open scene editor. Then click on file and choose open to which i'll ask for the scene (Make sure to change RSDKv4 Scenes to v3) which is loacted in your mod's data folder. Then i'll ask for the gameconfig which is in the game folder. If the scene shows up all you need to do is click on Run Game and if that works then congrats! You've set it up properly!
* Getting this all working was trial and error so not much tinkering went on however I did manage to edit the object placement and save it so next time will be more tinker focused than setup! ^_^

### 10/21/24 - 10/28/24("Passonate Preperation Zone 2" [Track 2](https://www.youtube.com/watch?v=r_lxs_TdYU0)):
* Text

### 10/28/24 - 11/4/24("Passonate Preperation Zone 3" [Track 3](https://www.youtube.com/watch?v=taQYqIg7pRg)):
* Checked the rest of the tools in RetroED such as the animation editor
  *  Viewed the sprites and animation frames as well looked at how they are stored.

### X/X/XX - X/X/XX:
* Text


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
