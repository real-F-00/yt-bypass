# yt-bypass
these are some instructions to bypass the youtube anti-adblocker popups or fix the page not loading at all when using an adblocker.

### if you're on a Chromium-based web browser (Chrome, Brave, Edge, Opera, Vivaldi, ecc...)
1) install the [User-Agent Switcher for Chrome](https://chromewebstore.google.com/detail/djflhoibgkdhkhhcedjiklpkjnoahfmg) from the chrome web store
2) go to to its [Settings](chrome-extension://djflhoibgkdhkhhcedjiklpkjnoahfmg/options.html)
3) under `New User-agent name` insert: `Googlebot`, under `New User-Agent String` insert: `Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)` (this part is **VERY** important, make sure you pasted it correctly.), under `Group` insert: `Googlebot`, under `Append?` select: `Append`, under `Indicator Flag` insert: `GB`, then click `Add`.
4) now you'll see that in the list of the available User-Agents you'll have a new group called `Googlebot` with a new option: `Googlebot` and the User-agent string we inserted earlier.
5) on the left of the page you'll see more options, click on `Permanent Spoof list`, this will bring you to a new page.
6) under `Domain` insert: `youtube.com` and under `User-Agent String` select: `Googlebot`, then click `Add`.
7) and with that, you're done! your adblocker will now work again on youtube.

### if you're on a Firefox-based web broswer (Firefox, Librewolf, GNU Icecat, Mullvad Browser, Tor, ecc...)
1) install the [User-Agent Switcher](https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/)
2) head over to [Youtube](https://youtube.com)
3) at the top-right of the browser window you should see a button that looks like a puzzle piece _**(if you don't see it, scroll to the bottom and follow the instructions then go to step 4 once they're done.)**_, click on it, you'll see a list of your installed extensions, find `User-Agent Switcher` and click on it, a menu will have popped up.
4) under `Preferences...` enable `Override for Domain`, scroll down until you find a category called `Bot` with an arrow pointing downwards **`V`**, if it's pointing to the left instead **`<`** click on it, you'll see 3 options, click on `Google bot`
5) and with that, you're done! your adblocker will now work again on youtube.

## i don't see the puzzle piece at the top-right of my browser window!
### if you're on Tor Browser, Mullvad Browser or GNU Icecat:
1) press `ctrl + Shift + A`, if you can't press those buttons then click on the icon with 3 lines at the top-right of the browser window **`三`** then click on `Add-ons and themes`
2) click on `User-Agent Switcher` and make sure it's enabled, under `Run in Private Windows` Click on `Allow`.
- **if you're on Mullvad Browser or GNU Icecat then you're done! simply close the `Add-ons Manager` tab and head back to step number `3` under `if you're on a Firefox-based web broswer (Firefox, Librewolf, GNU Icecat, Mullvad Browser, Tor, ecc...)` and continue as normal, if you're using Tor Broswer then keep reading.)**
3) now right-click on the icon with 3 lines at the top-right of the browser window **`三`** a context menu will pop-up then click on the option at the bottom which should be `Customize Toolbar...`, a new browser tab will have opened.
4) in the new tab you'll see a bunch of icons along with text below them, locate the icon with the text `User-Agent Switcher - Disabled` below it, right-click it and select `Add to Overflow Menu`, the icon will disappear from the list and you'll see it added in the `Overflow Menu` on the right of your browser window, then proceed to close the `Customize Tor Browser` tab.
5) make sure you're on the tab with [Youtube](https://youtube.com) open in it, at the top-right of your screen you'll now see an icon with 2 arrows pointing to the right **`>>`** click it and a small menu will pop up with an option that says `Agent Switcher - Disabled` with an icon to its left, click on it, a menu will have popped up.
6) you're done! now head back to step number `4` under `if you're on a Firefox-based web broswer (Firefox, Librewolf, GNU Icecat, Mullvad Browser, Tor, ecc...)` and continue as normal.
### if you're on any other generic Firefox-based browser (Firefox, Librewolf, ecc...)
- that's very strange, you must've deliberetely disabled it yourself in some way; if that's the case, _you're on your own_, i **can't** know what you've done but if you're unsure how you did it or you simply don't remember, then maybe you'll find your answer [here](https://support.mozilla.org/en-US/questions/1403154), best of luck.
