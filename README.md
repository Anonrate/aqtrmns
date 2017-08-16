# aqtrmns
AqTrmns - (Terminus Font - This is what you've been looking for)

I've still a lot of work to do, so I'm just going to say this for now.

I would like to add that I thank you so much sheckley (Dimitar Toshkov Zhekov)
for creating this wonderful font.  It is truly one of a kind.  I've always
been very picky with fonts.  Once I first saw your font, I was sold instantly.
Despite the updates prior to v4.40 being 3 years and this being a bitmap font..
Even though I had a lot of troubles trying to get this font to work when I
first found it..  I have learned a lot about the work that goes into creating a
font.  This has inspired me; you have inspired me to create my own font and
learn about what it takes to actually creat a font and all the work.  It really
is a lot of work and I am just getting started.  I have a lot of work ahead of
me, but I know it will be worth it.

My goal is port your font over so it's scalable and still looks pretty at
larger sizes.  I am aware that there is applications that can trace the gylphs
such as Potrace and AutoTrace, but they do not nearly do the justice that you
and this font deserve.

Once again, thank you for all of your hard work.  I was hoping send you an
email but there was no contact information to do so.  I really hope you see
this beacuse as said..  You deserve the appriciation.

Anonrate

# Table of Contents
* [Introduction](#introduction)
  * [What is Terminus?](#what-is-terminus?)
    * [Screenshots](#screenshots)
    * [Character Variants](#character-variants)
  * [Process](#process)
* [Requirements](#requirements)
* [Installation](#installation)
  * [Retrieving the Code](#tetrieving-the-code)





## Introduction
**AqTrmns** (or Aq *Terminus*) is a remake of the
*[Terminus][terminussite]* font created by [sheckley (Dimitar Toshkov Zhekov)
][sheckley].

The main goal of **AqTrmns** is to provide a *true* and reliable scalable
variant of [Terminus](terminussite) so it can even look pretty at larger sizes,
and accommodate people with a higher screen pixel density.

### What is Terminus?
This is what is stated for what [Terminus](terminussite) is on the
[Main Page](terminussite).
> Terminus Font is a clean, fixed width bitmap font, designed for long (8 and
  more hours per day) work with computers. Version 4.46 contains 1291
  characters, covers about 120 language sets and supports
  ISO8859-1/2/5/7/9/13/15/16, Paratype-PT154/PT254, KOI8-R/U/E/F, Esperanto,
  many IBM, Windows and Macintosh code pages, as well as the IBM VGA, vt100
  and xterm pseudographic characters.

#### Screenshots
These are some screenshots with [ao2](#ao2) and [gq2](#gq2) applied.  These
images are provided to you from the [Terminus](terminussite) itself.
<details>
<summary>Screenshots</summary>
Seems that I'm not able to show the screenshots directly from
[here][terminusshots] even though it worked the first time I tried it...
</details>

#### Character Variants
<dl>
<dt><a name="ao2"><b>ao1</b></a></dt><dd>ao1 ![alt text](ao1img) =>  ao2 ao2 -
  nice, but sometimes hard to distinguish from 'o'.</dd>

dv2 dv2 => dv1 dv1 - due to character matrix limitations, the printing de and
  ve are of slightly worse quality.

ge1 ge1 => ge2 ge2 - only for 0433, 0453 and 0491, not 0493 and 0495

<a name="gq2"></a>: gq1 gq1 => gq2 gq2 - some programs still use \` and ' as
  single quotes.

ij2 ij2 => ij1 ij1 (also short i)

ka1 ka1 => ka2 ka2 - the high cyrillic ka is used as decorative in Bulgaria;
  the latin 'k' is always high, of course.

ll1 ll1 => ll2 ll2 - should pass the il1I test (depends on your resolution and
  monitor quality), but the horizontal alignment is a bit worse.

td2 td2 => td1 td1 - perhaps td1 should be the default

hi1 hi1 => hi2 hi2 - higher upper case letters, digits etc. for size 18 - looks
  better, but there is even less space between the lines.

br2 br2 => br1 br1 - a bit more similar to Braille. X11 only, no Windows code
  page includes unicode range 2800-28FF.

### Process
The process is quite simple once you get the hang of it, but it's just rather
tedious and even more so if you have <abbr title="Obsessive Compulsive
Disorder">OCD</abbr> because everything literally has to be *Pixel Perfect*!
It's a real pain in the ass when you notice one fucking thing is off.
Sometimes it results in me redoing everything...

Currently [Terminus](terminussite) is just a bitmap

## Requirements
<sup>
  This needs to be populated once a script been made to install the font.
</sup>

[terminussite]:http://terminus-font.sourceforge.net/ "Terminus Font Home Page"
[sheckley]:https://sourceforge.net/u/sheckley/profile/ "sheckley profile on
Sourceforge"
[bitmapfonts]:https://en.wikipedia.org/wiki/Computer_font#Bitmap_fonts "Bitmap
fonts"
[fontforge]:https://fontforge.github.io/en-US/ "FontForge Open Source Font
Editor"
[terminusshots]:http://terminus-font.sourceforge.net/shots.html "Screenshots"

[ao1img]:http://terminus-font.sourceforge.net/img/ao1.gif "ao1"

## Installation
Installing the **AqTrmns
## Retrieving the Code

**As of right now I have *Partially* finished the following:**
* Numeric Characters have been traced
* Upercase Alpha have been traced
* Lowercase Alpha have been traced
* *All* punctiation have ben traced

Please note that right now the main priority is English.

### Issues
Some issues that we are currently having is that once the font is generated
with **FontForge**, the font is being recognized as a *Monospace* font.  Now I
have gont a head a used the font anyways in **Konsole**, but it is very clear
that it isn't being recognized as a *Monospace* font.

Right now I would say that is the issue that is of most importance right now.

I have just recently gotten into the understanding of creating a font so I am
very new to this area but I am rather very much enjoying it and am sure there
is still lots that I have to learn.
