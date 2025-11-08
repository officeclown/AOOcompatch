# Arkham Origins Online: Extended Cut
###### https://discord.gg/arkhamworkshop
Arkham Origins Online: Extended Cut is an extensive mod for the forgotten online mode of Arkham Origins that intends to rebalance, restore content, and extend the game, turning it into the most enjoyable experience it can be and serving as an "evergreen" experience for Arkham players.
## Installation
> [!IMPORTANT]
>Requires Arkham Origins and the Season Pass to be purchased on Steam, and [Arkham Revived Self Hosted](https://github.com/kiwifruitdev/arkhamrevivedselfhosted)

- Download this repository by pressing the green `Code` button in the top right, and selecting `Download as ZIP`

- Open Arkham Origins' directory by right-clicking it in Steam, and clicking on `Manage` > `Browse Local Files`, then navigate into to the `Online` folder.

- Open the downloaded ZIP file, and drag the `BmGame` and `DLC` folders into the game's directory, overwriting files when it asks.
  
- In the ZIP file, navigate into the `FOR DOCUMENTS` folder and drag the `WB Games` into `Documents`, overwriting files when it asks.  

- Follow the instructions on the [Arkham Revived Self Hosted](https://github.com/kiwifruitdev/arkhamrevivedselfhosted) repo to install and set it up.
  
## Hosting / Joining Games
> [!IMPORTANT]  
> Traditional Steam lobbies are limited and proven unreliable. LAN Emulation allows for more stable connection and is officially supported.
>
> A wired internet connection is recommended for the best experience, but not required.

### LAN Emulation
#### iroh-lan
*[iroh-lan](https://github.com/rustonbsd/iroh-lan) is the software of choice because of its ease of use and cross-platform compatibility.*

- [Download iroh-lan](https://github.com/rustonbsd/iroh-lan/releases) and extract it to an accessible directory.

- Run the program.

- Enter a name for your network and a password. Share these with everyone you want to play with.

- Have everyone press `Join`. It will take a minute, but when it's finished, you'll see everyone connected on the network.

- Move on to Hosting / Joining via console.

#### Hosting / Joining via console.

- To host, press `F10` to open the console and type `start [MAP]?listen?game=bmgame.gdgi[GAMEMODE]`
  - `[MAP]` can be `blackgate`, `chemplant`, `funhouse`, or `robotfactory`
  - `[GAMEMODE]` can be `gangland`, `hunterhunted`, `bethebatman`, or `bethevillain`

- To join, press `F10` and type `start 127.0.0.1`
  - This can be input before the host's game is up to join as soon as possible.

## Useful Commands
#### Host Only
`servertravel [MAP]?game=bmgame.gdgi[GAMEMODE]` - Loads a new game and brings everyone currently connected with you. Players stay on the same teams. Also a convenient way to restart a match with teams situated. Do not add `?listen`!

`playforever` - Disables the match timer and activates supervillain doors.

#### Anyone
`changeteam [TEAM]` - Change to `joker`, `bane`, or `heroes`. Unfortunately, it kills you and makes you wait for a respawn, losing a reinforcement for the team you're switching from. It's recommended to change teams and then have the host restart the match.

`setcharindex [NUM]` - Change characters instantly. `0` = Batman, `1` = Robin, `2` = Joker, `3` = Joker Thug, `4` = Bane, `5` = Bane Thug

## TODO / Known Issues
*Contributions welcome!*

See the [Issues](https://github.com/officeclown/AOOcompatch/issues) page.

