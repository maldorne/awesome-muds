```
From: George Reese <borg@imaginary.com>
Newsgroups: rec.games.mud.announce, rec.games.mud.lp
Subject: FAQ: [lpmud] rec.games.mud.lp and LPMuds
Reply-To: borg@imaginary.com
Message-ID: <etEQ1.3437$Ge.11072290@ptah.visi.com>
Date: Thu, 01 Oct 1998 05:31:54 GMT

Archive-name: games/mud-faq/lp
Last modified: 98/10/01
Version: 2.99
Posting-frequency: bi-weekly
```

# LPMud FAQ

Last Modified 98/09/15

The LPMud FAQ was originally authored 7 November 1994 by George Reese. It could not, however, have been completed on the efforts of a single person. See the credits section for a full list of contributors. To make comments or suggestions on this FAQ, mail borg@imaginary.com.

Copyright (c) 1994-1998 George Reese.
_________________________________________________________________
                                      
This is a list of Frequently Asked Questions asked about LPMuds and the newsgroup devoted to them, rec.games.mud.lp. This FAQ is posted twice a month to rec.games.mud.lp, rec.games.mud.announce, news.answers, and rec.answers. All readers are strongly advised to read this FAQ before posting questions to the LPMud news group, as your question may already be answered in here.

This FAQ is not intended to be a substitute for the general 3 part mud FAQ's. I strongly recommend people new to muds read those first. This FAQ deals with a particular class of muds known as LPMuds, and therefore does not even attempt to cover information important to other classes of muds.
_________________________________________________________________

The LPMud FAQ is divided into four sections:
 
 * Section I: Introduction    
 * Section II: Playing LPMuds    
 * Section III: Coding on an LPMud    
 * Section IV: Starting Your Own LPMud

_________________________________________________________________

## Section I Introduction   
  
  Contents

  1. What sort of posts belong in rec.games.mud.lp?
  2. I disagree with something in the FAQ. How do I get the FAQ changed?
  3. What is an LPMud?
  4. Isn't Amylaar an LPMud?
  5. Which is the real LPMud?
  6. How did LPMuds get started?
  7. What is the difference between LPMud and Dikus
  8. What do the terms "alpha testing", "beta testing", and "fully open" mean?
  9. Where are some ftp sites with LPMud stuff? 
  10. Is there anything about muds on WWW? 
  11. What are some mud related mailing lists?     

_________________________________________________________________                                      

### What sort of posts belong in rec.games.mud.lp?

From the rec.games.mud.lp charter of 23 October 1991:
 
