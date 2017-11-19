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

