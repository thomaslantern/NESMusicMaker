# NESMusicMaker
<h1>Let's Make Music Together!</h1>
This is my JS app to create an .NES cartridge that plays a short sample of music. Choose the notes you want on the music staff, then click on "download cartridge" to download an .NES cartridge that contains your little song snippet.

<h2>FAQ</h2>
<h3>Q: What exactly does this app do?</h3>

So basically what this app does is pretty simple: you pick some notes on the "Nes Music Maker" by clicking on the music staff. When you're happy with your note selections, press the "Download Cartridge" button and it will let you download your musical creation as a .NES file.

<h3>Q: Is there a limit to notes?</h3>

Currently the maximum is only 16 notes (I plan to fix this in future versions).

<h3>Q: Is there anything else I should keep in mind when using this app?</h3>

Rests don't work, so I've disabled them for now. Also, if you play the same note twice it just doubles the note length; this is because the note being played is basically just a straight sine wave, so there's no attack/release/decay on the note, like there would be with an actual musical instrument... so you can't hear where one note ends and the next begins, if they're the same note. This is something I will fix!


<h3>Q: Why did you make this app?</h3>

It was part of a school project for my web design course. We had to build our website about the subject of our choice, and I chose NES (ASM6502) programming. We needed to write some of our own JavaScript to add some gusto to our sites, and... NES Music Maker was born. I made it along with two graphical tools, both of which should end up on my GitHub in the near future.
