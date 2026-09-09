# Music Tools

Browser-based music production utilities for dark industrial, techno, and MIDI workflow generation. These are single-file HTML tools that run locally in any modern browser — no build step or server required.

## Tools

- **Dark Atmosphere Generator** (`dark-atmosphere-generator.html`) — layered dark ambient pads and evolving textures.
- **Dark Industrial Texture Generator** (`dark-industrial-texture-generator.html`) — industrial noise, metallic drones, and dense soundscapes.
- **Dark Techno Rhythm Generator** (`dark-techno-rhythm-generator.html`) — percussive techno grooves and rhythmic patterns.
- **MIDI Pattern Generator** (`midi-pattern-generator.html`) — chords, bass, and arpeggios with in-browser preview and Standard MIDI File export.
- **Sample Element Synthesizer** (`sample-synth.html`) — synthesized sample elements and sound design snippets.

## AI Helper

`vex-ai.js` is a small browser-side helper that talks to a local VEX Editor OpenAI-compatible endpoint at `http://127.0.0.1:9789/v1/chat/completions` for generating music ideas on demand.

## Usage

Open any `.html` file directly in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- All generator tools run fully client-side.
- The AI helper expects a local VEX Editor endpoint and is optional for the generator tools.
