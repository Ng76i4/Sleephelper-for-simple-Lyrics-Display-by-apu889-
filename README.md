# Sleephelper-for-simple-Lyrics-Display-by-apu889-

This help auto load\unload the lyrics skin when player not playing


To make this work first of all you have to installed webnowplaying plugin, or just install Spicetify and play along
To fix the "Simple-Lyrics-Display" not working with newest version of spotify when you already install webnowplaying plugin you have to edit AudioMusicPlayer.ini to make Spotify
indentify the sknin

From: ContextAction2=[!SetOption - String "Spotify"][!UpdateMeasure -][!SetOption -- String "SpotifyPlugin"][!UpdateMeasure --]
to: ContextAction2=[!SetOption - String "Spotify"][!UpdateMeasure -][!SetOption -- String "WebNowPlaying"][!UpdateMeasure --]

Move Musixmatch.ini to new folder named Lyricx

Copy Sleephelper Lyricx folder to Simple Lyrics Display folder

Open rainmeter and load SleephelperLyricx.ini

Now try to play, pause spotify player. It will also work when you turn of the player.
.
.
.
.
.
.
OR JUST SIMPLY INSTALL THE .RMSKIN 
