MONSTER BIRTHDAY SITE v2
Upload index.html (and the media folder) to GitHub. UNZIP FIRST: GitHub does not unzip files for you.
The first song is built into index.html, so it plays even if the media folder is missing.

ADD MORE SONGS
1. Put the mp3 in the media/ folder (e.g. media/song2.mp3). Upload the folder too.
2. Open index.html, find  songs:[  near the top of the script, and add a line after the first one:
   {src:'media/song2.mp3', title:'Song name', by:'Milis', lyrics:[[0,'first line'],[8,'second line']]},
   Names are case-sensitive on GitHub: song2.mp3 is not Song2.mp3. Avoid spaces.
   Songs play in order. The Jam ends after the last one.

EDIT THE TEXT
- Real message: find  essay:[  and put each paragraph in quotes, separated by commas.
- Last page message: find  finalMsg:'...'
- Lyrics for song 1: find  embedded:true  and edit lyrics:[] on that line.
