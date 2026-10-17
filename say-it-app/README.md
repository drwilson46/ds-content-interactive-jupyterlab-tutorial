# Say It — iPad pronunciation app

Type a word or phrase and tap **Speak** to hear it pronounced. Built as a single
web page using the iPad's built-in text-to-speech (Web Speech API), so it works
offline once loaded and needs no App Store install.

## Features
- **Speak** any word or group of words (Return key also speaks)
- **Spell it** — reads the letters one at a time
- Choose a **voice/accent** (e.g. en-US, en-GB, en-AU), adjust **speed** and **pitch**
- Highlights each word as it is spoken
- **Recent** list — tap a chip to hear it again (saved on the device)

## Put it on your iPad
1. Host `index.html` anywhere (e.g. GitHub Pages), or open the published link.
2. Open it in **Safari**, tap **Share → Add to Home Screen**.
3. It now launches full screen like an app.

More/better voices: iPad **Settings → Accessibility → Spoken Content → Voices**
(download an "Enhanced" or "Premium" voice).

`app.fragment.html` is the same page without the `<html>/<head>` wrapper, used
for publishing as a Claude artifact.
