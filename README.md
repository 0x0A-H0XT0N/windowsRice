# INDEX

- [Windows10Debloater](##Windows10Debloater)
- [Drivers](##drivers)
- [Firefox*](#firefox)
- [Discord](#discord)
- [Spotify](#spotify)
- [Rainmeter](#rainmeter)
- [JetBrains Mono font](#font)
- [More](#more)

## Windows10Debloater
Get it [here](https://github.com/Sycnex/Windows10Debloater) or run:

```iwr -useb https://git.io/debloat|iex```

## Drivers

- [AMD drivers](https://www.amd.com/en/support)
- [Logitech G HUB](https://www.logitechg.com/en-us/innovation/g-hub.html)
- [Logitech gaming software](https://support.logi.com/hc/en-us/articles/360025298053-Logitech-Gaming-Software): Full auto m16 is a must have
- [MSI Afterburner](https://www.msi.com/Landing/afterburner/graphics-cards): optional

## Firefox

1. [Download](https://www.mozilla.org/en-US/firefox/new/)
2. Sync your account
3. Set it to your default browser
4. [Run ffprofile](https://ffprofile.com/) or [download (my) profile.js]()
5. [Download nighttab config]() and import it

## Discord

1. [Download](https://discord.com/download)
2. [Download betterDiscord](betterdiscord.app/) for **Plugins** & **Themes**
    - **Theme** : [MaterialDiscord](https://betterdiscord.app/theme/MaterialDiscord)
    - **Plugins**

| Plugins | Links|
| --- | --- |
| **BetterVolume** | https://betterdiscord.app/plugin/BetterVolume |
| **CallTimeCounter** | https://betterdiscord.app/plugin/CallTimeCounter |
| **DiscordFreeEmojis** | https://betterdiscord.app/plugin/FreeEmojis |
| **GameActivityToggle** | https://betterdiscord.app/plugin/GameActivityToggle |
| **InvisibleTyping** | https://betterdiscord.app/plugin/InvisibleTyping |
| **NoSpotifyPause** | https://betterdiscord.app/plugin/NoSpotifyPause |
| **ReadAllNotificationsButton** | https://betterdiscord.app/plugin/ReadAllNotificationsButton |
| **ShowHiddenChannels** | https://betterdiscord.app/plugin/ShowHiddenChannels |
| **SpotifyControls** | https://betterdiscord.app/plugin/SpotifyControls |

## Spotify

1. [Download](https://www.spotify.com/us/download/windows/)
2. Run to install spicetify and its plugin and themes:

```
Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression
spicetify
spicetify config extensions webnowplaying.js fullAppDisplay.js popupLyrics.js
spicetify backup apply
cd "$(spicetify -c | Split-Path)\Themes\Dribbblish"
Copy-Item dribbblish.js ..\..\Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme Dribbblish color_scheme nord-dark
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```
**NOTE:** if the above fail (doom on us), here are the links for [spicetify-cli](https://github.com/khanhas/spicetify-cli/releases/) and [dribbblish theme](https://github.com/morpheusthewhite/spicetify-themes/tree/master/Dribbblish), color sheme `nord-dark`, extensions used are: `webnowplaying.js fullAppDisplay.js popupLyrics.js dribbblish.js`

## Rainmeter
![rainmeter + wallpaper engine, plugins used below](https://i.imgur.com/89fHR4a.jpeg "rainmeter + wallpaper engine, plugins used below")
1. [Download](https://www.rainmeter.net/)
2. [Download JaxCore](https://jax-core.github.io/)
    - **Plugins**: **Modularplayers, Modularclocks, Plainext**
    - Download them via the jaxcore interface, config them to your taste

## Font
![Jetbrains mono](https://i.imgur.com/10GUiJ7.png "Jetbrains mono demo from their website")
- [Download](https://www.jetbrains.com/lp/mono/)

## More

- Gaming:
  - [steam](https://store.steampowered.com/about/)
    - wallpaper engine
  - [league of legends](https://signup.na.leagueoflegends.com/en/signup/redownload)
    - [zar.gg](https://zar.gg/)
    - change language
  - [escape from tarkov](https://www.escapefromtarkov.com/)
- [vscode](https://code.visualstudio.com/Download)
  - sync using github account
  - download [git](https://git-scm.com/downloads)
- [github desktop](https://desktop.github.com/)  
- [qbitorrent](https://www.qbittorrent.org/download.php)
- [shareX](https://getsharex.com/downloads/)
- [winRAR](https://1337x.to/torrent/2480318/WinRAR-5-50-English-x84-x64-Universal-Patch-Crackingpatching/)
- [evernote](https://evernote.com/download)
- [todoist](https://todoist.com/downloads/windows)
- [powertoys](https://docs.microsoft.com/en-us/windows/powertoys/install)
- [windows terminal](https://www.microsoft.com/en-US/p/windows-terminal/9n0dx20hk701)
- [gitmind](https://gitmind.com/download)

TODO: ship skins, ship profile.js (firefox), ship nighttab config (firefox), check other rices on workspace
