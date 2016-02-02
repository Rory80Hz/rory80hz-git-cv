# From Zero to Principal Architect
## Introduction
### What the hell is this?
This is a story about how I travelled through time to my current work position. It is a living CV, documented with Git branches, detailing not just work expierence, but experience in general. 

### CVs are bad M'Kay
CV is the wrong word. We are badly served by CV's.

They are a checklist of buzz words, we all know we twist and turn them in different ways to suit the job description presented, to sell yourself into a role, to sell a role to a client, to sell an idea...we all know how it works, you stick in the relevant experience tailored to fit the bill, the recipient scans it for blatant lies and inconsistencies, barely reaches passed year 3 or 4 on the list and decides whether you are worth a closer look.

### An Alternative Proposition
The person you are is much more than that...it is years of collected experience, decision and indecision, events beyond our control, seemingly unconnected ideas, interests and opportunities. 

Hence this little experiment. It was born out of a conversation with [Peter Campbell](https://medium.com/@petecam), a fellow Kainos person, where we wanted to figure out what it is that made us the people we are and why we are in the roles we found ourselves in, and how can we share that experience with others.

There must be something more than just time served amongst 'Enterprise' architecture and beyond, more than sticking down really unhelpful tags on a CV like 'XPATH EXPERT'. This won't be for everyone, but hopefully if it resonates with you, let me know on twitter [@rory80hz](https://twitter.com/rory80hz) and if you are looking for a job, also, let me know, you might be the sort of person we are after.

### Right Now.
This is the bit that will change as time goes by, but right now, I am Principal Architect with Kainos, working in their Gov BU, currently engaged with GDS as Product Manager for the Government PaaS offering.

PaaS done right is an immense game changer, so this is a super cool thing to be involved in. I'm also massively interested in how to make things better for teams building services, users as a first class citizen, design, security, operations and testing. 

> "Yeah right, you are mad into everything?" 
>
> _You, just now_

Yes...pretty much, Why? well, thats the point of this excercise, lets see if I can figure that out.

### How do you use this thing?
Well, it's Git. Git reprents the divergence and convergence of code over time. Well, how about instead of code, we use that to represent ideas. Ideas in the form of paragraphs of a 'Living CV'. Want to see the history as a timeline? Look at the git history in something like [Source Tree](https://www.sourcetreeapp.com/) or [gitup](http://gitup.co/). The words provide the narrative for the various ideas and threads.

![images/example.png](Example of the history)

## From Then to Now
### From Tiny Acorns
How literal is this. The first computer I ever used was a [BBC Micro](https://en.wikipedia.org/wiki/BBC_Micro), manufactured by Acorn Computers. My primary school a little National School in the countryside of County Louth in Ireland, was convinced by my Dad that they should get one. I don't know the details of this, but get one they did in 1984, I was 5. Very occasionally we would be allowed to use it and it mostly revolved around playing [this game](http://www.computinghistory.org.uk/det/38952/Granny's%20Garden/). That was that. I couldn't get away from computers.

Later we would eventually get a BBC Micro at home, and this is where I started mucking about with BASIC, retyping code from magazines, understanding not one bit of it to make utterly crude games, which would on reflection go on to inform a large part of my opinion and ideas around technology.

### Games - the early days
As mentioned previously, games played a decent part of my informal education on the hows, whys and whats of how computers work, and to an extent pushed things a little bit more than the standard 'oh kids these days they are great with technology' (no they aren't but that's a whole other story).

So in the early days what did I learn from games?

> That they are memory hogging nightmares that require you to bend things to your will.
>
> _Historic Rory, 1990s_

Allow me to explain, in between my BBC Micro experiences things evolved and changed, via Spectrums, Amstrads and Commodore 64s. With those things you tended to stick in the tape (let grandad tell you about tapes some time) or disc (let grandad tell you about discs some time) waited for 17 hours, and, if you didn't find yourself having some sort of seizure thanks to the loading screens, you had a game you could play. 

Basic write protection to 'backup' these games was usually defeated with a dual tape deck, or strategically placed selotape, and early lessons were learned here about the value of genuine backups...when the Amstrad decided to eat your tape, and the nearest option for a replacement was 30 miles away, and the internet was still the realm of R&D skunkworks and academia, not to mention crossing the border in the 1980s in Ireland to go to the one computer shop in the North East was not exactly good craic, having a replica was a necessity.

Anyway, more typing code verbatim happened with the Amstrads my mates owned, and the buzz you got from hours of effort that resulted in admitedly crap games appearing on screen was imeasurable, I miss that sufficiently that im going to do a course on game development over the next while, but really, for me, it illustrated the power of these whiring boxes, you could do anything with them!!!

Back to the initial statment, about them being memory hungry beasts. In the dawning of the age of the x86, our family acquired an 386, with an insane 640k of memory. It ran stuff like Wordstar and some Sage thing...AND GAMES. OH YES. BUT OH NO! You have insufficient memory...enter [memmaker](http://www.easydos.com/memmaker.html) this let you manage memory allocation, but in order for this to work properly it needed to run at startup...so this meant changing config.sys and autoexec.bat, through this I learned how computers started up, got forced into mucking about with BIOS settings and by sheer necessity (i.e. Populus clearly must run) learned more than I ever intended.

It also provided the one of the highlights of my IT career. My game playing reached intolerable levels, so my Dad enlisted one of his students (he lectured in Elecontric Engineering in a local Regional College) to create a password protection program. It was great, it started after boot, prompted for a password and if you didn't get it right, DOS wouldn't load. Sadly, my education in boot process thanks to memory wrangling meant two things.

1. I wasn't scared to go poking around things
2. I had a suspicion where this Password protection program might get called (autoexec.bat)

On my next allowed compute time, instead of going straight to games, I discovered the batch file that called the program, found the program, found it stored the password in plaintext, made note of said password, and then used it to get onto the PC every time I was unsupervised.

Some really valuable lessons learned, namely:
* Don't be afraid to try things out
* Learn as much as you can, you don't know when unrelated things come together to form an answer
* Don't admit you know the password to a system, because someone will change it