This repo modifies the lyrics-plus custom app for spicetify to include romanization in karaoke mode and some other changes.

### Installation 

These are instructions to install in Windows, other platforms should be similar (see spicetify installation of custom apps)
- Follow installation instructions for spicetify [Installation](https://spicetify.app/docs/getting-started)
- Copy contents of CustomApps/lyrics-plus folder to the CustomApps folder of your installation folder (typically found in %appData%)
- Run spicetify apply on PowerShell 

### Features and Changes (wrt original spicetify)

- Chinese Romanization (Simplified+Pinyin)  
- Romanization in Karaoke Mode
- Animation for Synced mode (line interpolation)
- Uses Korean RR transcription as opposed to transliteration 
- Auto refreshes Musixmatch token (30 min cooldown)

### Known Issues

-The pinyin ruby (and the furigana ruby) is desynced with respect to the original. There is an ad-hoc manual sync attempt, but it is still desynced


### Disclaimer
This mod was mostly made using Github Copilot with Opus 4.5 and Gemini 3 Pro. There was plenty of manual checking of lines of code and reprompting but the bulk of it was done using the agent mode of Copilot.
This was only tested on a Windows 11 machine.


Reproduced below is the Readme for Spicetify
<h3 align="center"><a href="https://spicetify.app/"><img src="https://i.imgur.com/iwcLITQ.png" width="600px"></a></h3>
<p align="center">
  <a href="https://goreportcard.com/report/github.com/spicetify/cli"><img src="https://goreportcard.com/badge/github.com/spicetify/cli"></a>
  <a href="https://github.com/spicetify/cli/releases/latest"><img src="https://img.shields.io/github/release/spicetify/cli/all.svg?colorB=97CA00&label=latest%20version"></a>
  <a href="https://github.com/spicetify/cli/releases"><img src="https://img.shields.io/github/downloads/spicetify/cli/total.svg?colorB=97CA00&label=total%20downloads"></a>
  <a href="https://discord.gg/VnevqPp2Rr"><img src="https://img.shields.io/discord/842219447716151306?label=chat&logo=discord&logoColor=discord"></a>
</p>

---

Command-line tool to customize the official Spotify client.
Supports Windows, MacOS and Linux.

<img src=".github/assets/logo.png" alt="img" align="right" width="560px" height="400px">

### Features

- Change colors across the User Interface
- Inject CSS for advanced customization
- Inject Extensions to extend functionalities, manipulate UI and control player
- Inject Custom Apps
- Make yourself in control of the Spotify client

### Links

- [Installation](https://spicetify.app/docs/getting-started)
- [Basic Usage](https://spicetify.app/docs/getting-started#basic-usage)

---

### Code Signing Policy

Free code signing provided by [SignPath.io](https://signpath.io), certificate by [SignPath Foundation](https://signpath.org/).
