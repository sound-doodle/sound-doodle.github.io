## Summary



The purpose of this app would be to allow a user to layer midi sound files to create his or her own music.

The user will be able to choose from a sound bank of instruments such as drums or keyboard and create music using the touch screen of the device.  The app will allow the user to add instruments to the recording using free record or drag and drop to a grid to create a full band experience. 



## Intended users


*  The Songwriter

> As a songwriter, I want to use the builtin instrument library and free record function of this app so that I can quickly record a melody or harmony for future use.


*  The doodler

> As someone who enjoys music, I want to use the screen tap and record function so that I can tap out the groovy beats in my head.

## Client component

### Functionality

*  The app will display a time grid that will accept input sounds for playback.  
      *  The grid will have a slide menu to manipulate tempo and a button to customize musical divisions such as 16th notes or 8 notes per beat.
*  The user will have a top menu that will expand into buttons for New/recall, instrument library, custom sound bank.
*  The user will select a new track from the New button.
*  The user will select the first instrument from the instrument select menu.
*  The user will have the option to press record and free play the instrument to a metronome or slide sound files into the music time grid.
*  The user will be able to layer new tracks with the option to record a new instrument.
*  The app will have a playback button to play back all tracks or the tracks selected by the user to play.



### Persistent data

*  Instruments files.
*  Sound banks/libraries.
  
### Device/external services

*  Microphone <a href="https://developer.android.com/reference/android/media/MediaRecorder">Media Recorder API</a>

## Server component

### Functionality

* N/A

### Persistent data

* N/A

### External services

* N/A
 
## Stretch goals/possible enhancements 

* Time Signatures
* Instrument quick key selection.\
* Effects layering such as reverb, delay.
* Master track effects such as compression and EQ.