# someguy171's Guide to a new Windows 10 PC
New to PC gaming, or Windows 10 in general? Here are some tips and tricks, essential programs to use, and general advice!

## Table of contents
* Section 1 - Starting out
  * [General knowledge](#general-knowledge)
  * [Important parts of a computer](#important-parts-of-a-computer)
  * [Initial admin](#initial-admin)
* Section 2 - Organisation
  * [144Hz monitor?](#144hz-monitor)
  * [Two drives?](#two-drives)
* Section 3 - Downloading important things
  * [Downloading programs](#downloading-programs)
  * [Essential apps](#essential-apps)
  * [Drivers](#drivers)
* Section 4 - The extra few steps
  * [Other apps](#other-apps)
  * [Extensions for Firefox](#extensions-for-firefox)
  * [Changing settings for performance](#changing-settings-for-performance)
* Section 5 - Game settings
  * [DPI and Sensitivity](#dpi-and-sensitivity)
  * [Game settings - what do they mean?](#game-settings---what-do-they-mean)

# Section 1 - Starting out

## General knowledge

Windows 10 uses many default apps that are essential for navigation, organisation and setup.

![winapps](https://i.imgur.com/qI8nk5a.png)

Feature | Explanation
------- | -----------
Taskbar | The bar at the bottom. In the centre are the pinned apps. Pin apps by dragging them from File Explorer or the Desktop straight on top of the Taskbar.
Start Menu | Access the Start Menu by pressing the Windows icon on the left of taskbar, where you can search for programs and files.
Notification centre | View your internet settings, time/date, and notifications on the right of the taskbar.
Auto-scroll | Middle-click to enable auto-scroll; move your mouse up and down to quickly glide through pages.

If you having a gaming mouse, it could have side buttons. In web browsers and most apps, you can use two of these buttons to go back or forward one page. It can be different for every mouse, so test which ones work on your mouse.

## Important parts of a computer

CPU - The Central Processing Unit is the brain of the computer. Your CPU power is especially important in open world games.

RAM - Random Access Memory stores programs that are currently being used. Having more RAM will allow you to have more apps open, like a game + music app + video app + Discord + more, without impacting general performance.

GPU - The Graphics Processing Unit handles visuals. Your GPU is the most influential for performance in PC games.

Motherboard - The body of the PC. All other components are seated on or are connected to the "mobo."

Monitor - The screen that connects to your GPU in the PC. Usually 60Hz (fps), but can be 120Hz or 144Hz.

If you want to find out these parts' names, specs or details, use CPU-Z (in [Other apps](#other-apps)).

## Initial admin
Go to Settings, Update & Security, Windows Update, and select `Check for Updates`. Wait for the updates to download, and restart your PC as many times as needed.

Go to Settings, System, Display. Make sure your display resolution is good, and change your settings as needed if you have multiple monitors.

# Section 2 - Organisation

## 144Hz monitor?

A **144Hz monitor** will refresh 144 times every second, allowing for smoother visuals.
Although HDMI 1.4 can support 144Hz, it will often cap at 120Hz. To take advantage of your monitor fully, use **DisplayPort**.

Go to **Settings**, System, Display, and select `Advanced display settings`.
Choose your main display (the 144Hz monitor), and make sure, next to `Refresh rate (Hz)`, it says `144Hz`.

If it doesn't say this, select `Display adaptor properties for Display 1`.
Navigate to the `Monitor` tab, and change the refesh rate to `144 Hertz`.
If this option is not present, you may need to [update your graphics drivers](#drivers).

## Two drives?

A **drive** is storage, either as a *hard drive* (spinning disc) or an *SSD* (electronic, no moving parts). They appear in File Explorer with a unique icon, and their names will have a drive letter - for example, (C:) or (D:).

If you only have one drive, you can skip this section.

If you have an SSD for Windows, and another drive for extra storage, you'll want to clear as much space on the Windows drive as possible. While programs benefit greatly from the increased speed of a solid state drive, files generally don't. Keeping folders like Documents and Downloads on your SSD will take up too much space with little benefit.

1. In **File Explorer**, navigate to `This PC` on the left-hand sidebar.
2. Right click the `Desktop` folder, and select `Properties`.
3. Navigate to the `Location` tab, and select `Move...`.
4. Select your hard drive. Your SSD will likely have a small Windows icon beside it, while the HDD does not.
5. Right click in any blank space, hover over `New`, and select `Folder`.
6. Name the folder what you're moving. In this case, rename it to `Desktop`. Be sure to capitalise properly.
7. Select the newly made folder, and select `Select Folder`.
8. Select `Apply`, then `Yes` in the window that pops up.
9. Wait until the folder has successfully moved, then press `OK`.

Repeat the above steps for all folders in the `This PC` section:

* `3D Objects`
* `Desktop`
* `Documents`
* `Downloads`
* `Music`
* `Pictures`
* `Videos`

Be sure to rename the new folder (in step 6) correctly for each folder you're moving.

# Section 3 - Downloading important things

## Downloading programs
Download the correct version, 32 bit or 64 bit.

Not sure which to download? 

Go to **Settings**, System, About. Under `Device specifications`, `System type`, your architecture will be shown.

View this image to see how to safely download programs:

![downloading1](https://i.imgur.com/B06VbTy.png)

## Essential apps
- [**Firefox**](https://www.mozilla.org/en-GB/firefox/new/): A lightweight browser with good extensions and customisability.

- [**Discord**](https://discord.com/download): The best social app for gaming voice calls.

- [**Steam**](https://store.steampowered.com/about/): The biggest and most popular marketplace for games, made by Valve.

- [**Spotify**](https://www.spotify.com/uk/download/): Music streaming service.

- [**EarTrumpet**](https://www.microsoft.com/en-gb/p/eartrumpet/9nblggh516xp?activetab=pivot:overviewtab): Volume control. (drag it to taskbar from ^ menu)

- [**GeForce Experience**](https://www.nvidia.com/en-gb/geforce/geforce-experience/download/): Drivers and game optimisation. (**Nvidia / GeForce GPU only.**)

- [**Radeon Graphics Drivers**](https://www.amd.com/en/support): Auto-detects GPU and downloads drivers. (**AMD / Radeon GPU only.**)

- [**Everything**](https://www.voidtools.com/downloads/): Quickly search through all files on your drive(s)

- [**WinRAR**](https://www.rarlab.com/download.htm): Unzip / archive files.

- [**4k Downloader**](https://www.4kdownload.com/products/product-videodownloader): Simple YouTube video downloader.

## Other apps
- [**Battle.net**](https://www.blizzard.com/en-gb/apps/battle.net/desktop): Launcher for Blizzard and Activision games.

- [**Core Temp**](https://www.alcpu.com/CoreTemp/): Monitor your CPU temperature.

- [**CPU-Z**](https://www.cpuid.com/softwares/cpu-z.html): Find information about your PC.

- [**Epic Games Store**](https://www.epicgames.com/store/en-US/download): Free game(s) every week (as of May 2020).

- [**Origin**](https://www.origin.com/gbr/en-us/store/download): Launcher for EA games.

- [**Uplay**](https://uplay.ubisoft.com/en-GB): Launcher for Ubisoft games.

## Drivers

In basic terms, **drivers** are programs that allow your devices to work properly and effectively with Windows 10 and your programs/games. They are essential, especially if you want your PC to run new games well.

For gamers, the most important driver is your GPU driver, or **Graphics Drivers**.

1. Open **Nvidia Experience**.
2. Navigate to the `DRIVERS` tab.
3. Select `DOWNLOAD`.
4. Once it has downloaded, select `EXPRESS INSTALLATION`.
5. Wait until it has finished installing. Do not use your PC during this time.
6. Once it has finished, restart your PC.

Check Nvidia Experience every few weeks for a new driver. Sometimes, games will run much worse if you aren't on the most recent driver.

# Section 4 - The extra few steps

## Extensions for Firefox
- [**Augmented Steam**](https://addons.mozilla.org/en-US/firefox/addon/enhanced-steam-an-itad-fork/): Check price history and current best deals for games on Steam.

- [**Enhancer for YouTube**](https://addons.mozilla.org/en-GB/firefox/addon/enhancer-for-youtube/): Miniplayer while browsing, change skin, more tools.

- [**uBlock Origin**](https://addons.mozilla.org/en-GB/firefox/addon/ublock-origin/): Super simple adblocker.

## Changing settings for performance
- **Discord**
  - Settings, Appearance, **turn off Hardware Acceleration**
  - Settings, Windows Settings, **turn off Open Discord**
- **Steam**
  - Settings, In-Game, **enable in-game FPS counter**
- **Spotify**
  - Settings, Show Advanced Settings, turn off **Hardware Acceleration**

# Section 5 - Game settings

## DPI and Sensitivity

**DPI**, or Dots Per Inch, is a hardware value for your mouse that changes how accurate it is. If you have a gaming mouse, it will have a DPI button that cycles through its pre-made DPI levels.

**Sensitivity**, or 'sens' (pronounced sense), is the in-game speed of your mouse. In general, it's best to leave your DPI the same and change your sensitivity in the game.

## Game settings - what do they mean?

**Window setting** - Windowed (worst) is a regular window, like a browser. Fullscreen (best) maximises the resolution to fit your screen. Borderless Windowed (equal to fullscreen) looks like Fullscreen, but allows you to move the mouse out of the game.

**Resolution** - The number of pixels. Most monitors have 1920x1080 resolution. The lower the resolution, the worse the game will look, but the better it will run.

**Framerate** - The number of times the screen refreshes every second. 60fps (frames per second) is standard; anything more requires a specialised monitor.

**Vsync** - If your framerate is less than your monitor's refresh rate (e.g. game running at 20fps, monitor is 60Hz), you will see the [screen tear](https://imgur.com/eAcmiFC). This happens because the top and bottom of the screen are not synced. If you are experiencing screen tearing, turn Vsync on. Otherwise, leave it off.

**Field of View** (FOV) - the angle, in degrees, that you can see. With a higher FOV, things in front of you will appear smaller, but you can see more to the left and right.

**Motion blur** - Smears the edges of objects to accentuate camera movement. Leave this off - it drastically increases FPS.

**Global illumination** - Mimics how light bounces from one object to another. Turning it off increases FPS.

**Depth of Field** - Blurs objects that aren't in focus. Can be distracting, but doesn't impact FPS too much.

**SSAO/HBAO** - Adjusts lighting to calculate how much light falls on an object. Can have a decent impact on FPS.

**Anti-aliasing** - Blends colours and edges to mitigate the "jaggies" of diagonal lines. FXAA is fastest, but blurriest. MSAA is the most intelligent, but most taxing on FPS.

**Texture quality** - Controls resolution of all textures. Mostly taxing on VRAM.

**Texture filtering** - Reduces texture quality into the distance smoothly. It's old tech, so leave it at maximum and it still won't impact performance too much.

Any other settings may be specific to your game. Some games will have a VRAM counter; make sure whatever you change doesn't make the counter go above its maximum. This can cause your game to crash.
