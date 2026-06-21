# viewassist
Viewasssit for homeassistant enhancements
- Plays a random TTS response when a satellite enters listening mode. 
- Disables the microphone, waits for the END of audio playback and re-enables it safely to avoid loops.
- Uses the tts.speak service instead of media_player.play
