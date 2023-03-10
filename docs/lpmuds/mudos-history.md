From: erikkay@hulu.next.com (Erik Kay)
Newsgroups: rec.games.mud.lp
Subject: MudOS (long)
Message-ID: <4887@rosie.NeXT.COM>
Date: 28 Aug 92 21:38:14 GMT
Sender: news@NeXT.COM
Lines: 190


(just so you know ahead of time, this is
wayfarer@portals|tmi|overdrive, so this post will obviously be a bit
biased towards MudOS.  I'll do my best to be objective here though,
and give you the whole scoop on this name business.  Also be warned
that this post is somewhat long.)

sigh.  I kept telling myself that I was going to avoid this silliness.
I detest net flamewars with a passion.  However, things have gotten
out of hand here.  Many things that have been said are simply false.
People are attacking not only what we've worked on (MudOS), but also
attacked us (Jacques, Truilkan and myself) on a personal level.  Is
there really a need for all of this?  Can't we keep this rational?
sheesh.

The project originally began because a few of us at TMI got together
to talk about the driver.  We sat down to do exactly what people have
been suggesting, to try to pool everyone's personal mods and ideas for
the driver together and do them, since lars hadn't been responding to
diffs that were mailed and rumor had it that he was going to stop
taking diffs altogether.  (this is not a criticism of lars.  He's very
busy now, and I think he maintained the driver much longer than many
others would have in his situation) As you all know, this actually
happened shortly after we started (we began development around the
3.0.52-3 time frame).  We saw the need to continue enhancement and bug
fixing on the driver.  However, we also wanted to not be encumbered by
strict compatibility with the lars driver.  Thus we have never claimed
that we were compatible with lars' driver.

When the project originally started, Whiplash and I were really the
only ones maintaining the code.  We were calling our version of the
driver <lars-version-number>A (for American version).  This worked
fine at first, but as he and I made more and more changes, we were
developing internal versions much more quickly than Lars was, so we
began piggybacking on top of the A.  So our version numbers began to
look like this: 3.0.53.A2.2.  Again. this worked fine at first, but
then when lars finally released 3.1 and the last two followups after
it, it became very inconvenient to use this version numbering scheme.
Around this time, Truilkan started helping out as well, and things
became even more confusing with three people at three different points
in the country trying to do coherent version control.

Another thing that began happening around this time was that our
incompatibilities were becoming noticeable to people using our driver.
People who were using it on their sites and people at TMI were always
complaining that certain things didn't quite work in the same was as
their 2.45 driver or even in some cases, as their 3.0 driver.  People
seemed to assume that it would behave the same way, and didn't
understand why compat mode didn't work.

The final thing that came down to us deciding to change the name was a
discussion that Buddha and I had one day.  We basically wanted to
release a mudlib / driver combination that was easy to build almost
anything on top of.  Not just your standard fantasy mud, or even any
of the other many genres of MUDs out there.  We were bouncing ideas
around of what people could do with muds, and the problems almost
always came back to the fact that rewriting a mudlib from scratch is
always a major time constraint considering that nobody is getting paid
to do this, and most groups of people working on MUD projects aren't
close to each other. (MUD's are a horrible medium for trying to design
something or even to communicate simple ideas) At any rate, a lot more
was bounced around here, but the end result was talking about this
driver / mudlib combo we called 'mudos'.  We weren't even talking
about it with respect to the driver we were working on necessarily.
It was just an idea.  (and don't bother flaming that this isn't
original, etc., etc.  I know.  I never claimed that it was, or that
the idea was even particularly good.  It was just an idea that we
wanted to do something about at that point.)

So a few versions pass, and we finally got fed up with having to
answer the incompatibility question, and with having a broken version
numbering scheme.  So we decided that we wanted to start our version
numbers over.  We were originally just going to call it LPCA, but
instead Buddha (or myself, I forget) suggested that we call it the
MudOS enhanced LPmud driver.  This was suggested jokingly, and we
thought it was pretty funny at first, but eventually decided that it
actually sounded pretty cool, and that if we ever decided to do the
generic driver / mudlib project, that this would fit in nicely.  We
knew that we were going to be making a sizable number of additions and
cleanups to the driver before we really thought we would be 'done', so
we started at 0.8 rather than 1.0 on the version numbering.  After a
few versions down the line, we stripped the name in the version string
down to MudOS driver rather than MudOS enhanced LPmud driver, because
we felt the name was too unwieldy (it still remains as MudOS enhanced
LPmud driver in our docs).  Recently, we took out the word 'driver'
for the same reason.

