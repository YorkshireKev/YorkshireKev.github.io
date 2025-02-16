---
author: Kev
categories:
- Games
date: "2020-05-06T00:00:00Z"
lastmod: "2025-01-27"
tags:
- godot
title: Godot Experiment no. 2, Central Cavern
url: /central-cavern/
image : "/img/central-cavern.png"
---
![](/images/central-cavern/screenshot1.png)

One of my all-time favourite games is Manic Miner on the ZX Spectrum. When Bug-Byte released Matthew Smith's masterpiece in 1983 the bar was raised for quality gaming on the Speccy. Sure there were many, many excellent games released on the Spectrum (I'm looking at you Ultimate) but Manic Miner is still my go-to game when I need a retro gaming fix.

Ever since I saw Mario64 on the N64 I wondered what a 3D version of Manic Miner or Jet Set Willy would look and play like. After all, if Mario could make the jump to 3D, why not Willy?

So with Covid19 removing most of my excuses for not doing a spot of coding in the evenings I thought I'd try making a 3D version of Manic Miner. Well, not the whole game, just the first level to try and get a flavour of what a 3D manic miner might look like.

Having cut my teeth with the Godot game engine on my 2D shooter Retrocadia, I'm feeling confident I can get something working... I mean, writing a 3D game... how hard could it be right?

This page is my mini-blog/development diary. I'll add sections at the bottom of the page as I make progress with the game.
>
> Update - I've now completed making the game.
>
> Central Cavern has been released for Windows, Mac, Linux and Desktop Web Browsers.
>
> **Play it directly in your Desktop Web Browser: [https://www.kevssite.com/central-cavern-web](https://www.kevssite.com/central-cavern-web)**
> 
> **Download it from itch.io: [yorkshirekev.itch.io/central-cavern](https://yorkshirekev.itch.io/central-cavern)**
>
>**Download it from gamejolt: [gamejolt.com/games/central-cavern/532409](https://gamejolt.com/games/central-cavern/532409)**
>

Here are some screenshots of the finished version:

![](/images/central-cavern/screenshot3.png)
![](/images/central-cavern/screenshot2.png)
![](/images/central-cavern/screenshot4.png)

...and a short video of the game:

<div class="embed-container">
  <iframe
      src="https://player.vimeo.com/video/439503171"
      width="500"
      height="281"
      frameborder="0"
      webkitallowfullscreen
      mozallowfullscreen
      allowfullscreen>
  </iframe>
</div>



# FAQ #
**Is this going to be a full 3D version of Manic Miner?**
*No, I'm only going to do the first level, Central Cavern. Hence the name of this project is called Central Cavern.
I don't think I'm up for the slog of doing more than that :/*

**When do you expect the game to be released for download?**
*The game is available for download from itch.io: [yorkshirekev.itch.io/central-cavern](https://yorkshirekev.itch.io/central-cavern)* or from gamejolt: [gamejolt.com/games/central-cavern/532409](https://gamejolt.com/games/central-cavern/532409)

**What software are you using to make the game?**
*Well, the main game logic etc will be written using the Godot game engine, with GD Script for the programming language.
For the graphics, I'm using Blender. For sound, I'll probably use audacity to edit sound files etc, and for any 2D graphics, Gimp is my go-to choice of editor.*


# 6-Jun-2020 - The First Update! #
Off to a flying start! Okay, so I've been working on for a few weeks and not posted anything yet!. Over the last few weeks, I've managed to make the basic level structure in Blender and modelled the characters for the Guardian and Miner Willy. Actually, I'd done the Guardian a year or two ago do I just dug it out, imported it into the latest version of blender and added the rigging for animation. I'll probably redo Miner Willy at some point as I'm not happy with how he's turned out.

Anyway, I've now got a very basic working program. Obviously, there is loads more work to do before it becomes anything like a working game, but I'm quite pleased with the progress so far and I've really enjoyed making it.

Here's a short video of my progress so far...

<div class="embed-container">
  <iframe
      src="https://player.vimeo.com/video/428592264"
      width="500"
      height="281"
      frameborder="0"
      webkitallowfullscreen
      mozallowfullscreen
      allowfullscreen>
  </iframe>
</div>


# 25-Jun-2020 - Collapsing Platforms, Keys and More #
Over the last 3 weeks, I've made a fair amount of progress on and off. I've got the basic game working, with collapsing platforms, keys. Willy can now be killed by hitting the guardian or a spikey plant etc, or even by falling too far.

I've had to adjust some of the platforms to make the game possible to complete.

One of the trickiest things I've been trying to sort is the camera. I've added a second camera view that gets toggled to when the main camera view gets blocked. You can select between them manually too. This is much better than before, but still not quite an good as I want it to be.

I've still got a fair bit to add yet. There's more sound effects and, of course, some music. Not to mention a title screen and the game over boot scene. Hopefully, I'll have another update in a couple of weeks. Thanks for looking!

Here is an updated video showing the progress so far...

<div class="embed-container">
  <iframe
      src="https://player.vimeo.com/video/432599450"
      width="500"
      height="281"
      frameborder="0"
      webkitallowfullscreen
      mozallowfullscreen
      allowfullscreen>
  </iframe>
</div>


# Update 4-Jul-2020 - Music and Sound and a Title Screen! #
I've now added a simple title screen to the game with music taken from a 1936 recording of Johann Strauss's Blue Danub played by Finnish orchestra Rytmi-Pojat, directed by Eugen Malmstén. I've also managed to find a free version of Hall of the mountain King recorded by Kevin MacLeod, which I've trimmed to use as the in game tune.

I had to resort to doing a spot of coding on the ZX spectrum to get an authentic jumping sound.
![](/images/central-cavern/jump-code-zxbasic.png)
It must have been 30+ years since I've written anything in zx basic!

There have been a few other tweaks here and there, and I'm starting to see light at the end of the tunnel. I still need to add a game over screen, something for when the player completes the game and I'll probably faff with the lighting to try and give it a more underground feel if I can.

# Update 12-Jul-2020 - Just about finished it #
After a final flurry of activity, I've just about completed writing the game. There's probably a little bit of polish to add, but it's now a complete and playable game! Okay, so it's only got one level but as I always said, that's all I was ever going to write. I've added a game over screen, and a nice surprise if the player ever manages to complete the level.

My next task is to add some screenshots and make a short video of the gameplay. I then plan to seek permission from the copyright owners of Manic Miner (if I can find them) to see if I can release the game as a free download. Wish me luck!

# Update 21-Aug-2020 - Out in the wild! #
I have finally decided to make central-cavern available for download. I've uploaded the game to itch.io and I will also upload to gamejolt once their site comes back online.

# Update 27-Jan-2025 - Experimental Web Version Released #
I'm excited to announce a new web release of central cavern!

I've exported the game to the HTML5/WebAssembly platform, allowing it to run on most modern browsers.

**Important Note:** Due to the game's reliance on keyboard input, it's currently designed for desktop browsers. While it might load and run on mobile devices, there will be no way to play it without a physical keyboard.

To help audio playback, I've added a new start screen specifically for the web version. Most browsers require some user interaction before allowing audio to play, and this screen addresses that requirement.

There might be a few other minor audio glitches in the web version, but I plan to focus my attention on my next project instead of making further updates to this game.

I hope you enjoy playing the web version, which you can try [by clicking here.](https://www.kevssite.com/central-cavern-web)