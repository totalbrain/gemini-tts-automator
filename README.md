# Gemini TTS Automator WebApp

## Description
A web-based application that fully automates text-to-speech (TTS) generation using Google Agents in conjunction with Gemini TTS models. Supports modern Persian (Farsi, fa-IR, in preview) and English language capabilities. Leverages Google Cloud's Vertex AI or AI Studio for agent orchestration, ensuring automation through agent-driven workflows.

## Features
- User input handling for Persian and English text.
- Language and voice selection with auto-detection.
- Automated TTS generation with style controls (tone, pace, accent).
- Output delivery in formats like MP3, with playback and download options.
- Multilingual UI (Persian/English).
- User-managed Google API tokens for quotas.

## Getting Started
1. Clone the repo: `git clone https://github.com/your-username/gemini-tts-automator-webapp.git`
2. Install dependencies: `npm install` (for Node.js backend) or follow frontend setup.
3. Configure Google API credentials.

## Links
- Live Demo: [index.html](./index.html) (placeholder)
- History: [history.json](./history.json)

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License
MIT License - see [LICENSE](LICENSE) for details.

## Notes about Persian (fa-IR) preview support
Persian (fa-IR) support in Gemini TTS may be in preview and could not be available in all accounts/regions yet. Recommended fallbacks:
- Provide a configuration option to select a fallback TTS engine (e.g., another Google voice region or a third-party TTS provider) for Persian if the preview model is unavailable.
- Document in the README and configuration the required Vertex AI/AI Studio quotas and the steps to request access to preview models.
- Implement graceful error handling that informs users and offers a fallback voice/locale automatically.