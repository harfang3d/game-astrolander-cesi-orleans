<img src="img/logo_cesi_harfang.png" align="right" width="220"/>

# Astro-Lander Game

## CESI x HARFANG Workshop

![cesi banner](img/cesi_banner.png)

Astro-Lander is a game prototype co-created for a 1-day workshop between [CESI Orleans](https://orleans.cesi.fr/) & [Harfang 3D](https://www.harfang3d.com). The game relies on realtime physics to challenge the player on their skills to counterbalance gravity and inertia.<br>
Astro-Lander works both in **2D** and **VR**. It is implemented in **[Python](https://www.python.org/)** :snake:<br>

Astro-Lander can be played:
- on a PC (desktop/laptop) using the keyboard
- in VR, using any SteamVR-compatible heaset and the controllers
The gameplay remains in 2D, the display being in 3D or VR.

**Gameplay preview**

![gameplay](img/gameplay_000_web.gif)

* All the levels were created by a team of CS students at CESI Nanterre.
* Some of the game logic was implemented by the students.
* The game is open source and can be re-used for any other purpose.

## If you want to play :video_game:
 - Download the [latest release](https://github.com/harfang3d/game-astro-lander/releases) (look for a file like ` astrolander_xxx.zip`)
 - Unzip it
 - Run `2-run.bat` (or `3-run vr.bat` if you feel lucky and have SteamVR installed with a VR headset)
 - To control the lander (the spaceship with a little :brain: in it) press the arrow keys:
   - :arrow_left: Thrust `left`
   - :arrow_right: Thrust `right`
   - :arrow_left: + :arrow_right: Thrust `up`
 - Get all the coins
 - Reach the homebase (flat cylinder on the ground, looking like a target, facing upward)
 - If your life reach `0`, you die
 - If your fuel reach `0`, you die
 - Press `k` to enable the `AAA` rendering mode (realtime GI and reflections)

## If you want to code :computer:

### Requirements:
 - Python 3 (provided)
 - [Harfang 3.2.4](https://pypi.org/project/harfang/) (provided)
 - VSCode
 - [Harfang Studio](https://www.harfang3d.com/en_US/studio)
 - Blender/Maya (optional)
 
 ### How do install it:
 - clone the repository
 - open the folder in VSCode
 - run it
 
 ### How to edit/create a new level:
 - Install [Harfang Studio](https://www.harfang3d.com/en_US/studio)
 - Run Harfang Studio
 - open the project (`resources/project.prj`)
 - look for the `resources/scenes/levels` folder and make new levels
 - a library of blocks and stuff can be found in `resources/assets/blocks.scn`
 - you can simply copy/paste objects using `ctrl-c` & `ctrl-v`
 - GO! CREATE!

## Contributors :red_haired_woman: :man: :bald_woman: :bearded_person:
- Anthime-Didi
- Astrofra
- CharlesQ1
- Disketflu
- Entwickel
- floxx2112
- Kimimar0
- Kipixelle
- masky612
- NinD9
- Rom1RG
- Scorpheus
- StarLaqueur
- Taikylah
- Tetsud0
- ugolicatesi