>"The charter of this newsgroup is to discuss topics related to the LPMUD variant of MUD. LPMUD is a particular "brand" of MUD that was written by Lars Penji and has gained some populatity among MUD players in general, Discussions here should be confined to the following topics. Briefly, LPMUD uses a "parser" to interpret a 'C' like language (called LPC) which defines the actual game being played. Thus the various topics of discussion break down like so:

   * Player and 'Wizard' issues
   * Ongoing LPMUD campaigns
   * Parser programming issues and bug fixes
   * LPC (LP 'C" code) programming
   * LPC source code posting
   * LPMUD administrativia and announcements

  Topics of discussion which should NOT include this newsgroup are:

   * "LPMUD is (better,worse) than..." flames
   * Non-LPMUD campaigns
   * Non-LPMUD issues or programming"

Specifically, rec.games.mud.lp supports _almost_ anything dealing with LPMuds. The primary rule is that the topic of your posts must someway affect the LPMud community. We do not care about Dikus and MOOs and so on. They may be very nice servers, but if we wanted to be reading about them, we would be reading rec.games.mud.diku and so on.

Beyond that, the charter is a little unclear and out of date. What sort of LPMud related posts belong in the newsgroup generally falls into anything of general interest to the LPMud community in general or one-time administrative announcements for specific muds. This would include announcements of downtime, but exclude queries into why a particular mud is down.

In particular, the following questions are definitely _not_ welcome in rec.games.mud.lp:

* FascistMUD's admins are such jerks!!! They ...

  Why would you post this? I guarantee you will accomplish nothing by this. First of all, ALL mud admins have bad days where they may do something very unfair. It is the nature of things. So you may be the unfortunate victim of a rare set of circumstances rather than of a mean admin. Secondly, even if the mud admin is a jerk, no one on this newsgroup cares. People will play such muds either because the admin is damn good at creating a game or because the players are other jerks who like the atmosphere of lawlessness. Players like you may login from time to time, but eventually they will figure it out.

* Do not post mudsex sessions 

  An individual's sexual activities are not matters for public derision. How people choose to express themselves sexually is a private issue as long as only consenting adults are involved. 

* Where is CheeseMUD? I have not been able to connect all day! 

  If it is going to be down a long time, the admins should post to rec.games.mud.announce. Otherwise, it is either a short connection loss or it is just your problem. _Do not post these questions here or anywhere!!!_

* Advertisements for muds

  These belong in the newsgroup rec.games.mud.announce.       

In the event someone does post improperly to the newsgroup, readers should quietly inform the poster of the misstep via email. In the past, violations of the Charter or FAQ have erupted in counter-productive flame wars. By emailing the offender, you accomplish both the tasks of informing the person and of keeping the newsgroup free of pointless arguments.

_________________________________________________________________

### I disagree with something in the FAQ. How do I get the FAQ changed?

You should email the maintainer of the FAQ. Change requests fall into three different categories. I handle the requests differently based on the category into which a given request falls. The three categories are:

1. Matters of fact
2. Matters of opinion
3. Matters of consensus

The first kind of issue are matters of fact--i.e. the status of mud software, the email address of a mailing list, etc.--then I will simply add that to the FAQ. If you are not directly responsible for the issue in question, I might request an email from the person who is.

Matters of opinion will likely not replace existing passages, but instead appear alongside them. For example, the FAQ might state that capturing player emails is a good idea. Someone who disagreed strongly and presented an argument could email that argument to me. Since this is a matter of opinion, the new opinion would be added as an opposing opinion. In other words, it would not replace the existing clause.

Certain issues, such as the interpretation of the Charter, are neither matters of fact nor matters of opinion--they are matters of consensus. These are parts of the FAQ for which only one point of view can be right, yet a certain minority of people may nevertheless disagree with.

The FAQ has been around for a long time and represents the consensus of the newsgroup. Consensus does sometimes change, and the FAQ needs to be able to adjust with changes in consensus. For matters of consensus, I will ask anyone making a request to provide evidence that the consensus of the group has changed. Because the FAQ is established as the consensus of the newsgroup, the burden of proof is entirely on the requester. The nature of that proof is naturally dependent on the issue at hand.

_________________________________________________________________

### What is an LPMud?

An LPMud is one of many classes of muds, or multi-user domains. A multi-user domain is defined solely with respect to its ability to allow multiple real individuals to come together in some sort of environment. Although the most common environment is a gaming environment, muds need not be games. In fact, among other uses of MUDs that I know of, there are virtual colleges, a mud where victims of abuse can come together in a productive environment, and muds designed to bring students with disabilities into social contact with one another and others. The single defining theme for mud is therefore being a virtual environment where multiple people come in contact.

An LPMud specifically allows the users to manipulate the environment through a language called LPC. LPMuds are computer programs which listens to the internet for people attempting to connect, reads LPC files, and acts upon those LPC files according to the rules of the LPC language to create the virtual environment. Currently, I know of 6 major LPMud servers:
 
 * CD    
 * DGD    
 * LPC4    
 * LPMud    
 * MudOS    
 * Shattered World

With most other mud games, users do not have access to create in the language used by the mud. LPC is used not only to give users such an ability, but it is also designed with both ease and power in mind.   

_________________________________________________________________

### Isn't Amylaar an LPMud?

Amylaar is a person, not an LPMud. He is the primary author and torch bearer of the LPMud name. Given the generic sound of the term "LPMud" these days, people often refer to LPMud 3.2 as the Amylaar driver.   

_________________________________________________________________

### Which is the real LPMud?

LPMud 3.2 is the official continuation of the original LPMud server, however, all servers listed above are equally real. All have two traits that make a mud an LPMud:

 1. The environment is created through files written in LPC.
 2. The environment can change as new files are added and old ones changes, even while the game is running.       

_________________________________________________________________

### How did LPMuds get started?

I am not the greatest historian, and may be wrong on some important facts here, but this is the first shot at the FAQ, so here goes... Once upon a time, there was Lars Pensjö (the ö being an o with two dots over it... to an American, that is roughly pronounced "Penscha"), who wrote the original LPMud coming from an AberMUD background. If you play current LPMud's of the LPMud type, you won't really notice much of a difference from the original. From the coders' point of view however, LPC is nothing like it was with the original. For a long time, there was only LPMud run by Lars with patches by everyone under the sun. The original LPMud run by Lars was called Genesis. Its base town called Larstown was taken mostly from AberMUD.

Eventually, others got tired of waiting to see their patches added to Lars' driver, and Lars was working on version 3.0 of his driver as he was gradually losing interest in the project altogether. Version 3.0 turned out to be buggy as hell, and generally unworkable for a real LPMud. CD, LPC4, LPMud, and MudOS, all derive from this server as people saw good things in it and began creating working versions of LPMud 3.0 after their own concepts of mud server design.

Unlike the others, DGD was created from scratch. It therefore is missing a lot of the baggage which has come down from the beginning of time in the other drivers. Shattered Worlds, on the otherhand, derives from LPMud 2.4.5.   

_________________________________________________________________

### What is the difference between LPMud and Dikus?

This section is almost entirely quoted from a post by Tim Hollebeek: The main difference between Dikus and LPs is that a Diku server provides a game, while an LP server provides a language in which to write a game. This means that an LPMud server is more like your perl or python binaries than a Diku binary. An LPMud has an extra layer in which the game is written, called the mudlib or object library. The advantage Diku enjoys is that it can be more efficient since the game is more low-level. The other edge of this sword, however, is that it is very hard to make changes to a Diku and it requires a high level of technical knowledge.

An LPMud, on the other hand, is extremely flexible and requires a minimal amount of technical knowledge in order to build the same things (or even more complex things) as exist on Dikus. As a consequence, LPmuds tend to be more widespread and reflect a greater diversity of imagination.

The truth about LP's is that it is virtually impossible for a player to know they are on an LP; the driver is simply too far removed for it to make any difference to the player in terms of look and feel. Many LP's, however, do have a common look and feel because they share the same mudlibs.

_________________________________________________________________

### What do the terms "alpha testing", "beta testing", and "fully open" mean?

Generally, a mud goes through three basic stages. The first stage, "alpha testing", is a developmental mode in which players are rarely allowed access to the mud. Things are in such a disarray or in a flurry of changes that playing a consistent game is impossible. In the "beta testing" stage, a mud is generally opened to players solely for the sake of testing that the mud works. Without actual play testing, it is impossible to determine if a mud can handle being fully open. muds in either of the above stages generally will not compensate players for mishaps due to bugs in the game, and they will often even purge players from the mud. The purging is done either because old player objects are no longer compatible with new ones or because the mud needs to be re-balanced to fit new code.

In the final stage, "fully open", a mud is just that, fully open. That means you can expect certain standards from the mud, including such things as not dying from bugs. Nothing is ever bug free, so generally fully open muds will compensate players for mishaps which occur because of a bug. On the flip side, these muds usually also smite players who gain from bugs in the system.

_________________________________________________________________

### Where are some ftp sites with LPMud stuff?

See Section IV: Where can I find all of this stuff?

_________________________________________________________________

### Is there anything about muds on WWW?

The following is a list of LPMud related WWW URL's, a few of which are even written in the mud programming language LPC:
 
 * http://www.bat.org
   The BatMUD WWW Server
 * http://www.lostsouls.org
   The Lost Souls WWW Server
 * http://www.imaginary.com
   The Imaginary WWW Server
 * http://www.pvv.unit.no/viking
   The Viking mud WWW Server       

_________________________________________________________________

### What are some mud related mailing lists?

The following lists use the Mailman mailing list software. Click on the link to subscribe to those lists:

 * http://list.imaginary.com/mailman/listinfo/foundation-mudlib
   The Foundation Object Library Mailing List   
 * http://list.imaginary.com/mailman/listinfo/intermud
   The Intermud Protocols Mailing List   
 * http://list.imaginary.com/mailman/listinfo/lima-mudlib
   The LIMA Mudlib Mailing List   
 * http://list.imaginary.com/mailman/listinfo/lpc-language
   The LPC Language Mailing List   
 * http://list.imaginary.com/mailman/listinfo/mudos
   The MudOS General Discussion Mailing List   
 * http://list.imaginary.com/mailman/listinfo/mudos-bugs
   The MudOS Bug Reporting List   
 * http://list.imaginary.com/mailman/listinfo/mudos-develop
   The MudOS Developers' Mailing List   
 * http://list.imaginary.com/mailman/listinfo/mudos-patches
   The MudOS Patch Distribution List       

The following lists use the majordomo software. To subscribe, mail majordomo at the sites mentioned with "subscribe list-name" in the body of your mail. To get more information on the lists below, mail majordomo at the site mentioned with "info list-name" in the body of the mail. Naturally, list-name should be replaced with the appropriate list name.

For example, to subscribe to the lpc-language mailing list lpc-language@imaginary.com, you do the following:

 1. mail majordomo@imaginary.com
 2. subject is irrelevant, body says "subscribe lpc-language"
 3. the list will then confirm you have been added by mail 

To mail a post to the mailing list, simply mail lpc-language@imaginary.com and proceed as you would as if you were mailing a single person.

 * amylaar-users@nightfall.org
   The LPMud 3.2 and 3.2.1 Users Mailing List       

In addition, the TMI-2 mailing list uses different mailing list software which can be subscribed to by visiting the list page at http://www.mudlib.org/mailman/listinfo/tmi-2.

Individual muds may have their own mailing lists as well. Check with your LPMud for details. For people running lists with an audience beyond a single mud, please let me know of your list. If you use list software not listed, I need the name of the list, how to subscribe, and how to get more information.

_________________________________________________________________
                                 
## Section II Playing LPMuds
                                      
  Contents
  
  1. How do I play an LPMud?
  2. But I am using windows!
  3. How do I get a list of LPMuds?
  4. Are all LPMuds in English?
  5. Ok, the mud is asking me for a name, what do I do? 
  6. They told me I had to register!
  7. Name and password set, what next?
  8. I don't want anyone knowing my email address!
  9. Is it asking me for my gender?
  10. What does it mean by race?
  11. What is a class? What is a guild?
  12. I am in the mud, what do I do?
  13. What are some common commands?
  14. What is an alias?
  15. Why is the mud admin ignoring me?
  16. The admins are being unfair, don't I have rights?
  17. What about freedom of speech?
  18. What else is there?
       
_________________________________________________________________
                                      
### How do I play an LPMud?

You must first find the internet address of the mud you wish to play.Once you find the address, most often people use the "telnet" programto connect to this address. The mud FAQ has an excellent section onMUD clients, which are alternatives to the plain vanilla "telnet"program. However, generally speaking, with "telnet", you can accessthe mud of your choice by issuing the command:

  `telnet address port`

For example (% is considered your prompt):

  ```
  % telnet nightmare.imaginary.com 1701
  % telnet 129.10.114.86 5555
  ```

And so on. Some telnet programs do not allow you to pass arguments atthe command line. Instead, you get something like this:

  ```
  % telnet
  telnet> open
  (to) nightmare.imaginary.com 1701
  ```

Once you succeed, you will get a welcoming screen which should say thename of the LPMud and ask you for a name. A common error people willmake is leaving off the number at the end. If you do that, the telnetprogram assumes you mean to go to port 23, and it will give you alogin prompt to the host machine.

In addition, _some_ VMS telnet programs use the following syntax:

  `telnet 198.174.169.120/port=1701`

_________________________________________________________________

### But I am using windows!

The telnet program that comes with Windows95 and Windows NT is extremely anemic and not much good for anything. Other versions of Windows do not even come with a telnet program. To connect to a mudusing the default Windows95/NT telnet, go to the 'Start' menu and click on the 'Run' menu item. In the text field, enter:

  `telnet nightmare.imaginary.com 1701`

Of course, you should use the proper address for your mud as described in the telnet section. This will connect you to the mud, but it may be a bit confusing. The first thing you need to do is turn echo on so that you can see what you are typing. Go to the 'Terminal' menu and click 'Preferences'. Check the 'Local Echo' check box. You may also want to resize the window so there are no scroll bars.

You will not be able to stand playing a mud this way for very long. It is highly recommended you download a Windows mud client ASAP before you go insane. In the least, you might want to grab a useable telnet program like EWAN or CRT.

_________________________________________________________________

### How do I get a list of LPMuds?

I know of no place that lists ONLY LPMud's, however, there is Doran's Mudlist, which is produced semi-regularly and lists muds by type. You thus have all your LPMuds grouped together. You can find it posted to rec.games.mud.announce.

MUDs connected to the Intermud generally have mudlists which they maintain dynamically based on which muds they are currently talking to:

 * http://ie.imaginary.com:7885/gateways/mudlist
   The Idea Exchange Dynamic Intermud Mudlist      

Keep in mind, however, these dynamic lists hold only LPMuds which support intermud communication. They are by no means full lists. You will also find that many muds on this list are in some sort of developmental stage.  

_________________________________________________________________

### Are all LPMuds in English?

No. To provide a list of such muds is beyond the scope of this FAQ. Check the mudlists for a full and current listing. However, I would like to know about other languages which might be supported in the LPMud world, so please mail me if you have a mud in a language in other than English, German, or Swedish. Known languages:

 * Chinese  
 * Dutch  
 * English  
 * German  
 * Hungarian  
 * Polish  
 * Swedish

_________________________________________________________________  

### Ok, the mud is asking me for a name, what do I do?

Make up a name. Avoid using your real name or common names, real and mythical. You want not only to give character to your persona, but you also do not want everyone saying "Hey! Aren't you Bob from JustAnotherMUD"? I chose the name Descartes, because I was a philosophy major in college. In general, it is safe to assume any name consisting only of more than two characters and less than ten (a to z) is acceptable on any mud. Some muds allow really long names with spaces, apostrophes, hyphens, and other marks. Others are in between the extremes. Try the name you want. If the mud will not allow it, it will tell you, and it should tell you why. 

After making up a name, one of two things will happen. Either you will be prompted for a password, meaning you have picked a name someone else is using, or it will ask you to create a password, meaning you are a new character. If the first thing happens, just try again with another name. If the second happens, you are in good shape. 

To create passwords, make up one different than the one you use to access computers. Although muds encrypt passwords for storage, nothing prevents an unscrupulous mud admin from intercepting that password and using it for unethical purposes. It is also recommended that you use a password with numbers and mixed upper and lower case letters in it. 

_________________________________________________________________

### They told me I had to register!

Some muds require all their players to register before being allowed to play. Also, it may be the case that someone from the same place as you has been causing trouble, so the admins of the mud in question have decided to require only people from that site to register. If this is the case with the mud you wish to play, simply follow the instructions they give. In most cases they will give you an email address where you should send your registration.

_________________________________________________________________

### Name and password set, what next?

This is where you get to see why there is so little in common among LPMuds from the player's point of view. Some LPMud's will ask you a series of questions about who you are and what sort of character you would like. Others ask nothing more. Among the questions you might be asked are: what is your email address? what is your real name? what gender would you like to play? what race would you like to be? what class would you like to be? etc.   

_________________________________________________________________

### I don't want anyone knowing my email address!

MUD Administrators have a legitimate need to know your email address. No one else does. If a mud requires you to give your email address it should either offer you the option of keeping it private, or it should automatically keep the email private. If they do not keep your email private and you desire privacy, do not play the mud. Do not complain, however, that they ask for it.

_Note:_ There seems to be some difference of opinion on this one, so I decided to quote one of the comments:

> "Well, I have to disagree with this section: E-mail addresses are very difficult to verify in bulk, and really not worth the trouble unless you perform site registration. I believe the only people you have a legitimate need for an email address from is your wizards. Other than that, knowing the ip they log in from should be more than sufficient." -Rust (John Viega)

_________________________________________________________________

### Is it asking me for _my_ gender?

No. The game wants to know what gender you would like your _character_ to be. This means you can play a character of the opposite gender, your own gender, or one of the alternate gender types which might be offered. The other side of the coin to this, however, is that you should _never_ count on other people in real life being the gender of the character they play.

_________________________________________________________________

### What does it mean by race?

Many LPMuds have a feature called character races. The term "race" in these instances is not the same as the term used in modern society. In fact, the LPMud term race would more correctly be referred to as species. In fantasy type LPMuds, you will often see a selection of "races" like human, orc, artrell, gnome, etc. When you are asked to choose a race, a list of possible races should be provided for you.

_________________________________________________________________

### What is a class? What is a guild?

In general, a class is a grouping of players with common abilities. A guild as well can be said to have the same definition. Many muds, if they use either of these concepts at all, add some very individual nuances. To muds which do not have classes or guilds, the concepts are naturally irrelevant. Those which have one or the other are often using the terms in an interchangeable fashion. Finally, those muds which have both often define class in a more generic manner than guild. For example, on Nightmare, a class is like a profession and the guild like a particular job. You might have people in the fighter class who are in the templars guild, and others who are in the rangers guild. In short, the guild is a way of specializing your class abilities. 

Other muds allow "multi-classing", which may mean joining multiple guilds, classes, or both. It is always best to check out the "help guild" and "help class" command on any given mud to see how it defines these terms.

_________________________________________________________________

### I am in the mud, what do I do?

There is no one answer to this question, as the answer will vary from MUD to mud. No matter what, however, you should see if the mud has a "faq" command to get a listing of that mud's frequently asked questions. In addition, you should learn how to use the "help" command as well as find out about the rules governing that mud.

_________________________________________________________________

### What are some common commands?

The following commands exist on virtually all LPMuds. () around part of a command indicate that that part is optional. [] indicates that the text should not be taken literally. These commands naturally are not likely to be found on non-English muds. 

 * help ([topic])
   Gives you help. If you specify a topic, you get help on that topic. If you just type help, you will either get help on where to find other help, or you will be put into a help menu.         
 * tell [player] [message]
   Sends the string [message] to the player whose name is [player] anywhere on the mud. Some LPMuds do not allow players to tell to one another as it is viewed unrealistic.         
 * say [message]
   Sends [message] to everyone who is in the same mud room as you. This command is almost always aliased to "'", such that "'hi!" is the same thing as typing "say hi!".         
 * who
   Gives you a list of everyone connected to that mud.         
 * look
   Gives you a description of the mud room in which you are in.         
 * look at [object]
   Gives you a description of the object in question.           

_________________________________________________________________

### What is an alias?

As with UNIX, most LPMuds provide some sort of method for creating "aliases". An alias is simply a way in which you can have a easy to type command represent another command. For example, you will often want to type the phrase "get all from corpse" on any LPMud. It is much easier to make an alias so that whenever you type "gac", the LPMud interprets that as "get all from corpse". 

In order to create aliases, you need to know how your particular mud handles aliasing. Older muds use a device called a quicktyper. Newer MUDs have alias commands built in. Try issuing "help alias" and "help quicktyper" commands in order to find out how aliases are handled on your mud. If your mud uses quicktypers, you will have to go find the quicktyper object before you can create aliases. Ask any other player on such a mud where there quicktyper can be found.

_________________________________________________________________

### Why is the mud admin ignoring me?

Admins in particular are prone to a mud disease called "idling". This means that the lights are on, but nobody is home. An idle person is simply someone logged in to the game, but who is perhaps not actually at their computer terminal. That person is thus not really ignoring your question, since the person is never actually seeing it. 

If the admin is not idling, chances are that person is being overwhelmed with questions or is actually coding online. Many LPMuds will tell you that the person to whom you are talking is "idle" or "editing". If you get that response to a tell, do not expect an answer back right away. In addition, if it says the admin is editing (or anyone else for that matter), then it is generally considered rude to continue telling to that person as it makes it difficult for the person to edit. 

Many people these days have the ability to be on several muds at the same time. It is therefore entirely possible that the person to whom you are trying to talk is in fact looking at another window. To get that person's attention, it may be ok to "beep" them (by sending a control-G in a say or tell). Some people do not like others to do this to them, however, so be careful about doing it too much.

_________________________________________________________________

### The admins are being unfair, don't I have rights?

The short answer is yes, you have the right not to play the game. The long answer is much more complex. First off, any reasonable set of admins who wish to create a game which people will enjoy will enumerate the sorts of behaviour you can expect from them. In other words, admins on fun muds will state the rules of the game ahead of time and will not deviate from those rules. That way you know what to expect. In addition, if you do not like the rules, you don't get involved with playing the game. 

What prevents an admin from breaking their own rules? Absolutely nothing. In one sense, a mud is like someone else's swimming pool. You have absolutely no right to swim there, and they have the right to throw you out just because you talk funny or say things they don't like. Fortunately, there are plenty of muds out there with civil administrations to make this nothing more than a passing nuisance.

A common misconception is that mud admins administrate muds for power, and that arbitrary behaviour is a way of exercising that power. Though there may be a few misguided individuals out there who do in fact administrate muds for the sake of power, the fact is that no mud administrator has any power over you. Remember, the worst thing any admin can do to you is make you go play somewhere else.

A final thing to remember is that muds evolve and rules evolve with the mud. Just because rules change does not mean the admins are being arbitrary. Arbitrariness is reflected in sometimes applying rules and sometimes ignoring them, not in creating new rules to fit unforseen situations.

_________________________________________________________________

### What about freedom of speech?

No, not even freedom of speech. Again, reasonable admins will clarify in publically available rules what sort of speech (hate speech, offensive language, or whatever) is not acceptable on that mud. You may or may not agree with those rules or the political beliefs those rules represent, but at least you do know where you stand on the mud. It is thus up to you to decide if you can play under those rules or not. In the event you encounter an unreasonable mud, there is nothing much you can do but decide to leave. If it is a commercial mud, however, deciding to leave can be some sort of leverage.

A common source of friction between players and admins is where players decide to criticize admins. Most often, the players are not really trying to criticize the admins so much as inspire positive changes to make a game they love even better. In those cases, it is always good to remember that the admin is a real human who is closely involved with what the mud is. If you keep that in mind, you can often help bring positive changes to the mud you play without unintentionally striking a hidden chord in a sensitive admin.

_________________________________________________________________

### What else is there?

Explore the mud! Most gaming muds have places called "newbie" areas which are simplistic places for people new to the game to go and get the hang of things. When you first log in to a new mud, you should ask the others where the newbie area is. Also, read the login screen and news which scrolls across your screen at login time, as they contain important information about characteristics unique to the mud you are playing. 

Ask people questions. Just make sure you have read the help files first, or you will be sure to annoy someone. In addition, try not to choose a single person for your queries. Constantly being asked questions by the same person can often annoy people as easily as stupid questions.

_________________________________________________________________
                                      
## Section III Coding on an LPMud

  Contents  

  1. What is coding?
  2. What is LPC?
  3. How do I get to code on an LPMud?
  4. How do I learn to code?
  5. What is The Idea Exchange?
  6. How do I learn to code a room/monster/weapon/armou...?
  7. But you said that all LPMuds use LPC!
  8. My code is not working! How do I fix it?
  9. What is an efun? an lfun? a kfun? a sefun?... 
  10. Can I take my area from LPMud X to LPMud Y? 
  11. Can I code offline? 
  12. Why does the mud use ed? Why not have the mud use vi/emacs...? 
  13. How do I put my code into the game?     

_________________________________________________________________

### What is coding?

Coding is writing files for the computer to read. In the case of LPMuds, this means writing files in a computer language called LPC. The LPMud server reads these files and interprets what those files are telling the computer to do when certain player actions occur. Often that means things like displaying a description of a room when you enter it and so on. The LPC files which make up the backbone of any mud are called the mudlib. Coders use the mudlib code in such a way as not to have to rewrite many of the most common instructions over and over again. With most good mudlibs, therefore, there is more creation involved than coding.

_________________________________________________________________

### What is LPC?

LPC is an object building language created by the author of the original LPMud server, standing for Lars Pensjö C. Structurally, it is much like the more popular programming language C. Designed with LPMud object building specifically in mind, it puts the power of game building in the hand of the general user.  

_________________________________________________________________

### How do I get to code on an LPMud?

Policies vary from mud to mud. Some muds require you to make a certain player level before being allowed to code. Others require you to pass a test or fillout an application. Still others just let anyone come on and code. If you really want to get in on things, the best thing to do is either to talk to the admins of the mud you are playing, or go to The Idea Exchange (ie.imaginary.com 7890) The Idea Exchange has a newsgroup for coders looking to code and another for muds looking for coders. Keep in mind that many muds which are open to players already have more coders than they need.   

_________________________________________________________________

### How do I learn to code?

There are two parts to learning how to code on your mud:

 1. Learning LPC
 2. Learning your mud's object library (mudlib)

Each mud should have detailed documentation on part 2. Two LPC textbooks, a beginner and an intermediate, exist to take care of part 1. You can get the textbooks via ftp at ftp://ftp.imaginary.com/pub/LPC/. Documentation, however, will not    really do anything without looking at examples, practicing, and talking to more experienced coders. Examples should be everywhere on your mud (though they are not necessarily good examples). Practicing is simply just copying code you do not understand, making small changes to it to see what they do, and learning from what happens. To learn more about how to code from others, talk to more experienced coders on your own mud or visit The Idea Exchange which is designed to help people learn LPC.

_________________________________________________________________

### What is The Idea Exchange?

The Idea Exchange is centered around the advancement of LPMud technology and the promotion of its use. On The Idea Exchange you will find many of the people responsible for the software commonly used to build LPMud environments, including the authors of drivers and mudlibs. It is an excellent place for learning about LPC and discussing new ideas.

_________________________________________________________________

### How do I code a monster/room/weapon/armour...?

Read your mud's documentation, as this varies greatly from mud to mud.

> "Also, questions like that are almost impossible to answer in any   other way than showing an example. Thus, a much better question is:   'Where can I find an example of how to create a XXX?' or 'I don't   quite understand this part of the example on how to...'" -Drevreck   (Lars Syrstad)      

_________________________________________________________________

### But you said all LPMuds use LPC!

Yes, they do. However, they do not all use the same mudlib. The mudlib is the basic LPC files you make use of then you write your LPC files. The LPMud server in turn interprets your files and stores them in memory. Two muds using different mudlibs therefore can be wildly different from one another. And since the mudlibs are so different, the files you will write will be equally different.

An analogy might be that of a human dialect. Quebecois French and Continental French often use different words and such in order to express ideas. In spite of this, the language structure is the same. So, both are still French even though you sometimes need to say different things in order to mean the same thing.

In writing an object in LPC, you are almost always using the mudlib's LPC files rather than totally writing files from scratch. You do this through something called inheritances. Inherited code which exists on one mud may not exist on your mud, or may exist differently. Therefore when you try to use that code, it will not work as you expect even though both are in LPC.

_________________________________________________________________

### My code is not working! How do I fix it?

First, determine if the problem is with... 

 * the object failing to load 
 * the code causing an error when it runs 
 * no errors, it is just the expected things do not happen

Now that you know what "type" of error you have, you need to isolate it. Isolating it depends on the type of bug...
 * _the object fails to load_
   You have the bug isolated for you you in your error file. The location of the error log depends on the file name of the object with the error. It also depends on the way your mudlib logs such errors. Nightmare, for example, logs compile errors to /log/errors/std for obejcts in /std, etc, and /log/errors/descartes for objects from /realms/descartes. TMI-2 would log my errors to /u/d/descartes/log and mudlib errors to /log/* with sensitive logging going to /log/adm/* _know_ with MudOSthe driver does isolate the error for you to a useful degree of certainty. More on this later. For LPMud 3.2.1, you can use the: #pragma verbose_errors preprocessor directive to make compile time errors include a bit of context in error messages. Some mudlibs turn this #pragma on by default.
 * _an error occurs during execution_
   These are logged in the mud's runtime error logged, and they ALWAYS reflect the exact line where something happened. On MudOS muds before 0.9.20, the system runtime log was /log/debug.log. The mudlib in later versions has the option of naming it whatever. 

   > "Brought over from LPMud 3.[01].x , LPMud 3.2 uses /`hostname`/debug.log. LPMud 3.2.1 allows you to pass the option --debug_file to change this default. If there is a triple fault (i.e. an error while the master was processing an error in error processing), and you compiled the driver with the TRACE_CODE option, there will also be a trace of the last instructions executed. Moreover, if the driver is not out of memory, and there   is no triple fault, the apply runtime_error() is called in the master, with the error message, file name, object name and line   number as arguments." -Amylaar

   Note that for drivers which can compile LPC code to C and then link it into the driver, no line number information will exist to help you in debugging. You should therefore debug your LPC code thoroughly before compiling it to C.
 
 * _no errors, you just do not get expected results_
   These are the hardest to debug. You need to go through the code and test

    1. Which code is being executed
    2. The values of the variables in the executed code

    How do you do this? Take the following code with a priveledges bug...

    ```
    /* from /cmds/adm/_rid.c */

    int cmd_rid(string str) {
        if(!archp(previous_object())) return 0;
        if(!str || !user_exists(str = lower_case(str))) return 0;
        if(!((int)USERS_D->rid_user(str))) return 0;
        message("system", "You rid "+capitalize(str)+".", previous_object());
        return 1;
    }

    /* EOF */

    /* /secure/daemon/users.c */

    int rid_user(string str) {
        return rm(DIR_USERS+"/"+str[0..0]+"/"+str+SAVE_EXTENSION);
    }

    /* OTHER CODE DELETED FOR BREVITY */
    ```

    This is not real code (as a lot more should exist in such an operation). However it does serve the point. This code will load fine and execute without error. However, it will not delete the save file of any user. If anyone executes it, the following will happen:
              
    ```
    > rid weenieplayer
    What?
    >
    ```

    So what do you know? You know you typed "rid weenieplayer", and you know you got 0 returned. One of the following things happened:
    
    1. The "rid" command never got executed
    2. The archp() returned false for the person executing the
       command
    3. For some reason, str was equal to 0
    4. rid_user() in users.c returned 0 to the command
            
    How do you know if 1 is the problem? put the line... write("rid command executed") as the first line of the cmd_rid() function in the rid command. If the rid command is executed, you will see that it is executed before you see "What?". If it is not, you will just see "What?". If you do not see that line in write(), then you know your bug is with you whatever calls the "rid" command. If you do, then you know you must proceed further.
 
    Do the same after each line which returns 0. Make sure each write() string is unique so you know *which* line is being written out. This will tell you exactly *which* line is returning 0 in the rid command.
 
    In this case, it is #4 which is the problem. The users daemon is returning 0 for for rid_user(). This means that rm() is definitely returning 0. rm() only returns 0 when an rm fails. rm() only fails when an object does not have proper access. Therefore, in this case, you need to fix the bug in your security.
 
    If for some reason you cannot go editing the files in question (i.e. they are in the base lib files to which you have no access, changing them would be even more troublesome, etc), you should consider the efuns trace() and traceprefix().
 
    Do you need to go through all of these tedious steps? No, you can generally make good guesses as to where to look the more familiar you become with the code. For example, in this case you pretty much could have elimited step 1 if that command is an old command which used to work. After all, it is highly unlikely that the mud would suddenly stop executing that one command!
 
    Furthermore, if you had just made a change to the security system, you would immediately suspect that rm() failed and thus would have checked that first.
 
    This is why presenting me with your entier rid command would have been useless to me. I would have looked at it and said it *looks* ok. But I have no idea what changes you have recently made to your mud, nor do I know from looking at the code which of those lines is returning 0. I can only basically tell you that one of those lines is failing.
 
    However, if you were to tell me that for some reason your user object was returning 0 in trying to rm() the user file during the rid command, I could tell you details about the relevant parts of the Nightmare LPC Library security to this daemon. And then you could use that information to debug further and ultimately fix the bug.

_________________________________________________________________
                                      
### What is an efun? an lfun? a kfun? an sefun?...

For any function in LPC, there are three distinct parts...

 1. the prototype
 2. the call
 3. the definition

Whate differentiates all of these different types of functions is _where_ they are defined. The definition of the function is the part which says what it does.

 * afun (auto function, DGD only)
   the function is defined in the auto object and behaves like and efun from other drivers. This function is really very special type of lfun.
 * apply
   a function defined in the mudlib designed to be called only by the driver. All applies are also lfuns. Most of the functions in the DGD's driver object and other's master object are applies. In addition, the functions create(), init(), and reset() are also applies for LPMud 3.2 (not 3.2.1), MudOS, and CD.
 * efun (external function)
   this type of function is defined external with respect to the mudlib. In other words, in the driver. Since it is defined inside the driver, it is faster, but the mudlib is left with little control over what it does.
 * kfun (kernel function, DGD only)
   This type of function is much like an efun in that it is defined external to the mudlib in the driver kernel. There are some ways beyond the scope of this FAQ in which kfuns differ from efuns, ways which have little bearing to daily coding.
 * lfun (local function)
   Any function defined inside an object in the mudlib. The functions you write (like create() or reset()) are lfuns.
 * sefun (simulated external function)
   lfuns defined in an object known as the simul efun object. Any object in the mudlib is allowed to use these functions as if they were efuns (treat them like local calls).

You might also want to keep in mind the difference between a local call and a call_other. A local call is a call to a function defined in your object or to one of the objects it inherits. A call other is a call to a function defined in another object. Efuns and simul efuns, though not defined in your object, act like local calls. Afuns and kfuns are in fact local calls, since all objects inherit the auto object to which they are local.   

_________________________________________________________________

### Can I take my area from LPMud X to LPMud Y?

Can you? If they use the same mudlib, yes. May you? Often muds have restrictions against importing code in order to keep the mud unique. Talk to the administration of both muds for local details.   

_________________________________________________________________

### Can I code offline?

There are many different methods of coding offline, and which one is available to you depends on your mud. The methods are:

 1. ange-ftp
 2. your favourite editor + ftp
 3. cut-and-paste

Editing offline allows you a faster response time, the ability to multitask, and the ability not to be bothered by incoming tells screwing up your edit window. It also allows you to make use of editing environments which may be much more robust than standard mud ed.

ange-ftp is an emacs mode which allows you to edit files in emacs and have them automatically ftp'ed to your mud and back. ange-ftp requires

 * emacs with ange-ftp mode
 * an FTP server which gives access to host mud files

Using a local editor and ftp allows you free choice of which editors you use, but you have to manually transfer each file. If going from a DOS environment, you also need to watch for carriage-return/line-feed translation. FTP requires:  

 * An FTP server which gives you access to your mud files

Cut and paste requires no file transfer and allows you to use any editor which has immediate access to your mud files. For example, you can edit on your home computer using Notepad, then cut that from Notepad and paste to your mud window which is likely in ed. Cut and paste requires:  

 * The ability to cut and paste from editor to mud window.       

_________________________________________________________________

### Why does the mud use ed? Why not have the mud use vi/emacs...?

See Section IV: How do I get my mud to use vi/emacs instead of ed?   

_________________________________________________________________

### How do I put my code into the game?

A file is considered "in the game" if another file already visible to players references it. So, to put your stuff in the game, you need to change code already in the game to reference your code. This action normally requires the action of mud administrator. Most muds have some sort of quality control policies which state rules for having your code reviewed.

_________________________________________________________________
                                      
## Section IV Starting Your Own LPMud
                                      
  Contents

  1. How do I start my own LPMud?
  2. How do I find a site?
  3. Can I charge players to play my mud?
  4. Why can't I use any of the other servers or mudlibs?
  5. Our system needs upgrading, can't I get donations?
  6. I have a site, now how do I choose a server/library?
  7. What about Nightmare?
  8. What copyright issues are involved with using someone else's code?
  9. Where can I find all this stuff?
  10. Help! I can't get my driver to compile, what should I do?
  11. I have applied patch XXX, and now nothing works any more
  12. How do I do ANSI colours?
  13. Why not just hard code the colours?
  14. How to I make the mud use vi/emacs instead of ed?
  15. Is it possible to connect multiple muds together?
  16. Can a mud server run on DOS?
  17. Can a mud run under AmigaOS? OS2? Windows NT? etc...?

_________________________________________________________________
                                      
### How do I start my own LPMud?

  1. Come up with a unique and interesting idea
  2. Find a site
  3. And do:

     1. Choose a server
     2. Choose an object library

     Or:

     1. Choose an object library
     2. Choose a server
 
     Or:

     1. Choose a server
     2. Write your own object library
 
     Or:

     1. Write your own server
     2. Write your own object library

  4. Define administrative policies
  5. Find people to code areas for the mud
  6. Get some areas completed
  7. Open to players (with a beta test stage recommended)
       
_________________________________________________________________
                                      
### How do I find a site?

The most common method is to talk to the administrator of the machine from which you access muds and the rest of the Internet. If the resources are available, they will often allow you to run your mud server unless something political like a no-games policy is preventing it. If you are not running a mud as a game, however, this is not relevant.

Never run a mud without talking to your system administrator. LPMuds take up a lot of system resources, and many places simply cannot spare those resources on a single project, especially if the project is non-essential to the functioning of the entity running the machine. Not only is it just plain wrong to run a mud without permission, it also predisposes sysadmins to saying no to people who ask them when the resources are free.

If you cannot run it on your local machine, post a note to the ie.sites.wanted newsgroup on The Idea Exchange. Do not post to USENET newsgroups unless you have a working mud. It does not need to be complete, but posting notes saying "I have a cool idea, will someone give me a site" is inappropriate, unless that idea is completely fleshed out with some sweat in the form of work on paper and such.

Another avenue of finding a site is talking to local internet access providers. Often, they have extra small machines on which a mud could be run (sometimes for a fee). The most expensive route is to buy your own machine and your own Internet hookup.

_________________________________________________________________

### Can I charge players to play my mud?

If you write the server from scratch AND you wrote your mudlib from scratch and you have agreements with the coders who wrote areas on your mud, the answer, of course, is yes. The above will take roughly 3-5 years of full-time work to accomplish as well.

If you do not wish to go through all of that time to write your own server and object library, then you may only user DGD. Of course, you will have to get express permission from Dworkin. The only object library you may use for such purposes is LPMoo.

_________________________________________________________________

### Why can't I use any of the other servers or mudlibs?

They all come with some variation of the same copyright. Since all drivers except DGD were derived from LPMud 3.0, they all require a copyright at least as strict as that one, which basically states that you can use the server as you like, so long as you do not make a profit off of its use. Most current servers have much more strict and explicitly copyrights. On top of that, many of the mudlibs which exist also have similar copyrights. To require money of your players is therefore a violation of international copyright laws. DGD requires licensing through a third party company.

_________________________________________________________________

### Our system needs upgrading, can't I get donations?

Yes, you can request that your players donate money as long as the end of that money is to run the mud and donations are not a prerequisite for play on the mud. In other words, they must be donations, not fees.

_Note:_ I am not a lawyer, nor am I the author of all the mud code out there... Therefore, keep in mind that what I am saying about copyrights is my interpretation and not binding upon ANY of the server or mudlib authors out there. For reference to what is binding with respect to my code, see the copyright notice which accompanies it.   

_________________________________________________________________

### I have a site, now how do I choose a server/library?

Some people have a favourite mudlib, and therefore go at building their own mud from the angle of using that mudlib. Others have a favourite server and start from that angle. Others simply want to start a mud fast, while others want to really tinker with it and make it their own. The following is a rough guide to what is out there:

_Note:_ Also, I only publish software which the authors have somehow made known to me to be available, or in fact are widely known to be available. I will not publish information about software which I have no such verification, since being on a public ftp site is not the same as being publically available.

                                  Servers

 * CD
   Generally considered a slow driver, however it is designed to work very closely with the CD-lib. Therefore tests showing the CD driver to be slower are not necessrily fair as sole factors since they are mudlib-independent tests. The CD-lib is considered a well designed lib which is often a factor which leads people to choose this server. To see a CD server mud, visit Genesis.
 * DGD
   DGD is built on the belief that small is good. This is absent of much of the extra baggage which exists in all other drivers since it was created from scratch. There currently exist only a few, small native mudlibs for DGD, one of which is a MOO simulation. DGD's documentation is sparse. It includes dynamic object version updating amd supports compile time LPC->C compiling, meaning that when you compile the driver you can have some of your LPC files converted to C and compiled with the driver. In addition, unlike other LPMud servers, it is disk-based, meaning you can run a huge mud on virtually no RAM. You therefore never need to reboot or save objects. Dark has written a TCP/IP socket support for DGD which can be gotten separately from the driver. Erwin Harte is managing a network package for the driver. 
 * LPC4
   Maintained by Profezzorn, it supports a scripting feature that allows you to execute LPC files as atomic programs without running the mud in the traditional sense. In addition it features lambda closure types which are actually understandable to most people. It is designed for speed through the philosophy of creating large numbers of efuns to perform CPU intensive work. I know of no muds using this driver in practice. LPC4 also has socket efuns with TCP support. 
 * LPMud
   Once the fastest of all the drivers, it has lost this crown to MudOS. Nevertheless, it is an extremely fast driver which supports the old LPMud 2.4.5 Mudlib. It also supports closures, though its closure syntax is beyond general ease of comprehension. There is only one mudlib in wide release which is native to this server. 
 * MudOS
   The fastest and most feature-filled of the LPMud drivers, this one comes with TCP support for mudlib objects allowing you things like WWW, finger, SMTP, USENET, and other such access to Internet resources from inside the mud. It also comes with a choice of well-developed mudlibs native to the server. MudOS allows you to choose between UID support and no-UID support, which makes it easy to hack a LPMud 2.4.5 mud to work with MudOS if that is your cup of tea. MudOS supports a new function pointer syntax which is as functional as LPMud's closures without LPMud's obscure closure syntax. 
 * Shattered World
   Developed by one of the original LPMuds. I believe this driver originated from one of the first LPMud releases and has been heavily customized in such a way as not to be recognizable as such. 

Object Libraries

 * CD-lib 
   I am told this is a very well-designed mudlib. Some features of it are an enhanced sense of reality through player recognition (you must make the acquaintance of players before knowing who they are) and UDP intermud communications. 

   Runs under: CD (native) 
 * Dead Souls 
   A public domain version of the former Nightmare mudlib. It contains a complete mudlib from which to build a world, but is very difficult to set up. 

   Runs under: MudOS v21b25 (native) 
 * DGD Kernel Library 
   A minimal development library that can be used as a basis for both continuous and non-continuous systems. It comes included with the DGD 1.1 release. 

   Runs under: DGD 1.1 (native) 
 * Discworld Advanced 
   command parsing system and user interface, as well as many concepts you will not see in other mudlibs for any server. Too many frogs and wombles. 

   Runs under: MudOS 0.9.20 (native) 
 * Final Realms
   A modernized version of the Discworld mudlib. 

   Runs under: MudOS 
 * Foundation IIr1.1 
   A basic mudlib with nothing extra for people who want a solid design base from which to design a unique mudlib. No combat or anything else fancy is included. Nothing about it is pre-disposed towards fantasy or even game playing for that matter. On the positive side, there is nothing to deconstruct in order to build your own mudlib and there is more of a solid base to work from than something like Lil. The downside is that you will have to put in a lot of work to make a playable game from this. 

   Runs under: MudOS v21.7b23 (native) 
 * Heaven 7 
   A mudlib that essentially extends LPMud 2.4.5 with all the player features you always wanted such as classes, skills, and unlimited levels. It is well-suited to LPMud 3.2, but poorly suited to the other drivers under which it runs. 

   Runs under: LPMud 3.2 (native) 
 * Lil 
   A small, essentials only mudlib. Designed basically to give you examples of files as they must minimally be for the MudOS driver to run. Only useful if you plan really to write something totally from scratch. 

   Runs under: MudOS (native) 
 * LIMA 1.0a5 
   This is a brand new library, featuring the new MudOS natural language parsing package and a UNIX-like wizard shell with output redirection and command piping. In addition, it is a very modular, object-oriented mudlib with stack-based security. 

   Runs under: MudOS v22.1b4 (native)
 * LPMoo 
   A MOO simulation using LPC. This library allows you to work and play exactly as if you were using MOO instead of LPC. 

   Runs under: DGD (native) 
 * LPMud 2.4.5 
   The most well-known mudlib in existence. It is rather simple, not the best design, but if you know it, it is useful. Also, the widest range of drivers support it. Good for putting up and running a mud quickly. It is very ancient and inferior in design, flexibility, and functionality to modern mudlibs. 

   Runs under: DGD (non-native), LPMud 3.2 (non-native), LPC4 (non-native) 
 * Melville 
   Extremely minimalist mudlib for DGD. Documentation is sparse and it has few features. According to Dworkin, "Unfortunately it was never finished and today it is rather out of date. It does not work with recent versions of DGD." 

   Runs under: DGD (native) 
 * Shattered World 
   Mudlib to go with the Shattered World driver. It supposedly has a system for doing detailed economic and predictive analysis and is a distant descendant of the LPMud 2.4.5 mudlib. Other than that, I know absolutely nothing about it. 

   Runs under: Shattered World (native) 
 * TMI-2 1.4 
   Generic, designed for those who want to tinker around with their mudlib rather than get a mud up in no-time flat. Designed to be easily modified and comes with a full-range of intermud support as well WWW support. Features include the ability to take over monster bodies. Downside is its poor design and performance. 

   Runs under: MudOS v21 (native) 
 * TubMUD 
   Very intricate, and, according to Rust, "it is beautiful if you can figure it out." Intended more for Tub wizards to run at home than for wide-release. 
   
   Runs under: LPMud 3.2 (native)

If I have missed a lib, or stated something incorrect about your server or mudlib, or simply ommitted something, don't go flaming me. Email me the correct information so I can include it in the FAQ. I did my best to be fair in this, but in simply undertaking this task I have opened myself up to flames from anyone who I might have gotten wrong or simply does not like what I said. So please be gentle, and understand I mean no malice or ill-will anywhere in there!   

_________________________________________________________________

### What about _Nightmare_?

_Nightmare_ was removed from distribution by its author. No new muds may be built using this software. The Dead Souls mudlib, however, is a public domain version of the last available release of the Nightmare mudlib in a less user-friendly format.

_________________________________________________________________

### What copyright issues are involved with using someone else's code?

Some of the software listed above was written by a single person. Other works are collaborative efforts. Of all of these, I know of only Dead Souls as being in the public domain. In other words, the authors have retained the copyrights on their code or assigned them to a larger group, yet thay have decided to allow others to use their code for free.

Because these works are protected by copyright just like any other software you use, you may only use the software as long as you are not in violation of its licensing restrictions. The most common licensing restriction is to prevent commercial use without paying the developers a licensing fee. You need to read the licensing agreement of the software package you chose to determine if you can live with whatever restrictions it imposes.

_________________________________________________________________

### But I have changed their code!/I don't see any copyright!

There are two points to be made to anyone making these statements. The first is moral, the second legal.

First of all, you used the original author's software. You did not have to use it, and they did not have to let you use it. Playing legal games based on legal technicalities (real or imagined) is slimey and unethical. The author of any code you use deserves your respect for their wishes regarding that code.

Of course, there are people out there who cannot be bothered with issues of ethics. The question in their minds is, "Can I get away with it?" The answer is that you don't have a legal leg to stand on. Let's deal with the last question first. Any work--software, poetry, books, plays, films, etc.--is copyrighted from the moment it is created. No action is required by the author of the work in order for it to be protected. Certain actions (or lack of action) can weaken the protection an author has, but only two things can end that protection altogether:   * The author assigns, in writing, ownership of the work to another     person or entity.   * The author places the work, in writing, into the public domain.      Note that in either case, the author has to take a very specific action and has to do it in a very formal legal sense in order to end copyright protection for themselves. _Copyright laws do not require the author to register the work with any organization or government agency_.

While you may think the fact that you live in a different country from the original author is protection enough for you, guess again. Copyright laws in most countries, while not identical, derive from a treaty signed by most countries. The net effect of this treaty is that copyright laws are very similar from one country to the next.

As I stated earlier, there are things an author can do to weaken or strengthen their case in the event of a copyright violation. The degrees of strength of protection exist because there is a mild defense against copyright violation: ignorance. If a person can prove that they had no way of knowing a work was copyrighted (they believed it to be in the public domain because they believed either the author had placed it there or because the work was so old that copyright protection had lapsed). In this case, a person is limited in the damages they can suffer. The simplest action an author can take to protect against ignorance is placing a © along with their name and the date of the work's creation in a prominent location within the work. If it says it is copyrighted on its cover with a date within the last 75 years, a defendent cannot possibly claim to believe the work was in the public domain.

Of course, the other approach is to claim that the original author is not in fact the original author. This is where registering a work comes into play. By registering a work with an appropriate entity (like the Library of Congress in the United States), an author can prove that a given work is associated with them at a given time. If someone else wants to claim authorship of that work, they will have to prove the existence of the work in question prior to the date it was registered. There are even simpler ways of proving a work's authorship, such as mailing yourself a copy of your work without opening the envelope. Note, however, that such tricks are less authoratative than registering with an appropriate entity.

So you are convinced you cannot claim the work is not copyrighted. What about works that have been changed? You are still out of luck. A work based on another work is considered a derivative work and thus subject to two copyrights: the author of the original work and the author of the modified portions of the new work.

With respect to a derivative work, the first question is: do you even have the right to create a derivative work? Since the original author has a copyright on the original work, that person gets to specify the conditions under which you may use the original work. It is therefore possible that you are not even allowed to change any of the original. I do not know of any LP-related open distributions that prevent derivative works. Some works do, however, restrict what you may do with a derivative work (the GPL is a good example of a license that places restrictions on derivative works).

_________________________________________________________________

### Where can I find all this stuff?

These first set of sites are generic "goto" sites when looking for LPMud stuff:

  * ftp.bat.org   
  * ftp-na.imaginary.com (North America)   
  * ftp-eu.imaginary.com (Europe)   
  * ftp.imaginary.com (General)   
  * ftp.lysator.liu.se        

In addition, the primary site for individual pieces of software:

  * CD (server and library)
    ftp://ftp.cd.chalmers.se/pub/lpmud/
  * DGD (server)
    ftp://ftp.imaginary.com/pub/LPC/servers/
  * Discworld (library)
    ftp://ftp.imaginary.com/pub/LPC/lib/
  * Final Realms (library)
    ftp://ftp.imaginary.com/pub/LPC/lib/
  * Foundation (library)
    ftp://ftp.imaginary.com/pub/LPC/lib/
  * Heaven 7 (library)
    http://www.dialnet.net/users/mud1/dload.htm
  * Lil (library)
    ftp://ftp.actlab.utexas.edu
  * LIMA (library)
    ftp://ftp.imaginary.com/pub/LPC/lib/
  * LPC4 (server)
    ftp://ftp.lysator.liu.se/pub/lpmud/drivers/profezzorn
  * LPMud 2.4.5 (library)
    ftp://ftp.lysator.liu.se
  * LPMoo (library)
    ftp://ftp.ccs.neu.edu/pub/mud/mudlibs/
  * LPMud 3.2 (server)
    ftp://ftp.nightfall.org/pub/games/lpmud
  * MacMUD (server)
    http://www.eden.com/~hsoi/mud
  * Melville (library)
    ftp://ftp.ccs.neu.edu
  * MudOS (server)
    ftp://ftp.imaginary.com/pub/LPC/servers/
  * Shattered World (server)
    ftp://moo.cs.rmit.edu.au/
  * TMI-2 (library)
    ftp://ftp.imaginary.com/pub/LPC/lib/
         
_________________________________________________________________
                                      
### Help! I can't get my driver to compile, what should I do?

Thanks to Rust for putting together an answer for this question.

First of all, learn how to redirect stderror to a file if you don't already know how, or at least find a computer where you can cut and paste. Then, you have 3 options for getting these errors to a more experienced driver person:
 
 * You can try The Idea Exchange a mud dedicated to mud development, where people who may be able to solve your problem, or at the very least you can post it to your target driver's newsgroup on The Idea Exchange, where they will be seen by knowlegeable people fairly quickly. In addition, for Lima specific compile problems, you can visit its support site Lima Bean (telnet://lima.imaginary.com:7878).
 * You can post it to rec.games.mud.lp, but don't cross post, and it probably wastes a lot more bandwidth on this newsgroup than on The Idea Exchange.
 * You can mail the maintainers of your driver:

   + CD: jacob@dd.chalmers.se
   + LPC4: hubbe@lysator.liu.se
   + LPMud 3.2: amylaar@cs.tu-berlin.de
   + MudOS: tim@handel.princeton.edu    

For MudOS or DGD help, you are most likely to get a timely response by posting to the proper newsgroup on The Idea Exchange (ie.imaginary.com 7890). For LPC4, your best bet is direct mail, for CD, either direct mail or visiting Genesis (hamal2.cs.chalmers.se 3011) and mailing Tintin et al.

_________________________________________________________________

### I have applied patch XXX, and now nothing works any more.

_Answer from Joern Rennecke (Amylaar)_ Have you supplied the proper -p option to patch? If not, you might end up with a patch applied to the wrong file. Check with the appropriate man page to "patch" for more details.   

_________________________________________________________________

### How do I do ANSI colours?
 
There are several misconceptions about colours. The first misconception is that all of the world is an IBM PC using ANSI style colours. In fact, there are many different sets of escape sequences which have the same effects depending on terminal emulation. If your goal is providing colour support to players, then limiting yourself to just ANSI support is very similar to saying "Only people with IBM compat's can play my mud." Well, maybe not quite that drastic, but you get the point.
 
Also, you should keep in mind that the term ANSI has nothing to do with colours. ANSI is a standards organization, and one of the zillion things for which they have standards is escape sequences and what they do. Keep in mind that your goal is to have colours.
 
Finally, about giving your mud colour support. The Discworld Mudlib has developed a protocol now supported by at least Dead Souls, Foundation, Lima, and TMI-2. There is no reason, however, that other libs cannot add support this protocol. It enables creators to code to a single set of codes and have those codes dynamically interpreted into colours proper to the terminal emulation being used by a given player. If a certain player has no colour support, that person does not see the colour codes. For more information on this protocol, stop by The Idea Exchange at ie.imaginary.com 7890.   

_________________________________________________________________

### Why not just hard code the colours?
 
There are multiple colour escape sequence protocols. Some players cannot support colour escape sequences at all. Sending colour escape sequences to people who cannot handle them, or to people who use different protocols can mess up their displays severely, making the game unplayable.

_________________________________________________________________

### How to I make the mud use vi/emacs instead of ed?
 
This question gets asked constantly. When you come around to ask it, think about what exactly you want. Do you want to have vi or emacs on your mud? Or is it that you really want to have a convenient way of editing mud files (which ed certainly is not)? In truth, the real problem is the need for something more convenient than the very inconvenient ed which muds use. The kneejerk response to this need is the belief that your UNIX editing tools will solve this need. The fact is, however, there are better ways to accomplish this goal which are listed in Section III: Can I code offline?
 
Not convinced? There are the technical reasons that people often give, such as the fact that any visual editor will require character mode, which is non-trivial in the current batch of muds and very network intensive. The bottom line as to why this is not generally done is that it provides nothing, yet costs a lot.   

_________________________________________________________________

### Is it possible to connect multiple muds together?
 
Is it possible? Yes.
 
Why do you want to connect muds? There are two common meanings behind this:

  1. Distributed mudding
  2. Connecting multiple muds

Distributed mudding is basically a single mud whose resources are spread across multiple servers. Distributed anything is generally required of resource intensive, mission-critical applications. muds are not, in the scheme of things, resource intensive and they generally are not mission-critical applications. Distributed computing basically gives you the ability to expand horizontally rather than vertically. That means instead of buying yourself a sparc 20 to run your mud, you can architect it in such a way that two sparc 2 computers will give the same performance.

The fact of the matter, however, is that no mud currently in existence uses the resources which require this kind of scalability. In addition, most MUDs have a hard enough time finding one site, much less getting two.

More commonly, however, people are thinking of the ability to connect multiple MUDs together. Before deciding this is a good thing, you should define the problem you want solved by connecting muds. As of yet, I have not heard a problem which connecting muds solves. The most vocal reason is to allow a person to have the same character across multiple muds. At that point, however, you have to define _what it is to be that person_. Most people will quickly say that what defines their character is that they control it. If that is the case, then connecting muds does not solve this problem. A client which allows the person to login to multiple muds is what solves this problem.

The response then might be to have the same level/skills/whatever across the multiple muds. At this point, however, they cease to be multiple muds connected, but instead one huge distributed mud. This would be a poor way to design a distributed mud, and would also lead to political headaches and a huge waste of creative talent.   

_________________________________________________________________

### Can a mud server run on DOS?

Yes, most of the servers have DOS binaries available. In addition, most of the mudlibs have had their files arranged and ported so they fit in the FAT 8.3 naming scheme. If you wish to allow others access to the mud over modem lines, be sure to get the comdrv17.com file with your server and mudlib. For those who choose mudlibs with colours in them, the current batch of drivers was compiled in such a way that the drivers do not send output through ANSI.SYS (thus no colour).   

_________________________________________________________________

### Can a mud run under AmigaOS? OS/2? Windows NT? etc...?

These are the ports of which I am aware:

  * AmigaOS
    DGD, LPMud 3.2, 3.2.1, MudOS
         
  * Atari
    DGD, LPMud 3.2, 3.2.1
         
  * BeOS
    DGD
         
  * System 6
    MacMUD (which is LPMud 3.1.2), DGD
         
  * MacOS
    MacMUD, DGD
         
  * OS/2
    DGD, LPMud 3.2, 3.2.1, MudOS
         
  * Windows 95
    DGD, MudOS
         
  * Windows NT
    DGD, MudOS

_________________________________________________________________

### Credits

Credits for information in this FAQ beyond the information provided by the author:
 
> Abigail, Stig Bakken, Jose Corrales, Felix Croes, Joshua P. Dady, Lars Duening, Paul Gregg, Monique Girgis, Erwin Harte, Tim Hollebeek, Pelle Johansson, Andru Luvisi, Joern Rennecke, Danne A Solli, Christina Sterman-Hack, Lars Syrstad, Pekka Timonen, Linus Tolke, John Viega, Petri Virkkula

_________________________________________________________________

Copyright (c) 1994-1998 George Reese This document may not be reproduced outside of USENET newsgroups, ftp archives, electronic mailings, and other similar not for-profit endeavors without the express written consent of George Reese.   

_________________________________________________________________                                    

This FAQ is maintained by George Reese, borg@imaginary.com
