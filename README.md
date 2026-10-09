# Word by Word — Apna application prototype

An AI-assisted, browser-based vocabulary coach with five curated words. It teaches a definition and example, asks for spoken or typed recall, then asks the learner to use the word in a sentence. Each answer can be edited before checking. A review card closes the session.

Open index.html or serve this folder with a local static server. A publicly accessible HTTPS URL is required before submitting Apna's application. This folder contains no resume, credentials, analytics or identifying contact information.

## What works

- Browser text-to-speech for lessons and feedback.
- Speech recognition where the browser supports it; microphone access is requested only after a button click.
- Typed input when speech recognition is unavailable or access is declined.
- Simple deterministic feedback, retries, sentence practice, progress and restart.

## Prototype limits

Meaning feedback uses curated keywords. Sentence feedback checks the target word and sentence length, not semantic correctness. Voice-input compatibility and online recognition depend on the browser/provider. No custom language model, pronunciation scoring, persistent progress, account or backend is claimed. Audio and transcripts are not stored by this app; browser speech recognition may use the browser provider's online service.

Built with AI assistance for the application requirement. Ojas should review and try the voice flow before discussing it in an interview. Do not describe it as a previously shipped product, deployed client work or production AI system.

References: https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition and https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis
