## Games - the early days
As mentioned previously, games played a decent part of my informal education on the hows, whys and whats of how computers work, and to an extent pushed things a little bit more than the standard 'oh kids these days they are great with technology' (no they aren't but that's a whole other story).

So in the early days what did I learn from games?

> That they are memory hogging nightmares that require you to bend things to your will.
>
> _Historic Rory, 1990s_

### Backups
Allow me to explain, in between my BBC Micro experiences things evolved and changed, via Spectrums, Amstrads and Commodore 64s. With those things you tended to stick in the tape (let grandad tell you about tapes some time) or disc (let grandad tell you about discs some time) waited for 17 hours, and, if you didn't find yourself having some sort of seizure thanks to the loading screens, you had a game you could play. 

Basic write protection to 'backup' these games was usually defeated with a dual tape deck, or strategically placed selotape, and early lessons were learned here about the value of genuine backups...when the Amstrad decided to eat your tape, and the nearest option for a replacement was 30 miles away, and the internet was still the realm of R&D skunkworks and academia, not to mention crossing the border in the 1980s in Ireland to go to the one computer shop in the North East was not exactly good craic, having a replica was a necessity.

### Writing More Code
Anyway, more typing code verbatim happened with the Amstrads my mates owned, and the buzz you got from hours of effort that resulted in admitedly crap games appearing on screen was imeasurable, I miss that sufficiently that im going to do a course on game development over the next while, but really, for me, it illustrated the power of these whiring boxes, you could do anything with them!!!

### Battling the OS
Back to the initial statment, about them being memory hungry beasts. In the dawning of the age of the x86, our family acquired an 386, with an insane 640k of memory. It ran stuff like Wordstar and some Sage thing...AND GAMES. OH YES. BUT OH NO! You have insufficient memory...enter [memmaker](http://www.easydos.com/memmaker.html) this let you manage memory allocation, but in order for this to work properly it needed to run at startup...so this meant changing config.sys and autoexec.bat, through this I learned how computers started up, got forced into mucking about with BIOS settings and by sheer necessity (i.e. Populus clearly must run) learned more than I ever intended.

### Hacking 101
It also provided the one of the highlights of my IT career. My game playing reached intolerable levels, so my Dad enlisted one of his students (he lectured in Elecontric Engineering in a local Regional College) to create a password protection program. It was great, it started after boot, prompted for a password and if you didn't get it right, DOS wouldn't load. Sadly, my education in boot process thanks to memory wrangling meant two things.

1. I wasn't scared to go poking around things
2. I had a suspicion where this Password protection program might get called (autoexec.bat)

On my next allowed compute time, instead of going straight to games, I discovered the batch file that called the program, found the program, found it stored the password in plaintext, made note of said password, and then used it to get onto the PC every time I was unsupervised.

### So What?
Some really valuable lessons learned, namely:
* Don't be afraid to try things out
* Learn as much as you can, you don't know when unrelated things come together to form an answer
* Don't admit you know the password to a system, because someone will change it