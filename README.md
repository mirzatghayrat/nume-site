# NUME official website

Official website, support page and privacy policy for **NUME**, a hand-drawn math puzzle adventure for iPhone and iPad by Mierzati Aireti.

- Website: https://aralem.dev/nume-site/
- Support: https://aralem.dev/nume-site/support/
- Privacy policy: https://aralem.dev/nume-site/privacy/
- Contact: support@aralem.dev

## What this is

Three hand-written static pages plus one stylesheet. No build step, no server, no analytics, no third-party scripts. Fonts and media are served from this repository; license records live next to the assets:

| Asset | Source | License |
|---|---|---|
| `assets/CaveatBrush-Regular.ttf` | Caveat Brush | `assets/OFL-CaveatBrush.txt` (SIL OFL 1.1) |
| `assets/SpaceMono-Bold.ttf` | Space Mono | `assets/OFL-SpaceMono.txt` (SIL OFL 1.1) |
| `assets/nume-preview.mp4` music | MintoDog, OpenGameArt | `assets/MUSIC-LICENSE.md` (CC0 1.0) |
| `assets/shots/*.jpg` | Native NUME screenshots (build 1.0.0), also used on the App Store | © Mierzati Aireti |

## Editing

Edit the HTML directly and push to `main`; GitHub Pages serves the repository root. Links are relative so the pages also open from a local folder. The privacy policy text must stay identical to the copy inside the app (`PrivacyPolicyView`) and to the App Store privacy declaration; change all three together and update the effective date.

When the app is live, replace the "Coming to the App Store" key in `index.html` (search for `store-link`) with the App Store link.
