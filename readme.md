
# Awesome MUDs 

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome"/></a>
</p>

> A curated list of [MUD](https://en.wikipedia.org/wiki/MUD) development resources, tools, and apps.

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*

If you want to add anything to this list, please [open an issue](https://opensource.guide/how-to-contribute/#opening-an-issue) or a [pull request](https://opensource.guide/how-to-contribute/#opening-a-pull-request).

## Contents

- [Clients](#clients)
- [Codebases and drivers](#codebases-and-drivers)
- [Tools](#tools)
- [Protocols](#protocols)
- [People](#people)
- [Community](#community)
- [Papers](#papers)

## Clients

List of clients you can use to connect to different MUDs, grouped by operating system. Includes a list of [MUD protocols](#protocols) the client is compatible with (*although it can be an incomplete list, help is welcome!*)

### Multiplatform

- [Mudlet](https://www.mudlet.org/) [Linux, MacOS, Windows], [GMCP, MSSP, MCMP, MSP, ATCP, Aardwolf's 102, MSDP, MXP, MMP, Discord GMCP, GMCP Authentication]
- [Blightmud](https://github.com/LiquidityC/Blightmud) [Linux, MacOS], [TLS, GMCP, MSDP, MCCP2]
- [Tintin++](https://tintin.mudhalla.net/) [Android, iOS, Linux, MacOS, Windows] [GMCP, MCCP, MCCP3, MSDP, MSLP, MSSP, MTTS, MMCP, NAWS, MNES]
- [KildClient](https://www.kildclient.org) [Linux, Windows], [SSL, MCCP, MCCP2, MMCP, zChat]
- [TinyFugue](https://tinyfugue.sourceforge.net/) [Linux, MacOS, Windows], [MCCP]
- [TinyFugue Rebirth](https://github.com/ingwarsw/tinyfugue) [Linux, MacOS, Windows], [GMCP, ATCP]
- [AxMud](https://axmud.sourceforge.io/) [Linux, Windows], [MXP, GMCP, MSDP, MNES, MTTS]
- [Tortilla MUD client](https://github.com/tmud/tortilla) (completely in russian) [Windows XP and above, Linux and MacOS via Wine], [MCCP, MSDP, MTTS]
- [KBTin](https://github.com/kilobyte/kbtin) (Tintin++ fork) [Linux, MacOS, BSD] [MCCP, TLS]

### Windows

- [Avalon Mud Client](https://github.com/blakepell/AvalonMudClient)
- [CMUD](http://www.zuggsoft.com/index.php?p=cmud) (free trial, paid app) [MXP, MSP, MCP, MCCP, ATCP]
- [zMUD 7.21](http://forums.zuggsoft.com/index.php?page=4&action=file&file_id=65) (free trial, paid app, last version of CMUD precursor, unmaintained) [MXP, MCP, MCCP]
- [zMUD 3.62](http://forums.zuggsoft.com/index.php?page=4&action=file&file_id=18) (last free version of zMUD, very old, unmaintained)
- [Portal](http://gameaxle.com/)
- [MUSHclient](http://www.gammon.com.au/mushclient/mushclient.htm) [MXP, MCCP, MMCP, MTTS]
- [BeipMU](https://beipdev.github.io/BeipMU/) [TLS, MCMP]
- [WinTin](http://wintin.org/) (supports Tintin++ scripting language, unmaintained in its webpage, but [Tintin++ releases](https://github.com/scandum/tintin/releases) has updated windows versions)
- [GMud32](https://valiant8086.com/games/muds/gmud/) (very old, unmaintained)
- [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/) (generic telnet and ssh client, without MUD features)

### MacOS

- [Atlantis](https://riverdark.net/atlantis/)
- [MudClient.app](https://mudclient.app/) (free trial, paid app) [MCCP]

### Linux

- [GnomeMUD](https://gitlab.gnome.org/GNOME/gnome-mud) [MSP, MCCP2]
- [KMuddy](http://www.kmuddy.com/) [MCCP, MSP, MXP]

### Mobile

- [BlowTorch](https://bt.happygoatstudios.com/) [Android], [MCCP]
- [MUDRammer](https://github.com/splinesoft/MUDRammer) [iOS]

### Abandoned projects

Links to old abandoned open source mud client projects, maybe something useful in there:

- [MudWalker](http://mudwalker.cubik.org/) (unmaintained, abandoned) [MacOS] [MCP]
- [GGMud](http://www.ggsoft.org/ggmud/) (unmaintained, abandoned) [Linux, MacOS, Windows] [MCCP]
- [Lyntin](https://lyntin.sourceforge.net/) (unmaintained, abandoned) [Made in Python, probably multiplatform]
- [XpertMud](https://xpertmud.sourceforge.net/) (unmaintained, abandoned) [Linux, Windows]

### Web Clients

- [MudPortal](https://github.com/plamzi/MUDPortal-Web-App) (web client and proxy server ws/telnet) [MCCP, MXP, MSDP, GMCP, ATCP, MTTS]
- [mud-web-client](https://github.com/maldorne/mud-web-proxy/) (fork from MudPortal, just the web client, updated to allow wss)
- Mudslinger ([fork](https://github.com/ryanberckmans/mudslinger), [fork](https://github.com/Xiija/mudslinger)) (original code seems to be gone, the links are forks) (web client and proxy server) [MXP]
- [Grapevine](https://github.com/oestrich/grapevine)
- [DecafMUD](https://github.com/stendec/DecafMUD/) (very old, unmaintained)

### Web Proxies

Server apps that allow a web client to connect to a mud/telnet server:

- [mud-web-proxy](https://github.com/maldorne/mud-web-proxy/) (fork from MudPortal, just the proxy server, updated to allow wss/telnet)
- [websocket-to-tcp-tunnel](https://github.com/ChatTheatre/websocket-to-tcp-tunnel) (ChatTheatre proxy server, ws/telnet)

## Codebases and drivers

- [Full chronology](https://en.wikipedia.org/wiki/Chronology_of_MUDs) of the most important MUDs and codebases in the Wikipedia.
- [Online World Timeline](https://www.raphkoster.com/gaming/mudtimeline.shtml) on Raph Koster's web page, shows a chronology of everything related to online worlds, including MUDs.

### MUD1

[MUDs](https://en.wikipedia.org/wiki/MUD) evolved from the [original game](https://en.wikipedia.org/wiki/MUD1) (created in 1978 in the University of Essex by Roy Trubshaw and Richard Bartle), in _families_ of related games, mainly based in the technologies used to implement them.

- Original [MUD1 source code](https://github.com/PDP-10/MUD1) for the DEC PDP-10 mainframe.
- Chronology of the [original MUD variants](https://mud.co.uk/richard/incarns.htm), by Richard Bartle.
- [British Legends](http://www.british-legends.com), home of the MUD1 game.

### AberMUD

Created in 1987 at the Aberystwyth University, was the first popular open source MUD. Ported to C in 1988 in AberMUD2, and published as GPL in AberMUD V. It inspired the next three major codebases: [TinyMUD](#TinyMUD), [LPMud](#LPMud) and [DikuMUD](#DikuMUD).

- [Family tree](https://en.wikipedia.org/wiki/MUD_trees#AberMUD_family_tree).
- [Some documentation and source code](http://ftp.linux.org.uk/pub/linux/alan/Software/Games/AberMUD5/) for AberMUD5 in http://ftp.linux.org.uk.

### TinyMUD

Released by Jim Aspnes in 1989, running on Unix and written in C.

- [Family tree](https://en.wikipedia.org/wiki/MUD_trees#TinyMUD_family_tree).
- [Source code](https://archive.org/details/tinymud-1.5.5) of v1.5.5 on the Internet Archive.

_MU*_, sometimes called *Tiny family*, is an abbreviation which refers collectively to a family comprising: TinyMUD, MUSH, MOO, TinyMUCK. It has [its own wiki](https://mu.fandom.com).

#### [MUSH](https://en.wikipedia.org/wiki/MUSH)

Main variations: PennMUSH, TinyMUSH, [TinyMUX](http://www.tinymux.org/) and [RhostMUSH](https://code.google.com/p/rhostmush/).

- Lots of code and documentation on [MUSHCode](http://www.mushcode.com/).

#### [TinyMUCK](https://en.wikipedia.org/wiki/TinyMUCK)

Written by Stephen White in 1990. Later that year, he released [MOO](#moo).

- [MUCK Manual](http://www.rdwarf.com/users/mink/muckman/) ([alt link](https://fuzzball-muck.github.io/muckman/)).
- [Fuzzball MUCK server](https://github.com/fuzzball-muck/fuzzball) source code.

#### [MOO](https://en.wikipedia.org/wiki/MOO)

Written by Stephen White in 1990, derived from TinyMUCK, with object oriented design. Pavel Curtis did substantial modifications to MOO code, creating LambdaMOO, which was hosted at Xerox PARC.

- Documentation in the [moo-cows](http://www.moo-cows.com/) web.
- List of MOO games in [moolist](http://www.moolist.com/).
- [LambdaMOO](https://en.wikipedia.org/wiki/LambdaMOO) was created in 1990 by Pavel Curtis ([source code in sourceforge](https://sourceforge.net/projects/lambdamoo/)).
- [Stunt](http://stunt.io/), a set of extensions to the LambdaMOO server.
- [ToastStunt](https://github.com/lisdude/toaststunt), forked from stunt and being worked on.
- [LambdaMOO Programming](https://github.com/sevenecks/lambda-moo-programming) repository, collects and updates numerous MOO guides in one place, from the original server to ToastStunt. 

### LPMud

Released by Lars Pensjö in 1989, trying to combine the extensibility of [TinyMUD](#TinyMUD) with the adventures of [AberMUD](#AberMUD). He designed the LPC language (from Lars Pensjö C) and the *driver/interpreter*, trying to make the process of extending the game easier, separating the Mud in two different parts: the **driver** which acts as a *virtual machine/interpreter/runtime* (programmed in C), and the **mudlib** which implements the game code (programmed in LPC and executed by the *driver*). Some old games still being played today started here: [Genesis](https://www.genesismud.org/), [BatMUD](https://www.bat.org/), [NannyMUD](https://www.lysator.liu.se/nanny/), [Discworld](http://discworld.starturtle.net), etc.

- [Family tree](https://en.wikipedia.org/wiki/MUD_trees#LPMud_family_tree).
- [LPMud Timeline 1979-1995](http://web.archive.org/web/20121230064031/http://www.rpgmud.com:80/lpmud_timeline.htm), by George Reese (Descartes of Borg), in the now defunct rpgmud.com (link to the *Internet Archive Wayback Machine*). [Stored in this repository](./docs/lpmuds/lpmud-timeline.md).
- [LPMud FAQ (1995)](http://lpmuds.net/lpmud_faq.html), by George Reese (Descartes of Borg). Link to the [lpmuds.net](http://lpmuds.net/) web. Also [stored in this repository](./docs/lpmuds/lpmud-faq.md) converted to markdown.

Some language documentation:

- [LPC documentation](http://www.ldmud.eu/lpc-intro.html) for LDMud.
- [LPC Basics](https://www.lysator.liu.se/nanny/wiz/lpc/basic/Contents.html) and [Intermediate LPC](https://www.lysator.liu.se/nanny/wiz/lpc/intermediate/Contents.html), written for LPMud by George Reese (Descartes of Borg).
- [Self Conscious DGD](https://noahgibbs.github.io/self_conscious_dgd/), book about LPC for DGD written by [Noah Gibbs](https://codefol.io/).

#### Drivers

##### LPMud

After Lars Pensjö retired from LPMud development, Joern Rennecke (Amylaar) took over development of the LPMud driver and produced the 3.2 series of LPMud. This is sometimes known as the Amylaar driver.

- Source code not found in any repository, but the [MUDBytes files archives](http://mudbytes.net/files/tags/LPMud/) seems to have some versions uploaded.

##### MudOS

Another group of people started working from the LPMud v3.0 in 1992, and renamed it to MudOS, which will have several versions until 2003. (_mudos.org_, its original webpage is defunct, but you can find some of the last versions in the [maldorne repository](https://github.com/maldorne/mudos), and use them with Docker). It could use sockets at mudlib level (with LPC code), which allowed to create a TCP intermud network. This protocol evolved until [Intermud 3](#Intermud).

- [Code repository](https://github.com/maldorne/mudos) (fork).
- [History of MudOS](./docs/lpmuds/mudos-history.md) (recovered file from some driver distributions).

##### FluffOS

In parallel to the last versions of Mudos (the last one was v22.2b14, 2003), the Discworld developers forked it and renamed it as [FluffOS](http://fluffos.info/). [Still maintained](https://github.com/fluffos/fluffos). It had versions 1.0 to 1.36, 2.0 to 2.27, and since 3.0 the maintainer is [Yucong Sun](https://github.com/thefallentree), and major versions has been released with the names FluffOS 2017 and 2019.

- [Official code repository](https://github.com/fluffos/fluffos).

##### LDMud

Lars Düning continued the development of the LPMud driver renaming it to [LDMud](http://www.ldmud.eu) (but keeping the Amylaar version numbers, so starting with 3.2.2). LDMud is still [being maintained](https://github.com/ldmud/ldmud).

- [Official code repository](https://github.com/ldmud/ldmud).

##### CD MUD

- [Code repository](https://github.com/cotillion/cd-gamedriver).

##### DGD

Felix 'Dworkin' Croes developed in 1993 [DGD](http://www.dworkin.nl/dgd/) (Dworkin Game/Generic Driver), not derived from LPMud (so not using the same license) but compatible with LPC language. [Still maintained](https://github.com/dworkin/dgd), and open source since v1.4 (2010).

- [Official code repository](https://github.com/dworkin/dgd).
- [Self Conscious DGD](https://noahgibbs.github.io/self_conscious_dgd/), book about LPC for DGD written by [Noah Gibbs](https://codefol.io/).

### DikuMUD

Inspired by [AberMUD](#AberMUD) and [LPMud](#LPMud), created in 1990/91 at DIKU (*Datalogisk Institut Københavns Universitet* —the department of computer science at the University of Copenhagen—) in Copenhagen, Denmark.  

- [Family tree](https://en.wikipedia.org/wiki/MUD_trees#DikuMUD_family_tree).
- [DikuMUD.com](https://dikumud.com/).
- [DikuMUD Wiki](https://wiki.dikumud.net/).
- [DikuMUD gamma source code](https://github.com/Seifert69/DikuMUD-Gamma) (the original release), [DikuMUD alpha source code](https://github.com/Seifert69/DikuMUD) (newer than gamma), and [DikuMUD2 source code](https://github.com/Seifert69/DikuMUD2), all with LGPL license.
- [DikuMUD III source code](https://github.com/Seifert69/DikuMUD3), using HTML, websockets and Discord integration, being worked on, LGPL license.
- The [DikuMUD Omnibus Github repository](https://github.com/DikuMUDOmnibus) stores more than a hundred Diku-related software projects.

Some well-known derivatives of DikuMUD: [CircleMUD](https://muds.fandom.com/wiki/CircleMUD) ([web](https://www.circlemud.org/), [source](https://www.circlemud.org/pub/CircleMUD/)), [MERC](https://muds.fandom.com/wiki/Merc), [Envy](https://muds.fandom.com/wiki/Envy), [ROM](https://muds.fandom.com/wiki/ROM), [SMAUG](https://muds.fandom.com/wiki/SMAUG), [GodWars](https://muds.fandom.com/wiki/GodWars), [AwakeMUD](https://muds.fandom.com/wiki/AwakeMUD) ([web](https://www.awakemud.com/), [source](https://github.com/luciensadi/AwakeMUD)).

### Modern drivers

Some information about some modern *drivers/game engines/codebases* created long time after the original _MU*_ games.

#### Evennia

Created by Greg Taylor in 2006, Samuel "Griatch" Regandell took over the project in 2011. Modern library for creating online multiplayer text games in pure Python. Coding is done using normal Python modules imported into the server at runtime. BSD license.

- [Web](https://www.evennia.com/), [Github project](https://github.com/evennia/evennia), [discussion forum](https://github.com/evennia/evennia/discussions), [Discord server](https://discord.com/invite/AJJpcRUhtF).

## Protocols 

- Some info taken from the [tintin/mudhalla protocols and standards documentation](https://tintin.mudhalla.net/protocols/). 
- The [Mudlet wiki](https://wiki.mudlet.org/w/Main_Page) has a main page about all the [supported protocols](https://wiki.mudlet.org/w/Manual:Supported_Protocols) that could be useful too.
- CryoSphere MUD has a [page about MUD client/server interaction](http://cryosphere.net/mud-protocol.html) with some more useful information.

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

#### MCP

*Mud Client Protocol*. An attempt to provide a standard message format on which to build MUD-based client-server applications.

- [LambdaMOO documentation](http://www.moo.mud.org/mcp/index.html).

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

*MUD Client Media Protocol*. A standard for loading, playing and stopping media files with MUD clients over GMCP that is intended to modernise MSP.

- [Mudlet documentation](https://wiki.mudlet.org/w/Standards:MUD_Client_Media_Protocol).

#### zChat

Chat format. Similar to [MMCP](#mmcp) but not compatible.

- [Zuggsoft specification](https://www.zuggsoft.com/zchat/zchatprot.htm).

#### GSGP 

[*Game Scry Game Protocol*](https://game-scry.online/about). GSGP is a standardized JSON structure which you can make available for GameScry or other sites to ping for real-time data about a game, its active players, leaderboards, etc. See also [MSSP](#mssp).

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

#### Intermud

Communication protocol. TO DO.

## People

- Roy Trubshaw, co-creator of [MUD1](#MUD1).
- [Richard Bartle](https://en.wikipedia.org/wiki/Richard_Bartle), co-creator of [MUD1](#MUD1), writer of [Designing Virtual Worlds](https://mud.co.uk/dvw/). [Personal page](https://mud.co.uk/).
- [Alan Cox](https://en.wikipedia.org/wiki/Alan_Cox_(computer_programmer)), co-creator of [AberMUD](#AberMUD) and Linux kernel maintainer for several years.
- [Michael Seifert](https://en.wikipedia.org/wiki/Michael_Seifert_(programmer)), co-creator of [DikuMUD](#DikuMUD).
- [Pavel Curtis](https://en.wikipedia.org/wiki/Pavel_Curtis), creator of LambdaMOO.

## Community

### Discussion

- [r/MUD](https://www.reddit.com/r/MUD), Reddit's MUD subreddit.
- [The MUD Discord](https://discord.gg/zuz4D8s).
- [The MUD Coders Guild](https://mudcoders.com), 2016-2020 blog and Slack community.

### Player competition

- [Deathlogs](https://deathlogs.com/). MUD PvP logs.

### MUD listings

- [Grapevine](https://grapevine.haus/), MUD listing and web client.
- [Vineyard](https://vineyard.haus/), MUD hosting service, listing their hosted MUDs.
- [Game Scry](https://game-scry.online/browse/mud/?ord=popular), MUD listing.
- [Mud Portal](http://www.mudportal.com/), MUD listing and forums.
- [Mud Bytes](http://www.mudbytes.net/), MUD listing and forums.
- [Top Mud Sites](http://www.topmudsites.com/), defunct MUD listing, now read-only.
- [The Mud Connector](http://www.mudconnect.com/), MUD listing.
- [MudVerse](https://www.mudverse.com), MUD listing.
- [MUD MSSP Stats](https://iberia.jdai.pt/mudstats/mudlist), new listing using MUDs [MSSP](#mssp) protocol information.

### Links

- [MUDs Wiki](https://muds.fandom.com/wiki/Main_Page) in fandom.com.
- [The MUD Coders Guild Awesome-Mud list](https://github.com/mudcoders/awesome-mud). Awesome list, in the same fashion as this one.
- [MUD historical society](https://github.com/mudhistoricalsociety) is a github organization with a lot of repositories of old codebases.

### Technical Documentation

- [Mudhalla](https://mudhalla.net/), home of the Tintin client, MUD listing, protocols documentation.
- [Mudlet wiki](https://wiki.mudlet.org/w/Main_Page). Protocols documentation.

### Others

- [Titans of Text](https://www.titansoftext.com/), podcast, 33 episodes during 2019-2020.
- [50 Years of Text Games](https://if50.substack.com/), the original content of the book about text games, first published as a newsletter in Substack, free to read.
- [Terra Nova](https://terranova.blogs.com/terra_nova/), defunct collaborative blog for academics and professionals in game studies, focused primarily on the study of virtual worlds (2003-2014).

## Papers

- [Players Who Suit MUDs](https://mud.co.uk/richard/hcds.htm), a refereed paper which appeared in Volume 1, Issue 1 of the *Journal of MUD Research*, June, 1996. By Richard Bartle. Also known by its full title as "*Hearts, Clubs, Diamonds, Spades: Players Who Suit MUDs*".
