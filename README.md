# Ace of Spades Web Slots

A tiny, loud, in-browser slot machine themed around "Ace of Spades" energy (a tribute to Lemmy) -- reel locks, double-stakes, jackpots, and simple chiptune beep-riffs. It’s (hopefully) a fun little mini-game.

Play: https://flyingfathead.github.io/aceofspades-slots/

## What it is (and isn’t)
- It is: a single-page web slot game you can run in a tab.
- It isn’t: gambling, a casino sim, a blockchain thing, or a "strategy" game.
- Not affiliated with Motörhead or any rights holders -- this is just a fan tribute project.

## How to play
- Hit **SPIN**.
- You can **lock** reels (up to 2). Each lock increases the multiplier (locks double your bet -- x2 per lock).
- If you get offered **double-stakes**, that’s the risk button. Use it if you want to gamble the current state for a chance to climb back / spike higher.
- **Jackpots** exist. Sometimes you hit one. Usually you don’t. That’s slots.

There’s also a **Joker** mechanic in the symbol set (check the in-game rules text for how it behaves).

## Sound
This uses WebAudio. Most browsers require a user gesture before audio can start, so the first click is basically the "arm the sound engine" moment.

If your background music drowns out the UI blips, your browser or OS-level audio mixing is probably doing you dirty.

## Run locally
You can usually just open `index.html`, but if your browser is picky, serve it:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
