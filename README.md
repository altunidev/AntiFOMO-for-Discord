# AntiFOMO-for-Discord
A lightweight Discord CSS modification built to reduce distractions and hide unnecessary UI elements. Best if used with BetterDiscord or Vencord Themes. Can even be used in conjunction with other custom CSS themes!

As I find more annoyances, I intend to add blockers for these as and where they show up.

## Features
- In-webapp HTML element blocking
- Automatic updates
- Easily parseable file for maintaining and updating

## How to tweak
Simply comment out (`/* [sample text */`) any line you wish to disable. I've been pretty heavy-handed in blocking elements that annoy me personally, so I understand if others may want to re-enable features that I've blocked out. I'll do my best to label everything as and where necessary.

Tweaking will require you to use the main `AntiFOMO.css` file locally, as the autoupdate feature pulls the latest from this repository with my opinionated configuration. You can also host your own opinionated configuration with autoupdating by forking this repository and editing the `@import url` to your own source(s).

## Other notes
With the Nitro, Shop, and Quests sections being disabled from the home page, you can still navigate to these sections by pressing `Alt + Down Arrow` from the Friends section, or `Alt + Up Arrow` from the latest Direct Message recepient, as these pages still exist on the back-end. This CSS simply hides these as options to click on (and thus take up less screen space).

---

# Why did you make this?
For myself. Really it's as simple as that. I made this because I got fed up with all the upselling attempts and stuff locked behind "Nitro" access. I've dropped my nitro subscription after years of keeping it, as my way to "flip the bird" to Discord for advertising to me on a platform that I was paying for.

So I decided to stop paying.

In doing so, I started messing with custom themes, and I got the itch to remove annoyances that've been bugging me for a while, and I started on a bit of custom CSS.

I built the "Autoupdate" feature (by importing the main CSS file) because I use, on any given day, between one and four different PC's, all with Discord logged in (not including mobile devices). Having to replace the CSS file on every PC any time I find a new HTML element to block will get annoying after... well... even just one change. So instead, I'd have the CSS pull the latest from this repo automatically.

# Disclosure
This was drafted partially with assistance from ChatGPT (logged out, guest user mode) on the bare minimum featureset.

The extent to which LLM assistance was used is simply as a means to parse HTML and draft exact formatting inserted into the CSS file. I manually inspected web elements within the web console on Discord's webapp. I have personally tested the code extensively and audited every line of code, along with reformatting and architecting the structure of the file itself by hand.

The only file where LLM assistance was used is [`/AntiFOMO.css`](https://github.com/altunidev/AntiFOMO-for-Discord/blob/main/AntiFOMO.css), which currently consists of less than 25 sanely written, easily readable lines. I have personally audited and heavily tested this code.

If you have issues with LLM assistance, please do the open source thing and audit the file yourself. Want something not LLM-assisted? Feel free to fork this repo and do whatever you'd like with it.

Stopped reading after glazing over the word "ChatGPT" until the end? From one human to another, please re-read from the beginning of this section.
