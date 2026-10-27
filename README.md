# Just Stay Home and Play Synthesizers

A pocket synth lab that runs entirely in the browser — no build step, no dependencies, one `index.html`.

- **Synth** — two oscillators (sine / triangle / saw / square / custom), noise, filter with envelope, ADSR, LFO to pitch/filter/volume, presets and a random-patch button, touch keyboard with velocity and Hold.
- **Drums** — 7-track, 16-step sequencer with synthesized kick, snare, clap, hats, tom and bell; tempo, swing, per-track level/tune/decay/mute, preset patterns and randomize.
- **Pad** — multi-touch XY pad: left/right is pitch (snapped to a scale or free), up/down is brightness.
- **Waves** — draw 16 harmonics to build your own waveform; it becomes Osc 1's "custom" wave.
- **Learn** — 17 bite-size lessons on oscillators, pitch, mixing, intervals, detune, filters, resonance, envelopes, LFOs and noise. Each ends in a challenge: tweak the knobs until your sound's wave and loudness/brightness/pitch graphs match a target. Hints, progress tracking, and a button to send your patch to the Synth.
- **FX** — drive, delay, reverb, mix levels and a recorder that saves takes as audio files.

Everything you change is saved in your browser's local storage.

## Put it on GitHub Pages

1. Create a new public repo on GitHub (e.g. `stay-home-synths`).
2. Upload `index.html` (and this README) to the repo root.
3. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute it's live at `https://<your-username>.github.io/stay-home-synths/`.
5. On your phone, open that URL and use **Add to Home Screen** so it launches full-screen like an app.

## Tips

- Drag knobs up/down; double-tap to reset.
- iPhone: if there's no sound, flip the silent switch off.
- Desktop keys: `A W S E D F T G Y H U J K` play notes, `Z`/`X` change octave, `Space` starts/stops drums.
