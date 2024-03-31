---
author: Kev
date: "2015-05-29T00:00:00Z"
description: Online JavaScript keycode lookup utility
dsq_needs_sync:
- 1
categories:
- Programming
tags:
- javascript
redirect_from: /2015/05/29/javascript-keycodes/
title: JavaScript KeyCodes
url: /javascript-keycodes/
---
This is a simple JavaScript keycode lookup page. Just press a key and the JavaScript Key Code will be displayed in the box below.

If you want to stop your browser scrolling when you press space or arrows etc then click in the input field to take the focus away from the whole page.

{{< rawhtml >}}
<input type="text" maxlength="0" size="2">

<script>
  window.addEventListener("keydown", function (event) {
    document.getElementById("code").innerHTML = event.keyCode;
    if (event.key) {
      if (event.keyCode > 47 && event.keyCode < 91) {
        document.getElementById("char").innerHTML = " - " + event.key.toUpperCase();
      } else {
        document.getElementById("char").innerHTML = " - " + event.key;
      }
    }
  }, false);
</script>
<span id="code" style="background-color: #faee95; font-size: 100;  border-style: solid; border-width: 5px; border-color: #848789"></span>
<span id="char" style="font-size: 70;"></span>
{{< /rawhtml >}}

The text equivalent of the key being pressed is only displayed in browsers that support event.key. Rather surprisingly this does not include Chrome!