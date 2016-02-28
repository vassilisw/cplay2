# cplay2

### Description

cplay is now back with some more features!  
It is a fork of the well known cplay, so lets call it cplay2.

cplay2 is a curses front-end for various audio players. It aims
to provide a power-user-friendly interface with simple filelist
and playlist control. cplay2 is written in Python and can use
either pyncurses or the standard curses module.


### New (optional) features in cplay2

- Generates a **log** with files being played.
- Supports importing a list of files from any **script**, without leaving the ui.
- Repeat mode has an additional option to import songs from a **script** instead of actual repeating.
- **mplayer** support (currently only audio). Plugins, **ladspa**, etc may be passed to mplayer.
- Addjustable fade out, for **mixing** between songs!
- Max play time option. This will mix the song with next one, if the song is more than x mins and 
after it passes its 85% of its duration.
- Navigate **into m3u** playlist files.
- More settings can be set in the rc file.
- **Bookmarks are saved** between launches.
- New **colored** ui.
- Dynamic help page.


### Features

-


### Requirements

- python http://www.python.org/


### Optional requirements
- mplayer       (**recommended**)  www.mplayerhq.hu
- python-oss    (optional)         http://net.indra.com/~tim/ossmodule/
- mpg321        (optional)         http://sourceforge.net/projects/mpg321/
- ogg123        (optional)         http://www.vorbis.com/
- mpg123        (optional)         http://www.mpg123.org/
- splay         (optional)         http://splay.sourceforge.net/
- madplay       (optional)         http://www.mars.org/home/rob/proj/mpeg/
- mikmod        (optional)         http://www.mikmod.org/
- fintl         (optional)         http://www.python.org/sigs/i18n-sig/
- pyncurses     (optional)         http://pyncurses.sourceforge.net/
- ID3-py        (optional)         http://id3-py.sourceforge.net/
- pyvorbis      (optional)         http://www.duke.edu/~ahc4/pyogg/
- xmp           (optional)         http://xmp.sf.net/
- sox           (optional)         http://sox.sf.net/
- speex         (optional)         http://www.speex.org/


### Installation

Copy cplay2 wherever you're able to run it.  
Copy cplayrc into .cplayrc in your home folder: `cp cplayrc ~/.cplayrc`


### Usage

cplay2 [-nrRv] [ file | dir | playlist ]  
press 'h' for a friendly help page.


### Notes

In order for either mp3info (ID3) or ogginfo to work,
both corresponding python modules have to be installed.
This will change someday.

Remote control via /tmp/cplay-control-$USER


