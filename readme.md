
# Awesome MUDs 

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome"/></a>
</p>

> A curated list of [MUD](https://en.wikipedia.org/wiki/MUD) development resources, tools, and apps.

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. You might want to read the complete [awesome](https://github.com/sindresorhus/awesome) list.*

If you want to add anything to this list, please [open an issue](https://opensource.guide/how-to-contribute/#opening-an-issue) or a [pull request](https://opensource.guide/how-to-contribute/#opening-a-pull-request).

## Contents

- [Clients](#clients)
- [Codebases and drivers](#codebases)
- [Tools](#tools)
- [Protocols](#protocols)
- [Community](#community)

## Clients

List of clients you can use to connect to different MUDs, grouped by operating system. Includes a list of MUD protocols the client is compatible with (although can be an incomplete list, help is welcome!)

### Multiplatform

- [Mudlet](https://www.mudlet.org/) [Linux, MacOS, Windows], [GMCP, MSSP, MSP, ATCP, Aardwolf's 102, MSDP, MXP]
- [Blightmud](https://github.com/LiquidityC/Blightmud) [Linux, MacOS], [TLS, GMCP, MSDP, MCCP2]
- [Tintin++](https://tintin.mudhalla.net/) [Android, iOS, Linux, MacOS, Windows] [GMCP, MCCP, MCCP3, MSDP, MSLP, MSSP, MTTS, MMCP, NAWS, MNES]
- [KildClient](https://www.kildclient.org) [Linux, Windows], [SSL, MCCP, MCCP2, MMCP, zChat]
- [TinyFugue](https://tinyfugue.sourceforge.net/) [Linux, MacOS, Windows], [MCCP]
- [TinyFugue Rebirth](https://github.com/ingwarsw/tinyfugue) [Linux, MacOS, Windows], [GMCP, ATCP]
- [AxMud](https://axmud.sourceforge.io/) [Linux, Windows], [MXP, GMCP, MSDP, MNES, MTTS]

### Windows

- [Avalon Mud Client](https://github.com/blakepell/AvalonMudClient)
- [CMUD](http://www.zuggsoft.com/index.php?p=cmud) (free trial, paid app) [MXP, MSP, MCP, MCCP, ATCP]
- [zMUD 7.21](http://forums.zuggsoft.com/index.php?page=4&action=file&file_id=65) (free trial, paid app, last version of CMUD precursor) [MXP, MCP, MCCP]
- [zMUD 3.62](http://forums.zuggsoft.com/index.php?page=4&action=file&file_id=18) (last free version of zMUD, very old)
- [Portal](http://gameaxle.com/)
- [MUSHclient](http://www.gammon.com.au/mushclient/mushclient.htm) [MXP, MCCP, MMCP, MTTS]
- [BeipMU](https://beipdev.github.io/BeipMU/) [TLS, MCMP]
- [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/) (generic telnet and ssh client, without MUD features)

### MacOS

- [Atlantis](https://riverdark.net/atlantis/) 

### Linux

- [GnomeMUD](https://gitlab.gnome.org/GNOME/gnome-mud) [MSP, MCCP2]

### Mobile

- [BlowTorch](https://bt.happygoatstudios.com/) [Android], [MCCP]
- [MUDRammer](https://github.com/splinesoft/MUDRammer) [iOS]

### Web Clients

- [MudPortal](https://github.com/plamzi/MUDPortal-Web-App) (web client and proxy server ws/telnet) [MCCP, MXP, MSDP, GMCP, ATCP, MTTS]
- [mud-web-client](https://github.com/maldorne/mud-web-proxy/) (fork from MudPortal, just the web client, updated to allow wss)
- Mudslinger ([fork](https://github.com/ryanberckmans/mudslinger), [fork](https://github.com/Xiija/mudslinger)) (original code seems to be gone, the links are forks) (web client and proxy server) [MXP]
- [Grapevine](https://github.com/oestrich/grapevine)

### Web Proxies

Server apps that allow a web client to connect to a mud/telnet server:

- [mud-web-proxy](https://github.com/maldorne/mud-web-proxy/) (fork from MudPortal, just the proxy server, updated to allow wss/telnet)
- [websocket-to-tcp-tunnel](https://github.com/ChatTheatre/websocket-to-tcp-tunnel) (ChatTheatre proxy server, ws/telnet)

## Protocols 

Some info taken from the [tintin/mudhalla protocols and standards documentation](https://tintin.mudhalla.net/protocols/). The [Mudlet wiki](https://wiki.mudlet.org/w/Main_Page) has a main page about all the [protocols supported](https://wiki.mudlet.org/w/Manual:Supported_Protocols) that could be useful too.

### Generic protocols for remote connections

#### Character Mode

Directly transmit the mud client's input, required for BBSes, \*NIX servers, Roguelike MUDs, and interaction with other console software.

#### TELNET

Connect to \*NIX servers and BBSes using TELOPT negotiations.

#### VT100

Displays both client and server side text interfaces.

#### NAWS

*Negotiate About Window Size*. Sends the mud client's window size to the server. [RFC 1073](https://www.rfc-editor.org/rfc/rfc1073).

### Specific protocols for MUDs

There are two **RFCs** about telnet negotiation: [854](https://www.rfc-editor.org/rfc/rfc854.html) and [855](https://www.rfc-editor.org/rfc/rfc855.html). Some of the next protocols are implemented as telnet options, expanding on these two.

#### GMCP

*Generic Mud Communication Protocol*. GMCP is implemented as a Telnet option. Uses JSON syntax to define structured and typed data.

- [Tintin documentation](https://tintin.mudhalla.net/protocols/gmcp/).
- [IronRealms documentation](https://www.ironrealms.com/gmcp-doc).
- [IronRealms Nexus documentation](https://nexus.ironrealms.com/GMCP).
- [GMCP Additions](https://github.com/keneanung/GMCPAdditions).
- [Mudlet documentation for Discord](https://wiki.mudlet.org/w/Standards:Discord_GMCP).

#### MCCP

*Mud Client Compression Protocol* version 2 and 3. MCCP2 is implemented as a Telnet option. Allows a MUD server to compress output to the receiving client using the zlib compression library. Created in 1998, MCCP version 2 was created in 2000. In 2019 MCCP version 3 was created as a separate protocol.

- [Tintin documentation](https://tintin.mudhalla.net/protocols/mccp/)
- [MUSHclient notes](http://www.gammon.com.au/mushclient/mccp.htm).

#### MSDP

*Mud Server Data Protocol*. MSDP is implemented as a Telnet option. Developed in 2009, provides a standardized way to define typeless variables, arrays, tables, and commands. MSDP over [GMCP](#gmcp) offers standardized generic event handling besides sending structured data.

- [Tintin documentation](https://tintin.mudhalla.net/protocols/msdp/).

#### MSLP

*Mud Server Link Protocol*. Allows the creation of clickable links in the client side. MSLP is negotiated by using the [MTTS](#mtts) standard.

- [Tintin documentation](https://tintin.mudhalla.net/protocols/mslp/).

#### MSSP

*Mud Server Status Protocol*. MSSP is implemented as a Telnet option. Protocol for MUD crawlers to gather detailed information about a MUD, including dynamic information like boot time and the current amount of online players. See also [GSGP](#gsgp).

- [Tintin documentation](https://tintin.mudhalla.net/protocols/mssp/)
- [MudVerse info about the protocol](https://www.mudverse.com/mssp).

#### MTTS

*Mud Terminal Type Standard*. Transparant and straight forward standard for Mud Clients to communicate their terminal capabilities. See also [MNES](#mnes).

- [Tintin documentation](https://tintin.mudhalla.net/protocols/mtts/).

#### MMCP

*Mud Master Chat Protocol* for instant messaging and file transfers over private P2P connections. Is a decentralized chat protocol which allows MUD clients to communicate with each other over a TCP/IP connection.

- [MUSHclient compatible feature](http://www.gammon.com.au/mushclient/chat.htm).

#### MXP

*MUD eXtension Protocol*.

- [Zuggsoft specification](http://www.zuggsoft.com/zmud/mxp.htm). 
- [MUSHclient complimentary notes](http://www.gammon.com.au/mushclient/mxp.htm).

#### MSP

*MUD Sound Protocol*.

- [Zuggsoft specification](http://www.zuggsoft.com/zmud/msp.htm).

#### MCMP

*MUD Client Media Protocol*. A standard for loading, playing and stopping media files with MUD clients over GMCP.

- [Mudlet documentation](https://wiki.mudlet.org/w/Standards:MUD_Client_Media_Protocol).

#### zChat

Chat format.

#### GSGP 

[*Game Scry Game Protocol*](https://game-scry.online/about). GSGP is a standardized JSON structure which you can make available for GameScry or other sites to ping for real-time data about a game, its active players, leaderboards, etc.

#### ATCP

*Achaea Telnet Client Protocol*. Using TELNET code 200, was implemented by cMUD in 2008. In 2010 evolved to ATCP2 using TELNET code 201. Was later renamed to [GMCP](#gmcp). Achaea, Aardwolf, MUME, Avatar, Gensis, and MUSHclient provide package definitions modeled after the ATCP2 draft.

#### Aardwolf's 102

Similar to ATCP, Aardwolf includes a hidden channel of information that you can access.

- [Mudlet documentation](https://wiki.mudlet.org/w/Manual:Supported_Protocols#Aardwolf.E2.80.99s_102_subchannel)


#### MNES

*Mud New Environment Standard*. Implemented as a Telnet option. Seeks to supplement [MTTS](#mtts) by providing a straightforward way to use the NEW-ENVIRON telnet option to exchange and update various client and server settings.

- [Tintin documentation](https://tintin.mudhalla.net/protocols/mnes/).

#### MMP

*Mud Mapping Protocol*. IronRealms protocol as a way to export our in game map data so that clients (or players) can easily access and download this data.

- [Mudlet basic documentation](https://wiki.mudlet.org/w/Standards:MMP).

## Community

- [r/MUD](https://www.reddit.com/r/MUD). Reddit's MUD subreddit.
- [Mud Portal](http://www.mudportal.com/). MUD listing and forums.
- [Mud Bytes](http://www.mudbytes.net/). MUD listing and forums.
- [Top Mud Sites](http://www.topmudsites.com/). Defunct MUD listing, now read-only.
- [The Mud Connector](http://www.mudconnect.com/). MUD listing.
- [MudVerse](https://www.mudverse.com). MUD listing.
- [Grapevine](https://grapevine.haus/). MUD listing and web client.
- [Game Scry](https://game-scry.online/browse/mud/?ord=popular). MUD listing.
- [The MUD Coders Guild](https://mudcoders.com). Slack community.
- [The MUD Coders Guild Awesome-Mud list](https://github.com/mudcoders/awesome-mud). Awesome list, in the same fashion as this one.
- [Titans of Text](https://www.titansoftext.com/). Podcast (defunct?).
- [Mudhalla](https://mudhalla.net/). Home of the tintin client, MUD listing, protocols documentation.
- [Mudlet wiki](https://wiki.mudlet.org/w/Main_Page). Protocols documentation.
