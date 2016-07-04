## Why Keep a Notebook?

Well, for one, unless you plan on keeping everything in your head forever, you're going to forget things. And those things you forget will come back to bite you, sometimes lightly, sometimes not so. Sometimes it's just a few wasted seconds re-finding a wiring diagram; sometimes it's days of searching for that one thing you did to make the damn thing boot.

For another, there's the people who follow. We're never getting anywhere quickly if we spend our tiny human lifetimes trying to solve the same problems. There's also times where one person's unfinished experiment holds the breakthrough for someone else's project \(maybe even for the same person!\) Keeping notes and information around benefits everyone, even if the upkeep can be a bit of a pain in the ass.

## How to Keep a Notebook

I'm not going to be very prescriptive here-- Just use systems that work for you.

I say systems because you're hopefully going to be holding onto lots of types of data, and there is no one perfect system for storing it all.

For example, I'll give an overview of my personal systems:

* GitBook: Logs, Links, anything written that isn't essentially code
* GitHub: I tend to keep a repository for a category of interest \(A board, an engine, a sensor\) and load my experimental code into it for safe storage and easy searching.
* OneNote: Private thoughts, things I want to write by hand or draw.
* Pinterest: Inspiration

If I had to offer some tips as to what systems you should use to store your data, I'd say it should be easy to backup, easy to search, and easy to access in less than ideal conditions \(no wifi, for instance\).

## What to keep in your Notebook

Now for the fun part; what to keep in your notebook. As a rule of thumb, I go by the idea that storage is cheap, and better to have it and not need it than need it and not have it. The only temepering notion to this is the idea that your notebook should be easily searchable-- if you do keep absolutely everything you probably won't have the time or energy to store it in a way that makes it easily searchable.

That being said, these are generally the documents I keep during various events and tasks

### New microcontroller, board, non-trivial sensor or peripheral

I tend to create a section in GitBook or my main wnitten system with the following:

* Link to the product page where I got the thing
* Data Sheets
* Link to any tutorials I find useful \(SparkFun and Adafruit shine here\)
* Link to any working sample code, regardless of language

That's before I start playing with the new toy. When I'm ready to take a hack at it, I start a repository or create a new folder in an existing, related repository. There, I start scaffolding with:

* folder containing the sample code for annontation/modification
* A quick notes.md file for notes to be moved back to my main note source
* A setup.md for notes on setup
* A folder for my experimental code

I then add a link to this repository to my main notes source. I usually keep the notes source open as I work, as the information inside tends to be highly relevant towards my goal of understanding and using a device.

If the device has working sample code, especially if it's not in my target language, I create a pseudocode section in my notes section for the device-- I find translating code line by line from one language to another rarely works for me, and the pseudocode layer helps me think and see the big picture.

Whatever I end up doing, I try to summarize it and keep a log in my notebook-- this both helps me spot problems in my methods and helps prevent me from making the same mistakes or trying the same solution multiple times.

### Starting a new project

This usually begins with a section in my notebook that already contains logs and attempts to refine the idea from an abstract concept to hints at how I would tackle an implementation. After that, I search for the notes for each component I'll need and create a list of links that will be handy later when I need a specific data sheet or need to remember exactly what math I need to do on the raw data for a particular sensor.

Then, it's-- and you may have guessed this by now-- logs. Wiring diagrams. PoC sketches/code. Mind maps of ideas. Pseudocode. Sometimes even CAD drawings or .stl files!

When keeping logs for a project, keep things sorted chronologically-- it tends to help if you have conflicting answers to a problem in your notes, and it can be useful to review the overall evolution of a project.

# An example of a journal entry

I learn by doing, and barring that I learn by wtching someone else work. So in this section I'll be placing the notes I took during a November 9th 2017 stream in which I attempted to add the SX1509 GPIO expander to the Johnny-Five Library. I've added some posthumous notes for explanation.

## Pre-Stream

Notes: I gathered some information that would expedite my work mid-stream-- I hate long silences in my stream, so I try to do a little research beforehand. Keyword try.

Datasheet for SX1509: Sparkfun C++ lib for SX1509:

Note: I'll cover this in reverse engineering, but I find libraies written in languages other than the one I'm using very useful when writing new code.

Goals for the stream:

* Get Digital Out working
* Get Digital In working
* Get PWM out working

## During the Stream

Note: I walked the viewers through what I'd be doing that night, and set up the camera to wire up my demo rig; I forgot to collect the materials beforehand, but luckily this was in some weird reality where my shop was organized, so locating the parts went smoothly.

Parts used:

* Arduino Uno \(Note: ease of use with johnny-five was a total factor here\)
* SX1509 Breakout from SparkFun
  * \(Note: I should've explained to viewers that these need soldering and that I had tried many configurations of pin and socket headers before landing on one I liked; this is the kind of info I love to see\)
* 4 pin-to-socket breadboard cables
* 2 pin-to-pin breadboard cables
* 1 LED
  * \(Note: I explained to my viewers that because the SX1509 does 3.3V power, I didn't need a resistor\)



