
<h1 align='center'>
<img alt='Opale-Messenger' height="40px" src='./images/icone.png'>
  Opale Messenger 
</h1>

<p align="justify">
  Opale is a wrapper for the famous Facebook Messenger widely used nowadays. More than a wrapper, Opale brings
something very particular, the Opale bubble. You've certainly experienced the Facebook Messenger bubble which you
can play with on your Android smartphone, Opale does the same old trick on your computer. The bubble tells you
how many conversations you've missed, and it blinks when you get incoming messages. It's really useful when you're
multi-tasking and you just don't want to switch between tabs or windows slowly since it's a pain. </p>

<h1 align='center'>
<img alt='Opale-Messenger' src='./images/screen.png'>
</h1>

## Features

- Messenger app native from Facebook
- Bubble which you can interact with and use to show/hide chat and which you can move around.
- Shortcuts which you can use to show/hide the bubble or show/hide the chat.
- Some settings allowing you to save your account informations and to log you automatically in Messenger.
- The bubble keeps always on top so that you can always have it right under the hand.
- Opale Messenger keeps in your system tray, and the bubble can be toggled by right-cliking on it.

## Keyboard shortcuts

Description            | Keys
-----------------------| -----------------------
Toggle bubble          | <kbd>Alt</kbd> <kbd>Q</kbd>
Toggle chat window     | <kbd>Alt</kbd> <kbd>A</kbd>
Unfocus the bubble     | <kbd>Alt</kbd> <kbd>Z</kbd>



## Install

```sh
$ git clone https://github.com/DavidMellul/Opale-Messenger.git
$ cd Opale-Messenger
$ npm install
$ npm start
```

## Platforms supported

Since I'm developing Opale Messenger on Windows, everything should work fine on any Windows OS. <br /><br />
Since Electron is cross-platform, it should also work well on Mac OS X & Linux but I can't ensure it. <br />

I've tested Opale Messenger on Mac OS Sierra thank's to vmware, everything seems alright.<br />
Thank's to <a href="https://github.com/svin83">@svin83</a> who has tested on Linux Mint Mate, Opale works on this Linux distribution and certainly on other distros (**Note: The bubble's background doesn't work well on Linux -> <a href="https://github.com/DavidMellul/Opale-Messenger/issues/2"> see issue</a>**).



## Builds and Installers

<p align="justify">Till now (the 20 January 2017 when I'm writing) the only installer I've been making (with electron-packager and innoSetup) is for Windows 32 bits, so that it works on both operating systems no matter it's architecture is wheter x86 or x64.</p>


<strong>Installer for Windows 32-64 bits : http://dmware.fr/opale/opale_setup.exe</strong> <br />
<strong>DMG for Mac OS 64 bits : http://dmware.fr/opale/opale.dmg</strong> <br />
<strong>For Linux users, simply follow the command-line steps</strong><br />

<strong>Important:  Your antivirus may consider checking the installer and the launcher the first time, nevermind I didn't sign my software, nothing to worry about.</strong>


## Further improvements


I would be glad if someone could give me a feedback or just tell me how I could simply improve. <br />
I would consider being a lot more greatful if someone  could package the app so that users could use Opale Messenger on both Windows and Mac (Linux maybe ?) with an installer. (<strong> ---> Further teamworking on cool projects ?</strong>)

## Bugs and Issues

If you catch any suspect behavior or anything you could simply describe as an "issue" / "bug", please post an issue / pull request about it. 

## Disclaimer 

<strong>Remark 1: I'm a student in computer science, I'm mainly focused on software development, please be constructive and keen on anything you could think is a bad habit since I've almost never experienced web development more than some tricky webdesign and some AJAX (JQuery / JS / PHP). </strong><br /><br />
<strong>Remark 2: I don't believe I'll have time to maintain this project or to make it better since it's purpose was to train cross-platform hybrid software development, any help would be sincerely very appreciated.</strong>

## License

This software is under the MIT License which can be found in the file named as LICENSE.

