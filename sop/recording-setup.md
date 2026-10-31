# SOP – recording set-up (₹0 to start) · Level of this SOP: Basic

Menu names below were correct for recent versions; check them on the day, as apps move menus.

## PC screen + voice: OBS Studio
1. Download OBS Studio from the official site obsproject.com (source: [obsproject/obs-studio](https://github.com/obsproject/obs-studio)). Run the Auto-Configuration Wizard → "Optimise just for recording".
2. **Settings → Video:** Base and Output resolution 1920×1080, 30 FPS.
3. **Settings → Output (Simple):** Recording Quality "High Quality, Medium File Size"; Recording Format **MKV** (a crash does not lose the file); Encoder: Hardware (NVENC / QuickSync / AMF) if listed, otherwise Software x264.
4. After recording: **File → Remux Recordings** → MKV to MP4 for the editor.
5. **Settings → Audio:** Sample rate 48 kHz. Mic/Aux = your mic. Turn off Desktop Audio unless the tool makes sounds you need.
6. Mic filters (right-click the mic in Audio Mixer → Filters): add **Noise Suppression** (RNNoise), then **Compressor**, then **Limiter** at −1 dB.
7. Sources: one **Display Capture** (whole screen) or **Window Capture** (one app). Hide notifications: Windows Focus / Do not disturb on.
8. Before every session: record 10 seconds, play it back, check the voice level stays in the yellow, never red.

## Phone screen
- Android quick-settings **Screen record** (with microphone on), or mirror to the PC with scrcpy ([Genymobile/scrcpy](https://github.com/Genymobile/scrcpy)) and record in OBS. Hide personal notifications, use a test account, and blur numbers in editing.

## Room and voice
- Small room, soft things around (curtains, bed), fan off while recording.
- Phone earphones with mic are fine for Phase 0. Mouth 10–15 cm from the mic, slightly to the side.
- Read the script once aloud before recording. Record in short sections; leave 2 seconds of silence between sections for easy cutting.

## Privacy checklist before recording
- [ ] Test Google account / test phone profile, not personal accounts
- [ ] No Aadhaar, phone numbers, bank details, office files or election data on screen
- [ ] Browser bookmarks bar and other tabs hidden
- [ ] Notifications off

## Editing (free)
- DaVinci Resolve (free), Shotcut or Kdenlive on PC. YouTube Studio's editor for small trims.
- Export: H.264, 1080p, 30 fps; Shorts 1080×1920.
- Captions: upload the script as a transcript in YouTube Studio and let it sync; check Telugu captions by eye.
