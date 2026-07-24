# AntiFOMO-for-Discord
A lightweight Discord CSS modification built to reduce distractions and hide unnecessary UI elements. Best if used with BetterDiscord or Vencord Themes. Can even be used in conjunction with other custom CSS themes!

As I find more annoyances, I intend to add blockers for these as and where they show up.

## How to tweak:
Simply comment out (`/* [sample text */`) any line you wish to disable. I've been pretty heavy-handed in blocking elements that annoy me personally, so I understand if others may want to re-enable features that I've blocked out. I'll do my best to label everything as and where necessary.

## Other notes:
With the Nitro, Shop, and Quests sections being disabled from the home page, you can still navigate to these sections by pressing `Alt + Down Arrow` from the Friends section, or `Alt + Up Arrow` from the latest Direct Message recepient, as these pages still exist on the back-end. This CSS simply hides these as options to click on (and thus take up less screen space).

### Disclosure
This was drafted partially with assistance from ChatGPT (logged out, guest user mode) on the bare minimum featureset.

The extent to which LLM assistance was used is simply as a means to parse HTML and draft exact formatting inserted into the CSS file. I manually inspected web elements within the web console on Discord's webapp. I have personally tested the code extensively and audited every line of code, along with reformatting and architecting the structure of the file itself by hand.

The only file where LLM assistance was used is [`/AntiFOMO.css`](https://github.com/altunidev/AntiFOMO-for-Discord/blob/main/AntiFOMO.css), which currently consists of less than 25 sanely written, easily readable lines. I have personally audited and heavily tested this code.

If you have issues with LLM assistance, please do the open source thing and audit the file yourself. Want something not LLM-assisted? Feel free to fork this repo and do whatever you'd like with it.

Stopped reading after glazing over the word "ChatGPT" until the end? From one human to another, please re-read from line 15 to line 21 of this file.
