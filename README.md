# Granular retreat deck, live follow

`index.html` is the deck the room sees at https://eddiesanjuan.github.io/granular-live/. Phones on that link follow the presenter's slides.

## Update the deck
1. Edit `index.html` directly, here or on GitHub. If you rebuild from an older source file, carry over the first slide ("Follow along"), the last slide ("Didn't get to the interview?"), and the script block marked `v1.5 live follow`, or the live link stops following.
2. Commit to `main`. GitHub Pages republishes in about a minute.
3. Refresh the presenter tabs. Anyone already following should refresh too if slides were added, removed or reordered, because phones follow by slide number.

## How following works
- Only a tab opened with the presenter link (shared privately, not in this repo) sends slide changes. Everyone else only listens.
- A participant tapping through moves only their own phone, and the presenter's next slide change or 10-second heartbeat brings them back.
- The newest slide change wins, so a presenter tab left open and idle on another laptop does not pull phones away from the person actually presenting.
