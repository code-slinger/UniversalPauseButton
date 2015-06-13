# Universal Pause Button
------------------------

I like to play video games.  I also have a significant other, and she often walks into the room to talk to me while I'm playing a video game.  I would like to pause the game so that I can give her my undivided attention while she's talking to me, but a lot of games (particularly single-player ones) have these "un-pausable" cut scenes or other areas of the game where the normal pause functionality doesn't work.  This annoys both me and her, because I'm supposed to be the computer expert, and it looks like I don't even know how to pause my stupid video game.  So usually what ends up happening is I skip the cut scene and miss the story, or upset my SO by not paying attention to her as well as I should.

So that is why I wrote Universal Pause Button. It's a very simple Windows desktop app that sits in the system tray. Its icon resembles a pause button.  When you hit the actual Pause key (also known as Break) on your keyboard, the program determines which window is currently in the foreground (i.e. your game's window,) and pauses it.  No matter where you are in the game. Even in the middle of one of those pesky cut scenes that would otherwise be un-pausable.  When you press the key again (as long as you haven't since re-focused to another window,) the game will un-pause.

As of v1.0.3 you can now customize the "Pause" key that you want to use. Read the settings.txt file. The program reads the custom pause key from the settings.txt file during startup.

I've currently been testing this with The Witcher 3, and it is working great.  However, your mileage may vary. "Pausing" processes is something that usually only debuggers do, and I can't predict how your game will react to it.  Pausing processes may lead to race conditions among the threads of that process, but like I said, testing has been very positive for me so far.  I've already gotten great value out of the program, as there are lots of cut scenes in The Witcher 3, that I don't want to skip. The main use case for this app is single player games, as pausing your multi-player game will undoubtedly just get you kicked from the session, as if your computer had just crashed or hung. So don't use it in multi-player games.  It also works on applications that are not games at all.

https://myotherpcisacloud.com
