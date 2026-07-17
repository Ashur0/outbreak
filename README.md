# OUTBREAK — Zombie Survival

A dark **WebXR survival-horror shooter**. Night has fallen and the dead are coming — hold
your ground, spend your points at the field station between rounds, and survive until dawn.
Playable **in a VR headset** (Meta Quest browser → *Enter VR*) or **in your browser** with
mouse/keyboard or touch.

▶ **Play: https://ashur0.github.io/outbreak/**

Single self-contained `index.html` (raw WebXR + WebGL, zero dependencies). Built by reskinning
the SWARM engine into a whole new game.

## Controls
- **VR** — trigger to fire, hold to charge; physically dodge.
- **Desktop** — mouse to aim, click to fire, **hold** to charge, **Q** for airstrike.
- **Mobile** — drag to aim, tap to fire.

## Features
- Rounds of escalating horde pressure, **BLOATER / BRUTE / ABOMINATION** bosses.
- Zombie variety: shamblers, runners (fast), spitters (ranged), splitters.
- **Survival mode** (50 nights) with a between-round **Field Station**: Med-Kit, Body Armor,
  Sentry Gun, Speed Cola, Double Tap (spend Points earned from kills).
- Charge shot, **Airstrike** ultimate, dread ambient soundtrack + gunfire + groans, a grim
  survivor radio voice, bloom (desktop), leaderboard, share card.

## Global leaderboard (optional)
Deploy `worker.js` on Cloudflare (free) and set `LB_URL` in `index.html` — see the same steps
as any of the stable's games.
