# Mofibo.com-Mp3tag-scraper
Let Mp3Tag parsing audiobook information from mofibo.com

This is my modified custom web source for mp3tag. The original authors are qudo, dano, and Romano and with inspiration from seanap

Windows
1. Place the file in C:\Users\xxx\Mp3tag\data\sources
2. Restart Mp3Tag
3. Go to Tag Sources >> Mofibo.com 
4. Tag the file and e.g. edit some changes
BINGO!

E.g use this format string: 
'C:\path\to\your\Audiobooks\Audiobooks\%albumartist%\%series%\%year% - %album%[ '['%series% %series-part%']']\%album% (%year%) ['['%series% %series-part%']' ]- %Narrator%'
