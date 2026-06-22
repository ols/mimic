Mimic — your voice, but better. Or weirder. Or both.

A slim, low-latency Windows voice changer that takes  you from "open the installer" to "talking like a  dragon in Discord" in under a minute — no reboot, no  driver install, no subscription.

Mimic listens to your mic, runs it through pitch-shift / formant / reverb DSP and neural RVC voice conversion on your GPU (DirectML, ~10× faster than CPU), and pipes the result into Discord, OBS, Zoom, or wherever — via the free VB-CABLE virtual audio cable. No restart prompts, no signed kernel drivers.

What sets it apart:

- 🎙️  Train your own voice from a sentence — type "a gravelly drill sergeant", hit Quick Test, get a playable RVC voice in 3-5 minutes. Or pick from 50 curated idea chips across Fantasy, Sci-fi, Memes, Spooky and more if blank-page paralysis hits.
- 🎚️  Two-knob simplicity — Dark↔Bright and Dry↔Wet sliders that drive the whole vocal chain. Power users still get the four-knob DSP under "Advanced".
- 🌃 Vibe layer — six bundled ambient beds (Cathedral, Hellfire, Cyberpunk, Underwater, Forest, Vinyl) that mix under your voice for instant atmosphere.
- 📤 Share-a-voice — export any trained voice as a single .mimic-voice file your friends can import in one click. Trade voices like Pokémon.
- ⚡ Built for actual realtime — ~210 ms end-to-end (200 ms hop + SOLA crossfade + cpal buffer), positional rnd seeding, RMVPE neural pitch detection, octave-error correction, automatic latency recovery after Windows audio stalls.
- 🎭 Custom voices with emoji faces — every voice you train gets its own face in the catalog. No more "untitled-3.onnx".
- 💬 Plain-English errors — missing a Python package? You get one sentence plus a triple-clickable fix command, not a stack trace.

Free, source-available, ~12 MB installer, alpha software. Built in Rust + Tauri + Svelte by people who got tired of voice changers that need a system reboot to install a virtual audio device.

<img width="1658" height="1239" alt="image" src="https://github.com/user-attachments/assets/32fc3c29-53b8-458b-a00e-feae31f2c3d8" />
<img width="1659" height="1278" alt="image" src="https://github.com/user-attachments/assets/76410b21-1371-486c-acf9-f031e7f0008e" />
