---
author: Kev
categories:
- Games
date: "2026-10-11"
lastmod: "2026-10-11"
tags:
- linux
- cli
- ssh
- zx81
title: Termzogs
url: /termzogs-game/
image : "/img/termzogs.png"
---
![](/images/termzogs.png)

Termzogs is the second CLI game I've made. Yet again, it is based on a classic ZX81 game. This time inspired by the superb game *Mazogs* by Don Priestley.

For this game, I decided to give AI Vibe Coding a try. I was curious to find out two things. First, I wanted to see if it would make coding easier and faster (I was pretty sure it would manage that much). The second reason was to see if programming would still be enjoyable and rewarding, or if AI would take all the pleasure and satisfaction out of writing code.

Here's how I approached creating this game.

First, I wanted to create a spec for how the game should be structured and the basic mechanics of how it should work. To help me do this, I used Google Gemini in the browser. After a bit of iteration with Gemini, I had a first draft Markdown file I could use to see if the coding agent could get something running.

For the coding agent, I used GitHub Copilot in VS Code. I didn't have a strong preference for any particular code assistant. I considered Claude Code, Cursor, and Codex as well, but figuring I'd need to take out a subscription, I decided to try Copilot first as it was the cheapest option. Yep, I'm that tight!

Rather than jumping in and subscribing to the Pro version straight away, I decided to start with the free tier and upgrade once the free quota ran out.

Placing the Markdown file into a new folder and opening VS Code, I asked the AI to read the spec file and create the basic game based on the specifications.

I was amazed at what a great job it made of it. It created a basic game that actually worked first time! Everything was static, with only one character per game cell, but it all functioned properly. It generated a maze, placed Zogs throughout the corridors (though they didn't move yet), structured the project cleanly, and even wrote test suites. I was very impressed!

This first version was simple, and the game wasn't complete by any means. For the next iteration, I decided to work with Gemini again to create a second spec file to flesh out the gameplay. I then copied the second spec into the game folder and repeated the process, asking Copilot to update the game based on the new specifications.

Again, GitHub Copilot did a fantastic job.

At this point, I wanted to build out the game one step at a time so as not to change too much in one go, so I didn't bother with any further spec files. I used the Copilot chat panel to refine the code directly, making the graphics bigger, adding a map view mode, building menus, and improving the maze generation algorithm. It really felt like pair programming with a senior, insightful coding partner.

I found the overall experience extremely positive. When I wrote CLI Labyrinth, it took me ages to get the maze generation code working smoothly; it was quite hard work. I think that project took me a couple of weeks' worth of evenings to complete. Termzogs took just 4 evenings of effort, and the end game quite a bit is more complex.

As always, you can download pre-built binaries of the game for Linux and Mac from [itch.io](https://yorkshirekev.itch.io/termzogs).

If you just want to play it without installing anything, I built a WebAssembly (Wasm) compiled version that runs in the web browser. You can [play Termzogs directly in your web browser](https://www.kevssite.com/termzogs).

And finally, if you want to see what kind of code an AI vibe coded game looks like, you can check out my [GitHub repository](https://github.com/YorkshireKev/termzogs).

Perhaps the most impressive thing about GitHub Copilot is its generous free tier. I intended to purchase the Pro subscription once the free quota expired, but amazingly, I finished the entire game development while using less than 70% of my free tier allowance! My next experiment will be a lot more involved than a terminal CLI game, so I expect I'll need to upgrade soon.

Has AI taken the pleasure out of coding? For me, absolutely not. It has definitely changed the approach to coding. It feels much more like pair programming or directing your own senior developer. AI has given me a renewed spark for creating games and applications by taking away the repetitive, tedious tasks. Time will tell where this technology goes, but I doubt I'll be going back to coding without AI anytime soon.