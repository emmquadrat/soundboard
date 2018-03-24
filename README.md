# soundboard
A simple sound board for use with the Shadowrun tabletop RPG.

This is a simple soundboard based on HTML and javascript. You don't need to have coding skills to adjust the soundboard to your needs but you need to edit the «Soundboard.html» file with a text editor.

The file uses a code like this

```javascript
var soundboard_buttons = [
	// Ambient Music
	['Intro','Soundtrack/262493__gipsyga__intro-to-a-space-series.mp3','soundtrack'],
	['Tension 30Seconds','Soundtrack/Tension-25s.mp3','soundtrack'],
	['Sad scene','Ambient/solitary_cello.mp3','soundtrack'],
…
```

You can customize the audio like this:
- Make square brackets for every sound you want to use.
- Inside the brackets you must declare three values, seperated by a comma.
	1. The text on the button.
	2. Define the path and the name of the audio file. It must be an mp3 format. The audion files' folders are on the same level as the folder '_htlm' containing this file.
	3. The category of this button. It basicaly defines the color of the button. For now, seven categories are set. Soundtrack, Environment, Magic, Spirits, Matrix, Guns and Vehicles. You can define more categories by just adding a class with the appropriate name to the list below.
- If you make an empty set of variables (like so: ['']), a linebreak is inserted.
  
All the sounds used here are free audio from [freesound.org](https://freesound.org/). It's a marvelous source of all kinds of sounds you realy need to check out.
I really hope to not mess around with the copyright of freesound.org here. If you are a representative of this organization and have any issues with this work, please contact me. This is a non commercial project with no intention but providing a simple solution for a common problem.

If you want to use this soundboard just load it on your computer (click «clone or download» on the top right) unzip the file and open «Soundboard.html» in your browser.
