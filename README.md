# Wes-Bos-JS-Notes

<h2>Day-1 Drum kit</h2>
The first day of the challenge sees us building a web drum kit application. I recognise thatr this must involve a function that links keyboard presses (turns out this is called ‘the event’) to trigger the audio file to play. To do this we ‘addEventListener’ to the window (This can be applied to divs... etc)
 window.addEventListener('keydown', playAudio)
div.addEven….

The next step is assigning the keycode triggers to the event function and the audio files.
Keycode https://keycode.info/ is a code assigned to keyboard keys. 
.onclick is another trigger function that can be used to trigger events

Use a data- attribute to attach the keyboard with a data-key attribute- then attach the audio element to the data-key:
<audio data-key="65" src="sounds/clap.wav"></audio>

To select the audio file we use the   
document.querySelector(`audio`)

