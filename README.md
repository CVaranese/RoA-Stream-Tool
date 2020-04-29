![preview](https://cdn.discordapp.com/attachments/574303886869790730/700308095779340298/unknown.png)
# RoA Stream Control

**This readme is WIP!**

So you want to do a Rivals of Aether stream, huh? Well, today is your lucky day, because I have done tons of work so you don’t have to! With this, you will be able to set up a RoA tournament oriented stream in no time.

# Features
- [Easy and fast setup](https://gfycat.com/fragrantfortunatealbacoretuna) using a browser source.
- [Handy interface](https://gfycat.com/slimynimbleequestrian) to change everything you need quickly, like player names, character, scores, round, casters...
- Every single skin the game has to offer is ((supported)) (more than 300 different skins!), included high quality renders.
- Some **Workshop** characters are also ((supported))!
- ((Dynamic, optional intro)) to be played when changing to the game scene.
- A "((VS Screen))" used to hide the game while changing replays.
- All the content on the combo boxes can be edited at will. You can quickly change which characters or skins your tournament is going to be using.
- Easy to customize! Add your own skins, workshop characters, custom overlays or even dive into the code if you're brave enough!
- This is **not** a [Stream Control](http://farpnut.net/StreamControl) clone. It doesn't have anything to do with it, everything is custom made.


# How to setup
These are instructions for regular OBS Studio, but I imagine you can do the same with other streaming software:
- Get the [latest release](https://github.com/Readek/RoA-Stream-Control/releases).
- Extract somewhere.
- Add a new browser source in OBS.
- Set it to local file -> 'RoA Scoreboard.html'.
- Set 1920 width and 1080 height. (if it looks weird after this, set your canvas resolution to 1080p or make the source fit the screen).
- Use custom frame rate -> 60 (if streaming at 60fps of course).
- Tick 'Refresh browser when scene becomes active'.
- Manage it all with the 'RoA Stream Control' executable.

Repeat from the 3rd step to add the VS Screen (*VS Screen.html*).

# Advanced Setup
Yes, the instructions above could be enough, but we can do better. All of this is optional of course.
 
2 basic transitions are included in the *Webms* folder, intended to be used to change to the game scene and the vs screen, if you don't have a transition yourself of course. To use them:
- Add a new stinger transition.
- Set the video file to *Game In.webm* if creating the game scene transition, and *Swoosh.webm* if creating a transition for the vs screen.
- Transition point -> 300 ms.
- I recommend you to set the Audio Fade Style to crossfade, just in case.
- On the scene's right click menu, set it to Transition Override to the transition you just created.

Let's do something a bit more advanced. We now have 2 tiny problems. On online replays, ((the overlay won't cover the player's icon on the top HUD)), but don't worry, we can fix that! Also, woudn't it be cool to remove the "3, 2, 1" numbers that the game plays when starting a game, so we can properly show our own intro? We can also do that:
- Download [these super cool rips](https://drive.google.com/open?id=1NEDii3B50eHT_goADzn6t3_O8Uvok0Gs), RIPs 26 and 27 will remove the "*3, 2, 1*", and RIP 31 will remove the icon border of the top HUD. I'll try to keep them updated.
- Get the [Rivals Modding Tool](https://github.com/jam1garner/rivals-modding-tool/), and extract it on the game's folder.
- Open the exe, then *Rip sprites*.
- A new folder with the game's sprites will appear, drop the super cool rips there and replace them.
- Back to the exe, select *Replace sprites*.

# Frequently Asked Questions, maybe
WIP
