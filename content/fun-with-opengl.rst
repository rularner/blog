:title: Development environments
:category: Development
:author: Rusty Larner

When I started to write this article it was a reminder of how long I've been working with computers.  The Commodore 64 I started out with was just a basic <heh> editor; my brother and I spent a week typing in the code for a basic shoot-em-up (and a week more debugging the typos we made - wheee gosub!).  When I got to college, I started programming on 'real' hardware; Cal Poly had an AIX system, the Computer Science department somehow wrangled a Sun Irix system (with the first introduction of GL - no, it wasn't "open" yet!).  This was the beginnig of the vi/emacs wars; I came down firmly in the vi camp, mainly because at the time vi was far more likely to be installed on the systems I was working on.  After I graduated, I moved on to IDEs; first Visual Studio, then Eclipse.

Well, that was a wonderful trip down memory lane.  One of the things I started to feel in the IDEs was their limitations; I am currently working on projects that typically span multiple languages and platforms.  Plus, as I've matured as a programmer I've moved away from using a mouse (Just last week I was writing in C++, JavaScript, HTML, and Python, on EC2)  IDEs are just too heavyweight for that situation, so I (somewhat happily) went back to my roots; and found they have moved on!  Discovering the changes to vim has been a pleasure; just last week a co-worker turned me on to tabs.

In addition, I'm upgrading my shell game; switching from my old bash standby to zsh.  (You have to love any shell that has a standard plugin framework called oh-my-zsh)  These two combined have reduced the amount of typing I need to do each day, which also means I can get my work done faster.  There is definitely some muscle retraining to do; for example, I am still more likely to manage vim instances via ctrl-Z jobs than editor tabs.

Since I've been working on multiple different systems recently (setting up EC2 machines, trying to test locally on VMWare instances, etc.), I've also started to delve into the world of github-managed dotfiles (http://dotfiles.github.com).  Hopefully soon I'll be able to have the ideal zsh/vim configuration mirrored across every machine I'm on without needing several scp's each time!

