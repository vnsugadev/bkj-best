# Audio Files for Incoming Call Feature

## Required Audio Files

The incoming call popup feature uses two audio files:

1. **ringtone.m4a** - Plays when the incoming call popup appears (loops continuously)
2. **funny_audio.mp3** - Plays when the user accepts the call

## Current Status

Both files are currently populated with placeholder audio from existing files in the repository:
- `ringtone.m4a` is a copy of `oles_dave_ballmer.m4a`
- `funny_audio.mp3` is a copy of `ggamoor.mp3`

## To Customize

To use your own audio files:

1. Replace `ringtone.m4a` with your desired ringtone (should be a short, looping-friendly audio)
2. Replace `funny_audio.mp3` with your desired funny audio response (plays once when call is accepted)

Both files should be placed in the root directory of the website.

## Browser Autoplay Policy

Note: Modern browsers may block autoplay of audio. The ringtone will only play if:
- The user has interacted with the page at least once before the popup appears
- The browser's autoplay policy allows it

If autoplay is blocked, the popup will still appear and be functional, but the ringtone won't play automatically.
