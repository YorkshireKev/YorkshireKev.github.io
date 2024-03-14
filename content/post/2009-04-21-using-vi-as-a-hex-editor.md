---
author: Kev
categories:
- Linux
date: "2009-04-21T00:00:00Z"
dsq_needs_sync:
- 1
dsq_thread_id:
- 1763114083
redirect_from: /2009/04/21/using-vi-as-a-hex-editor/
syntaxhighlighter_encoded:
- 1
tags:
- hex
- vi
title: Using vi as a hex editor
url: /using-vi-as-a-hex-editor/
---
Sometimes I find it useful to switch to hex mode when editing a file in vi. The command for switching is not very obvious so thought I'd share...

So, open a file in vi as usual. To switch into hex mode hit escape and type:
{{< highlight bash >}}
:%!xxd
{{< / highlight >}}

And when your done and want to exit from hex mode hit escape again and type:
{{< highlight bash >}}
:%!xxd -r
{{< / highlight >}}

Okay, so this isn't actaully switching to vi's 'hex mode'; vi doesn't have one. What the above actually does is to stream vi's buffer through the external program 'xxd'.
