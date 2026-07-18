# language_translator
A browser based translation tool: 
enter text, pick a source and target language, and get a translation back with copy and text to speech support.
Features:
Text input with source and target language selectors (28 languages)
Translates using the free MyMemory Translation API (no API key required)
One tap language swap
Copy button for the translated text
Text to speech playback for both the original and translated text
Responsive layout  works on mobile and desktop
Tech stack
HTML, CSS, and vanilla JavaScript — no build step, no dependencies
MyMemory Translation API
Browser Web Speech API for text-to-speech
Run it
Open index.html in any browser. No installation needed.
Live demo
Enable GitHub Pages on this repo (Settings → Pages → Source: Deploy from branch → main) to get a shareable live link.
Notes
The free API tier is capped at ~500 characters per request and 5,000 characters/day. To use Google Cloud Translate or Microsoft Translator instead, see the commented example near the top of the <script> tag in index.html.