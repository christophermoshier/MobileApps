# MobileApps

## 👻 Moshier Paranormal
A neon, synthwave ghost-wrangling game starring the Moshier family. One `index.html`, all art drawn in code, no build step.

- **Play:** https://christophermoshier.github.io/MobileApps/moshier-paranormal/
- **Files:** `moshier-paranormal/` — `index.html` (the whole game), `manifest.webmanifest` + `icon.svg` + `sw.js` (add-to-home-screen / offline)

### How to play
Drag your thumb to aim (the beam hits a point **above** your thumb). Hold the beam on a ghost until it says **LET GO!**, then release to trap it. Tap the power button (bottom-right) when it's charged.

### Easter eggs (spoilers)
- Tap **Chris** 5 times fast on the crew screen: CHEAT MODE (infinite beam). Your score gets stamped "⚠️ CHRIS CHEATED" in flashing letters, including on the high-score board, forever. 5 more taps turns it off.
- **Incoming call: Dean** on Mom's phone mid-round: "Mom the food here is SO bad." The live video shows Gloop cooking in the dining hall kitchen.
- Rare golden **Fix-It Friday toolbox ghost** (round 2+): worth 5x, plus 5x on everything for 8 seconds.
- A **dad joke** on every loading screen.
- Chris's hair gets greyer every round (and every time he's hit). The round summary tracks it with the DAD HAIR GREY-O-METER.
- Dean checks himself out in a mirror if you stop firing for 2.5 seconds.
- Pepper is never more than 6 inches from Steph. If you play as Pepper, Mom keeps popping in to check on her.
- Pepper roasts low scores on the results screen.

### Privacy
Family photos were used as drawing reference only and are **never** committed. `.gitignore` blocks image files as a guardrail.

### GitHub Pages setup (one time)
1. Repo **Settings → General → Danger Zone → Change visibility → Public** (free Pages requires a public repo).
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)` → Save.**
3. Wait ~1 minute, then open the Play link above.
