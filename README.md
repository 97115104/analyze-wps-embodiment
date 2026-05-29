# Speaking Rate Analyzer

A browser-based tool that measures words per minute (WPM) from a live microphone or an uploaded audio file, then generates a copy-paste analysis report.

**Live demo:** https://&lt;your-username&gt;.github.io/analyze-wps-embodiment/

## Features

- **Microphone mode** — real-time transcription via the Web Speech API with a live WPM counter
- **File upload mode** — drag-and-drop any audio file (MP3, WAV, M4A, OGG, FLAC, WebM); transcribed in-browser by Whisper AI (no server)
- **Pace assessment** — categorises your rate as Slow / Moderate / Optimal / Fast with a visual bar
- **Copy-paste report** — plain-text report with metrics, assessment, and full transcript

## Browser compatibility

| Feature | Chrome/Edge | Firefox | Safari |
|---|---|---|---|
| Microphone (Web Speech API) | ✅ | ❌ | ✅ |
| File upload (Whisper AI) | ✅ | ✅ | ✅ |

## Privacy

All audio processing happens locally in your browser. No audio or transcript data is sent to any server.

## License

[MIT](LICENSE) © 2026 97115104

## Attestation

This project was built collaboratively with AI assistance and is attested via the [attest](https://attest.97115104.com) open attribution protocol.

Verify: https://attest.97115104.com/s/47w1auzt
