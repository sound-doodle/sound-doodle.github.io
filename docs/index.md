---
title: Overview
subtitle: Project description and status
menu: Overview
order: 0
---


## Summary



The purpose of this app would be to allow a user to layer midi sound files to create 
his or her own music and to collaborate with friends.

The user will be able to choose from a sound bank of instruments such as drums or keyboard to create music using the touch screen of 
the device.  The app will allow the user to add instruments to the recording timeline using drag and drop to a time grid. Future releases
will allow users to record audio.



## Intended users


*  The Songwriter

> As a songwriter, I want to use the built-in instrument library and free record function of this app so that I can quickly record a melody or harmony for future use.


*  The Doodler

> As someone who enjoys music, I want to use the screen tap and record function so that I can tap out the groovy beats in my head.

## Client component

### Functionality

*  The app will display a time grid that will accept input sounds for playback.  The time grid will be 4/4 time signature.
*  The user will have a top menu that will expand into buttons for New/recall, instrument library.
*  The user will select a new project and new tracks from the New button.
*  The user will select the first instrument from the instrument select menu.
*  The user will be able to layer new tracks with the option to record a new instrument.
*  The app will have a playback button to play back all tracks or the tracks selected by the user to play.



### Persistent data

*  Instruments files.
*  Sound banks/libraries.
  
### Device/external services

*  Internet for data transfer.

## Server component

*  Hosting saved song files.
*  Sharing custom sound libraries.
*  Uploading MIDI/Wav files.
*  Sample MIDI/Wav sounds.

### Functionality

*  User can upload files to server/cloud.  Those with proper credentials can access, comment, or add to the project.

### Persistent data

*  Sound sample files.
*  Downloaded files.
*  Unique user Ids.
*  Saved user data.

### External services

*  Internet for data transfer.
 
## Stretch goals/possible enhancements 

* Time Signatures/tempos.
* Will incorporate MIDI sound file support.
* Microphone access for custom recordings.  
* Instrument quick key selection.
* Effects layering such as reverb, delay.
* Master track effects such as compression and EQ.
* To support future audio recording: Microphone <a href="https://developer.android.com/reference/android/media/MediaRecorder">Media Recorder API</a>
