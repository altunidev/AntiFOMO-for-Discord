# AntiFOMO-for-Discord
A lightweight Discord CSS modification built to reduce distractions and hide unnecessary UI elements. Best if used with BetterDiscord or Vencord Themes. Can even be used in conjunction with other custom CSS themes!

As I find more annoyances, I intend to add blockers for these as and where they show up.

## Features
- In-webapp HTML element blocking
- Automatic updates
- Easily parseable file for maintaining and updating

## Preview
<details>
    <summary>Images</summary>
    
### Before
<img width="326" height="272" alt="image" src="https://github.com/user-attachments/assets/6f9e8c99-f2da-4526-ba5c-8e64ab15b61c" />

<img width="236" height="58" alt="image" src="https://github.com/user-attachments/assets/2cc4829d-d70a-4951-a3dc-9f543f894896" />

<img width="1024" height="1165" alt="image" src="https://github.com/user-attachments/assets/61356bad-79ae-4b6a-8259-211603da58ab" />

### After
<img width="330" height="154" alt="image" src="https://github.com/user-attachments/assets/e78a8a47-5d7b-4386-ae6a-1b3354ead757" />

<img width="157" height="62" alt="image" src="https://github.com/user-attachments/assets/0f76de65-9ce7-4e74-8f50-9a64bab4ca60" />

<img width="1029" height="1174" alt="image" src="https://github.com/user-attachments/assets/b091961f-ef5b-45be-ac89-52c637a5dfaa" />
</details>

## Installation
1. Install [Vencord](https://vencord.dev/) for your client
2. Within Discord, navigate to Settings > Vencord Settings > Themes
3. Download desired `.css` file (either the [source file](https://github.com/altunidev/AntiFOMO-for-Discord/blob/main/AntiFOMO.css) or the [auto updating file](https://github.com/altunidev/AntiFOMO-for-Discord/blob/main/AntiFOMO_Autoupdate.css) work, based on your desired use-case)
4. Click "Open Themes Folder"
    - If you're on Discord on a web browser, click "Upload Theme" instead
6. Navigate to where the `.css` file is, copy/move -> themes directory
7. Click "Load missing Themes"
8. Enable "AntiFOMO"

<details>
  <summary>Tips and Tricks...</summary>

## How to tweak
Simply comment out (`/* [sample text */`) any line you wish to disable. I've been pretty heavy-handed in blocking elements that annoy me personally, so I understand if others may want to re-enable features that I've blocked out. I'll do my best to label everything as and where necessary.

Tweaking will require you to use the main `AntiFOMO.css` file locally, as the autoupdate feature pulls the latest from this repository with my opinionated configuration.

You can also host your own custom configuration _with_ autoupdating by forking this repository and editing the `@import url` to your own source(s).

## Other notes
With the Nitro, Shop, and Quests sections being disabled from the home page, you can still navigate to these sections by pressing `Alt + Down Arrow` from the Friends section, or `Alt + Up Arrow` from the latest Direct Message recepient, as these pages still exist on the back-end. This CSS simply hides these as options to click on (and thus take up less screen space).

</details>

---

<details>
  <summary>More miscellaneous information...</summary>

# Why did you make this?
For myself. Really it's as simple as that. I made this because I got fed up with all the upselling attempts and stuff locked behind "Nitro" access. I've dropped my nitro subscription after years of keeping it, as my way to "flip the bird" to Discord for advertising to me on a platform that I was paying for.

So I decided to stop paying.

In doing so, I started messing with custom themes, and I got the itch to remove annoyances that've been bugging me for a while, and I started on a bit of custom CSS in the "Edit QuickCSS" Vencord theme feature.

I built this to be as minimal as possible. This does not aim to re-proportion or shuffle around elements. I aim to maintain full compatibility with the modern Discord client, such that it also maintains compatibility with customised CSS themes, should anyone wish to use these.

I built the "Autoupdate" feature because I use, on any given day, between one and four different PC's. Having to update the CSS file on every PC any time I find a new HTML element to block will get annoying after... well... even just _one_ change.

# Does this go against Discord's ToS?
Maybe. This does modify the client slightly.

But the entire Vencord project also modifies the client too, and it's existed for this long without being nuked from orbit.

As far as I've seen, the biggest thing against ToS is _**the malicious use of**_ clientside modifications. This aims only to improve the individual user experience and runs without affecting other users. In technicality, this is nothing more than a simple CSS modification.

# Disclosure
This was drafted partially with assistance from ChatGPT (logged out, guest user mode) on the bare minimum featureset.

The extent to which LLM assistance was used is simply as a means to parse HTML and draft exact formatting inserted into the CSS file. I manually inspected web elements within the web console on Discord's webapp. I have personally tested the code extensively and audited every line of code, along with reformatting and architecting the structure of the file itself by hand.

The only file where LLM assistance was used is [`/AntiFOMO.css`](https://github.com/altunidev/AntiFOMO-for-Discord/blob/main/AntiFOMO.css), which currently consists of less than 50 sanely written, easily readable lines of code (not including line comments, which I have written). There are more lines of documentation than code, in attempts to ensure this is as accessible to as wide of a population as possible. Additionally, I have personally audited, edited, and heavily tested this code.

If you have issues with LLM assistance in code, please do the open source thing and audit the file yourself. Want something not LLM-assisted? Feel free to fork this repo and do whatever you'd like with it.

Stopped reading after glazing over the word "ChatGPT"? From one human to another, please be decent and re-read from the beginning of this section.

</details>
