---
title: Overview
subtitle: Project description and status
menu: Overview
order: 0
---


## Summary



The purpose of this app would be to allow a user to layer midi sound files to create his or her own music and to collaborate with friends.

The user will be able to choose from a sound bank of instruments such as drums or keyboard and create music using the touch screen of the device.  The app will allow the user to add instruments to the recording using free record or drag and drop to a grid to create a full band experience. 



## Intended users


*  The Songwriter

> As a songwriter, I want to use the builtin instrument library and free record function of this app so that I can quickly record a melody or harmony for future use.


*  The doodler

> As someone who enjoys music, I want to use the screen tap and record function so that I can tap out the groovy beats in my head.

## Client component

### Functionality

*  The app will display a time grid that will accept input sounds for playback.*  The grid will be 4/4 time signature.
*  The user will have a top menu that will expand into buttons for New/recall, instrument library, custom sound bank.
*  The user will select a new track from the New button.
*  The user will select the first instrument from the instrument select menu.
*  The user will slide MIDI sound files into the music time grid.
*  The user will be able to layer new tracks with the option to record a new instrument.
*  The app will have a playback button to play back all tracks or the tracks selected by the user to play.



### Persistent data

*  Instruments files.
*  Sound banks/libraries.
  
### Device/external services

*  Microphone <a href="https://developer.android.com/reference/android/media/MediaRecorder">Media Recorder API</a>
*  Internet for data transfer.

## Server component

*  Hosting saved song files.
*  Sharing custom sound libraries.
*  Uploading MIDI/Wav files.
*  Sample MIDI/Wav sounds.

### Functionality

*  User can upload files to server/cloud.  Those with proper credentials can access, comment, or add to the project.

### Persistent data

*  Sound files.
*  Downloaded files.
*  Log-in credentials.

### External services

*  Internet for data transfer.
 
## Stretch goals/possible enhancements 

* Time Signatures/tempos.
* Microphone access for custom recordings.  
* Instrument quick key selection.
* Effects layering such as reverb, delay.
* Master track effects such as compression and EQ.