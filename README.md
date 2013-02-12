ofxTimelineTracks
=================

Tracks to use with ofxTimeline
----
ofxTLNote
----
Generic Note Container - holds Pitch as an integer and Velocity as a normalized float
Enter notes via OSC (you can use midi via Osculator if you need)
Resize/move notes with mouse
Save/Load notes from xml file


----
ofxTLMidiNote (deprecated, no longer works with the current ofxTimeline)
----
Video example: https://vimeo.com/46793363

    Enter Notes with mouse or MIDI device
    Output MIDI notes to any device (with pitch and velocity)
    Resize/move notes with mouse
    Save/Load notes from xml file (needs to be updated to save track settings like selected device and range)
    Inputting a new note or stretching an existing note so that it overlaps an existing note start will overwrite the existing one, or doing that to a note end (but not the start) will simply crop the existing note.
    
