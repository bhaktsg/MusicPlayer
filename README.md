# MusicPlayer
Music Player in Python using Pygame modules


ABSTRACT:
In the last few years, MP3 players have made it possible to take your whole music collection with you anywhere. Our implementation does provide the convenience of an MP3 player. This Music player can play, pause, rewind, resume and select songs with the previous button and next button according to set requirements as well as set up songs. It can be used easily for music and it’s convenient and quick and has a simple User Interface(UI).


MODULE - WISE DESCRIPTION:

Pygame mixer library-
This module contains classes for loading Sound objects and controlling playback. The mixer module is optional and depends on SDL_mixer.The mixer module has a limited number of channels for playback of sounds.All sound playback is mixed in background threads. When you begin to play a Sound object, it will return immediately while the sound continues to play. A single Sound object can also be actively played back multiple times.The mixer module must be initialized like other pygame modules, but it has some extra conditions.Pygame will default to reasonable values, but pygame cannot perform Sound resampling, so the mixer should be initialized to match the values of your audio resources.

Mutagen is a Python module to handle audio metadata.It can read Xing headers to accurately calculate the bitrate and length of MP3s.


TECHNOLOGY SELECTED AND TECHNOLOGY FEATURES USED:

  Tkinter- For implementing the Graphical User Interface (GUI) of the music player.
  
  Pygame - mixer: For loading Sound objects and controlling playback.
  
  Mixer functions
  
  Mutagen
  
  IDE used- PyCharm
  
  
