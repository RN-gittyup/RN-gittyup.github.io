# Handwash Hero: Cosmic Clean-Up (v2)

A new sci-fi prototype focused on varied pretend clean/dirty scan levels, animated gremlin characters, a 20-second wash timer, a tap-to-pop bubble minigame, and collectible sticker rewards.

## Preview
Open `index.html` in a browser. Camera viewfinder and service worker features need HTTPS or localhost. If camera access is granted, it shows a live view only; frames are not analyzed, captured, stored, or uploaded. Scan results are randomly selected unless the demo parent Family Pass selects an outcome.

## Character animation update (v3)
The gremlin encounter now has three individually designed SVG characters with shaded, dimensional styling and distinct personalities: Mischief (sneaky), Fizz (hyperactive), and Doomdrop (dramatic boss). Their portal entrance, body acting, eye movement, gestures, dialogue, and escape animation play as a short scene. The wash timer includes an animated soap-power stage with escalating prompts and a foam-blast victory. Characters are stylized 2D vector artwork with layered shading and motion, not actual 3D models.

## Files
- `index.html` — app, animations and game logic
- `manifest.json` — PWA manifest
- `sw.js` — offline cache
- `icon.svg` — icon source

## Production before App Store
This is not yet an App Store submission. Wrap with Capacitor, build/sign through a Mac or cloud macOS runner, implement StoreKit $4.99 purchase and restore, secure parent gate, privacy policy, support URL, accessibility checks and child-privacy review. Keep marketing clear that scans are simulated and never detect germs.
