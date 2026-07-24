# AntiFOMO-for-Discord
A lightweight Discord CSS modification built to reduce distractions and hide unnecessary UI elements. Best if used with BetterDiscord or Vencord Themes. Can even be used in conjunction with other custom CSS themes!

## How to tweak:

Simply comment out (`/* [sample text */`) any line you wish to disable. I've been pretty heavy-handed in blocking elements that annoy me personally, so I understand if others may want to re-enable features that I've blocked out. I'll do my best to label everything as and where necessary.

### Disclosure
This was drafted partially with assistance from ChatGPT (logged out, guest user mode) on the bare minimum featureset.

The extent to which LLM assistance was used is simply as a means to parse HTML and draft exact formatting inserted into the CSS file. I manually inspected web elements within the web console on Discord's webapp. I have personally tested the code extensively and audited every line of code, along with reformatting and architecting the structure of the file itself by hand.

The only file where LLM assistance was used is [`/AntiFOMO.css`](https://github.com/altunidev/AntiFOMO-for-Discord/blob/main/AntiFOMO.css), which currently consists of less than 50 sanely written, easily readable lines. I have personally audited and heavily tested this code. I intend to improve it by hand.

If you have issues with LLM assistance, please do the open source thing and audit the file yourself. Want something not LLM-assisted? Feel free to fork this repo and do whatever you'd like with it.