Now, you might argue that changing the name was premature at that
point.  We had changed a significant amount of code, but the
incompatibility list was still relatively small, and it was
essentially an LPmud with a few new toys on it and a few more bug
fixes.  I still stick by that original decision however.  As you can
see, (if you believe that I'm not simply lying outright) none of the
decisions to change what we referred to the driver as were to enhance
our own personal glory or to try to downplay lars' part in the driver
(almost all of it).  We changed the name in the version string because
(a) we're not compatible with standard 3.0 mudlibs. (b) we wanted a
convenient version numbering scheme (c) we wanted to differentiate
ourselves from being "yet another custom hacked lpmud driver".  I'm
sure that these are some of the same reasons that genesis' driver name
was changed to 'cd'.  They were able to restart their version
numbering, they aren't confused with standard lp drivers, and they are
definitely not thought of as just another hacked driver by most
people.  One further enhancement to (c) is what Johan pointed out:
it's better marketing.  It sounds cooler.  We wanted people to use it
(at least partly because tmi's mudlib depends on its features).
However, we were never attempting to gain personal fame, or trying to
degrade lars.  We didn't start calling our driver MudOS for any other
reason than what I have described above.

Let me respond to a few specific comments now that I've given you the
whole story.

First of all I noticed that there are two groups of people attacking
us: people with their own custom drivers, and people who want one
stable driver to use.

To the Lars faithful who want one driver: he's a busy guy.  He has
said that he doesn't plan to release a further version of his driver
that has anything other than bug fixes.  He doesn't plan to add any
functionality.  That's one reason why there are so many different
drivers.  So how about the rest of us all getting together and forming
a committee and putting together one driver?  Well, that's what MudOS
came from.  Originally, people at TMI got together and asked everyone
who was modifying their driver to get together and discuss bringing
all of those changes together.  I believe that an invitation to this
meeting was even posted to rec.games.mud. (sulam?  buddha?)  About 10
people showed up and we all talked for a while.  For a month or two,
we had a bulletin board where all of us posted ideas / suggestions /
etc.  However, nobody really had the time to get together and work on
the code.  Whiplash took the initial responsibility together and
merged in lots of changes from various people.  But then the people
slowly began to filter away, and in all of that, Whiplash and I were
really the only ones that were modifying the code directly.  Then
truilkan came along, then jacques a while later.  Along the way, many
others have been contributing pieces of code to us, and helping us to
test the driver.  It's worked out surprisingly well (except for having
multiple people working on the source across the country (and
world)... that's always been a pain to do remotely).  But to get
*everyone* together to agree?  That would be next to impossible, and
the result would probably be crap.  That's why a number of people left
the project early on.  They didn't agree with the majority, and
weren't interested in being a part of it.  You can't make everyone
happy.

To the people with other drivers: we have never claimed "our mud is
better than yours".  We're not trying to make this a point at all.
We're just trying to make a good lpmud driver.  Yes, it's an lpmud
driver.  We never said that it isn't.  The reasons for calling it
MudOS are described above.  You keep saying that we're being
disrespectful, and stealing credit from lars.  This is simply not the
case.  We credit lars throughout the distribution.  He is responsible
for what we have.  Many of you have also stated that you believe that
all we have is a couple of hacks on top of the standard lpmud driver.
That we have no substantial differences.  Well, once again, we've
never said that we're not an lpmud driver.  But we *do* have
*substantial* differences.  Our communications are done completely
differently.  The backend was completely rewritten to be more
efficient, and to deal with socket efuns.  Function handling was
completely rewritten.  Much of the internal storage was completely
rewritten.  In fact, just about every part of the driver has been
significantly changed in one way or another.  That's not even talking
about the feature additions that have been made.  From a code
perspective, we are more different from the lpmud driver from which we
derived, than we are similar to it.  Before you make accusations like
this, you should have at least looked at our driver to verify your
claims.  They are simply false.  Maybe you have modified your driver
to that extent as well.  That's great.  Once again, we've never said
"ours is better than yours".  The point is that we're trying to make
useful modifications to the driver, and to make that driver publicly
available for everyone to use.  Because of that, our situations are
different.  Being involved with TMI, we're interested in supporting
these people, fixing bugs that affect them, adding features that they
request.  You might call your driver an lpmud driver.  I would also
call MudOS one.  However, it has a different name, so that there is no
confusion that there are significant differences and incompatibilities
between the two.  If you were distributing yours, and you cared about
helping people who might want to use it, you would have to at the very
least add some tag to your name to differentiate your driver from
lars'.

To the people of genesis: Thank you for keeping this discussion
rational to some extent.  I think that you understand where we're
coming from here.

All flames to /dev/null.  As I've said, I'm not interested in a flame
war.  I simply wanted to clear up some of the misconceptions that have
been thrown around here.  I'd be more than happy to have a rational
discussion with people who aren't solely interested in trying to flame
us in to the ground for no good reason.
