
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

- [Mudlet](https://www.mudlet.org/) [Linux, MacOS, Windows], [GMCP, MSSP, MSP, ATCP, Aardwolfs 102, MSDP, MXP]
- [Blightmud](https://github.com/LiquidityC/Blightmud) [Linux, MacOS], [TLS, GMCP, MSDP, MCCP2]
- [Tintin++](https://tintin.mudhalla.net/) [Android, iOS, Linux, MacOS, Windows] [GMCP, MCCP, MSDP, MSLP, MSSP, MTTS, MMCP, NAWS]
- [KildClient](https://www.kildclient.org) [Linux, Windows], [SSL, MCCP, MCCP2, MudMaster, zChat]
- [TinyFugue](https://tinyfugue.sourceforge.net/) [Linux, MacOS, Windows], [MCCP]
- [TinyFugue Rebirth](https://github.com/ingwarsw/tinyfugue) [GMCP, ATCP]

### Windows

- [Avalon Mud Client](https://github.com/blakepell/AvalonMudClient)
- [CMUD](http://www.zuggsoft.com/index.php?p=cmud) (free trial, paid app) [MXP, MSP, MCP, MCCP, ATCP]
- [zMUD 7.21](http://forums.zuggsoft.com/index.php?page=4&action=file&file_id=65) (free trial, paid app, last version of CMUD precursor) [MXP, MCP, MCCP]
- [zMUD 3.62](http://forums.zuggsoft.com/index.php?page=4&action=file&file_id=18) (last free version of zMUD, very old)
- [Portal](http://gameaxle.com/)
- [MUSHclient](http://www.gammon.com.au/mushclient/mushclient.htm) [MXP, MCCP]
- [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/) (generic telnet and ssh client, without MUD features)

### MacOS

- [Atlantis](https://riverdark.net/atlantis/) 

### Linux

- [GnomeMUD](https://gitlab.gnome.org/GNOME/gnome-mud) [MSP, MCCP2]

### Mobile

- [BlowTorch](https://bt.happygoatstudios.com/) [Android], [MCCP]
- [MUDRammer](https://github.com/splinesoft/MUDRammer) [iOS]

### Web Clients

- [MudPortal](https://github.com/plamzi/MUDPortal-Web-App) (web client and proxy server ws/telnet) [MCCP, MXP, MSDP, GMCP, ATCP]
- [mud-web-client](https://github.com/maldorne/mud-web-proxy/) (fork from MudPortal, just the web client, updated to allow wss)
- Mudslinger ([fork](https://github.com/ryanberckmans/mudslinger), [fork](https://github.com/Xiija/mudslinger)) (original code seems to be gone, the links are forks) (web client and proxy server) [MXP]
- [Grapevine](https://github.com/oestrich/grapevine)

### Web Proxies

Server apps that allow a web client to connect to a mud/telnet server:

- [mud-web-proxy](https://github.com/maldorne/mud-web-proxy/) (fork from MudPortal, just the proxy server, updated to allow wss/telnet)
- [websocket-to-tcp-tunnel](https://github.com/ChatTheatre/websocket-to-tcp-tunnel) (ChatTheatre proxy server, ws/telnet)

## Protocols 

### Generic protocols for remote connections

#### Character Mode

Directly transmit the mud client's input, required for BBSes, \*NIX servers, Roguelike MUDs, and interaction with other console software.

#### TELNET

Connect to \*NIX servers and BBSes using TELOPT negotiations.

#### VT100

Displays both client and server side text interfaces.

#### NAWS

**Negotiate About Window Size**. Sends the mud client's window size to the server. [RFC 1073](https://www.rfc-editor.org/rfc/rfc1073).

### Specific protocols for MUDs

#### GMCP

**Generic Mud Communication Protocol**.

#### MCCP

**Mud Client Compression Protocol** version 2 and 3. 

- [MUSHclient notes](http://www.gammon.com.au/mushclient/mccp.htm).
- There are two **RFCs** about telnet negotiation: [854](https://www.rfc-editor.org/rfc/rfc854.html) and [855](https://www.rfc-editor.org/rfc/rfc855.html).

#### MSDP

**Mud Server Data Protocol**.

#### MSLP

**Mud Server Link Protocol**. Allows the creation of clickable links client side as well.

#### MSSP

**Mud Server Status Protocol**.

#### MTTS

**Mud Terminal Type Standard**.

#### MMCP

**Mud Master Chat Protocol** for instant messaging and file transfers over private P2P connections.

#### MXP

**MUD eXtension Protocol**.

- [Zuggsoft specification](http://www.zuggsoft.com/zmud/mxp.htm). 
- [MUSHclient complimentary notes](http://www.gammon.com.au/mushclient/mxp.htm).

#### MSP

**MUD Sound Protocol**.

- [Zuggsoft specification](http://www.zuggsoft.com/zmud/msp.htm).

#### MudMaster

**Chat format**.

- [MUSHclient compatible feature](http://www.gammon.com.au/mushclient/chat.htm).

#### zChat

**Chat format**.
