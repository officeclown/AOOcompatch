# Arkham Origins Online: Extended Cut
[![GitHub commits](https://badgen.net/github/commits/Naereen/Strapdown.js)](https://GitHub.com/Naereen/StrapDown.js/commit/) [![GitHub latest commit](https://badgen.net/github/last-commit/Naereen/Strapdown.js)](https://GitHub.com/Naereen/StrapDown.js/commit/) [![Extended Cut Discord](https://badgen.net/discord/members/csharp)](https://discord.gg/xe4exTyGc7)
###### https://discord.gg/arkhamworkshop
Arkham Origins Online: Extended Cut is an extensive mod for the forgotten online mode of Arkham Origins that intends to rebalance, restore content, and extend the game, turning it into the most enjoyable experience it can be according to it's original blueprint and serving as an "evergreen" experience for Arkham players.
## Installation
> [!IMPORTANT]
>Requires Arkham Origins and the Season Pass to be purchased on Steam, and [Arkham Revived Self Hosted](https://github.com/kiwifruitdev/arkhamrevivedselfhosted)

- Download the latest nightly update by clicking [here](https://github.com/officeclown/AOOcompatch/archive/refs/heads/main.zip) or via pressing the green Code button in the top right then downloading as ZIP`

- Open Arkham Origins' directory by right-clicking it in Steam, and clicking on `Manage` > `Browse Local Files`, then navigate into to the `Online` folder.

- Open the downloaded ZIP file, and drag the `BmGame` and `DLC` folders into the game's directory, overwriting files when it asks.
  
- In the ZIP file, navigate into the `FOR DOCUMENTS` folder and drag the `WB Games` into your windows `Documents` folder, overwriting files when it asks.  

- Follow the instructions on the [Arkham Revived Self Hosted](https://github.com/kiwifruitdev/arkhamrevivedselfhosted) repo to install and set it up.

- You're up! Launch the game and the title screen should say Extended Cut, and you should be able to get past it without error.
  
## Hosting / Joining Games
> [!IMPORTANT]  
> Traditional Steam lobbies are limited and proven unreliable. LAN Emulation allows for more stable connection and is officially supported.
>
> A wired internet connection is recommended for the best experience, but not required.

### LAN Emulation
> [!IMPORTANT]  
> We are currently looking for a cross-platform, free, and preferably ephermeral LAN emulation solution to adopt as standard. If you have any leads, contact us in the discord.
>
> As of now, the community uses [Radmin VPN](https://www.radmin-vpn.com/) (windows only)

#### Hosting / Joining via console.
*It is recommended to run these host commands from a regular lobby, to apply any INI changes and ensure stability*
- To host, press `F10` to open the console and type `start [MAP]?listen?game=bmgame.gdgi[GAMEMODE]`
  - `[MAP]` can be `blackgate`, `chemplant`, `funhouse`, or `robotfactory`
  - `[GAMEMODE]` can be `gangland`, `hunterhunted`, `bethebatman`, or `bethevillain`

- To join, press `F10` and type `start [HOST IP]` where `[HOST IP]` is the address of the host provided by the LAN emulator
  - This can be input before the host's game is up to join as soon as possible. It can also be input well after to join or rejoin mid-game.

- You can optionally be given a specific team upon joining or hosting by appending `?team=[0-2]` to the command. For example, to join as Bane gang, the command would be `start [HOST IP]?team=1`
  - `0`= Jokers, `1` = Banes, `2` = Heroes

## Useful In-Game Commands
#### Host Only
`servertravel [MAP]?game=bmgame.gdgi[GAMEMODE]` - Loads a new game and brings everyone currently connected with you. Players stay on the same teams. Also a convenient way to restart a match with teams situated. Do not add `?listen`!

`playforever` - Disables the match timer and activates supervillain doors.

`kickplayer [0-7]` - Kicks a player from your lobby. The number corresponds to the order of players on your screen, with you (the host) starting at 0. This command is generally useless as the kicked player can just join back, even interupting the start countdown. If you're having problems with belligerent players, host via LAN emulation instead.

#### Anyone

`changeteam [TEAM]` - Change to `joker`, `bane`, or `heroes`. Unfortunately, it kills you and makes you wait for a respawn, losing a reinforcement for the team you're switching from. It's recommended to change teams and then have the host restart the match.

`setcharindex [NUM]` - Change characters instantly. `0` = Batman, `1` = Robin, `2` = Joker, `3` = Joker Thug, `4` = Bane, `5` = Bane Thug

## TODO / Known Issues
*Contributions welcome!*

See the [Issues](https://github.com/officeclown/AOOcompatch/issues) page.

