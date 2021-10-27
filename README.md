# Movie Time /L Unleashed

*Why can't I be viewing this on the same crappy black and white TV that everyone watched the original missions on?* - well, now we can!

[Unleashed](https://ksp.lisias.net/add-ons-unleashed/) fork by Lisias.


## In a Hurry

* [Latest Release](https://github.com/net-lisias-kspu/MovieTime/releases)
	+ [Binaries](https://github.com/net-lisias-kspu/MovieTime/tree/Archive)
* [Source](https://github.com/net-lisias-kspu/MovieTime)
* Documentation
	+ [Project's README](https://github.com/net-lisias-kspu/MovieTime/blob/master/README.md)
	+ [Install Instructions](https://github.com/net-lisias-kspu/MovieTime/blob/master/INSTALL.md)
	+ [Change Log](./CHANGE_LOG.md)
	+ [TODO](./TODO.md) list


## Description

So some time ago, whilst recreating an Apollo mission, the original author thought to himself "why can't I be viewing this on the same crappy black and white TV that everyone watched the original missions on?" Ah, the nostalgia. Anyway, now we can. Oh, and there's night vision, too.

<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEjSmQM6n4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/8UXGvEDwdF0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Features

* Windows 32-bit.
* Windows 64-bit, reported window-sizing bug (looking into).
* Mac. @TheGamingNoobster says it does.
* Linux. Reported to work by @BigFatStupidHead.
* Win64 may display oversized settings window.
* Add pixelation effect for certain modes.
* A thermal camera mode that can be used in conjunction with Deadly Reentry.
* A JJ Abrams camera mode. Lens flares for everyone!

### The Title Overlay System

As you see in the first two screenshots, you can now add overlay graphics in real-time. To do this, you need to first create the graphic(s) you want to overlay. There's included a few examples in the MovieTime/Textures directory (`Apollo 11.png` and `Duna 1.png`). These were done in Paint.NET. Note that you can use the alpha-channel to make cutouts as well as semi-transparent areas.

To make the overlay appear, edit your `GameData/MovieTime/MovieTime.xml` file in a text editor (it will appear after the first time you run KSP). Find the section that you want the overlay to appear (ie, `<SpaceCentre>`, `<Flight>`, `<Map>`, etc) and add an entry in the section: `<TitleFile>Apollo 11.png</TitleFile>` - this will be the file that you want to overlay in that section. You can do this even while KSP is running. Once you've set your scene, hit the `Title` button on the MovieTime settings screen and it will load the overlay.

I've added a key binding, `CTRL+O`, that will toggle the `Title` setting without you having to bring up the settings panel. Also, `CTRL+SHIFT+O` will force a re-read of the .xml file and a re-load of the overlay file. This can be used to change from one overlay to another on the fly. Yeah, the system is a bit convoluted, but I wasn't up to building a secondary 'director' app that would feed MovieTime with this information.



## Installation

Detailed installation instructions are now on its own file (see the [In a Hurry](#in-a-hurry) section) and on the distribution file.

## License:

This work is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). See [here](./LICENSE)

Please note the copyrights and trademarks in [NOTICE](./NOTICE).


## UPSTREAM

* [bernierm](https://forum.kerbalspaceprogram.com/index.php?/profile/25648-bernierm/) ROOT
	+ [Forum](https://forum.kerbalspaceprogram.com/index.php?/topic/92874-*)
	+ [Imgur](https://imgur.com/a/Ts1iX)
	+ [CurseForge](https://www.curseforge.com/kerbal/ksp-mods/movietime/)
	+ [Github](https://github.com/bernierm/MovieTime)
