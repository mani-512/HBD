# TODO: Unify Audio to "Sundari neeve BGM.mp3" Across Project

- [x] Update love/index.html: Change audio source from "music/setlove.mp3" to "../Sundari neeve BGM.mp3" and remove unnecessary ogg source.
- [x] Update love/main.js: Set bgMusicURL = null; to disable additional SoundCloud audio.
- [x] Modify index.html: Store audio.currentTime in sessionStorage before navigating to love/index.html.
- [x] Modify love/index.html: Remove autoplay from audio, set currentTime from sessionStorage on load, then play the audio to continue from where it left off.
- [x] Fix audio glitch on navigation: Use 'canplay' event to set currentTime and play only after audio is ready, preventing brief restart.
