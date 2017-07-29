---
layout: post
title: Bloc Jams
thumbnail-path: "img/blocjams.png"
short-description: Bloc Jams is a music streaming application built to resemble Spotify and iTunes. This features interactive scroll bars and volume controls, and features a library of various albums.

---

{:.center}
![]({{ site.baseurl }}/img/blocjams.png)

## Summary

Bloc Jams is a music streaming application built to resemble Spotify and iTunes. It features interactive scroll bars and volume controls, and features a library of various albums.

## Explanation

This was my first project in the Bloc program, so I built the app while tackling a steep learning curve. I coded the HTML, CSS and Javascript from the ground-up, but was given snippets of code to aid in the learning process. There were several components I was required to built alone, such as the play/pause feature for the docked control panel.

## Problem

For the docked control panel, I wanted to add three working buttons - previous, next and play/pause controls. These needed to reference the song list and change each song's play or pause button accordingly. This would enhance the application and give it a sophisticated and useful interface.

## Solution

I created a nextSong function that would change the currently playing song to the next song on the list. Should this occur on the last song in the list, the function would loop back to the first song. I next created a previousSong function using similar code, but for the previous button. Finally, I created a play/pause function that played or paused the song depending on the status of the sound file on click.

## Results

The control panel features three fully-working playback control buttons. Centralizing the controls on the bottom panel made for a more easily usable application.

## Conclusion

This being my first web development project, I learned a great deal about jQuery and javascript functions. The end result is professional music streaming application, but more importantly a coding knowledge foundation.
