# CleanCast – Chrome Extension

## Idea
- A **Chrome Extension** that mutes profanity in real‑time on streaming platforms (Netflix, Disney+, etc.) using closed captions.

## Stack
- **Manifest V3**
- **Content script** to inject into pages
- **Web Audio API** to manipulate audio stream
- **Backend** (optional): TinyDB or local storage for word list

## Competitors
- **VidAngel** ($9.99/mo) – heavy‑weight, paid subscription.
- **Stream Clean** – caption‑based, limited platform support.

## Differentiators
- **Platform‑agnostic** (works on any streaming site with captions).
- **Real‑time** audio filtering (no buffering).
- **Freemium** model – basic profanity list free, premium custom list.

## Current Status
- ❌ Paused – content script not firing on YouTube.
- ⚠️ No console logs – injection failing silently.

## Next Steps
1. **Re‑create the extension** (delete and reload unpacked).
2. **Add console.log** in `content.js` to confirm injection.
3. **Check `manifest.json` permissions** (`tabs`, `activeTab`, `storage`).
4. **Test on YouTube** – see if `document.querySelector('video')` returns a media element.
5. **Add debugging** (chrome://extensions/ -> “Errors”).

## Funding
- Target freemium price: ~$5/mo
- Potential ad‑support or sponsorship from streaming services.
