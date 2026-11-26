# Growth Audit · PureVPN

**Live:** https://bterzic123.github.io/purevpn-flow-rebuild/
(prototype directly: https://bterzic123.github.io/purevpn-flow-rebuild/?view=proto)

PureVPN's Meta ads sell three different things: streaming that works anywhere, privacy from
trackers, and staying connected while travelling. Every install still meets the same four slides
and the same paywall, "Your First 7 days are on us!". This audit rebuilds the first launch in
PureVPN's own design so that one question after the slides decides what the paywall says.

The prototype shows three phones side by side, one per ad promise, with a Today step (the
paywall as it ships), light/dark, a 30-second walkthrough and a QR code to open it on a phone.

## The five ideas

| # | Idea | Outcome |
| :-- | :-- | :-- |
| 1 | Ask what they want PureVPN for, then answer it on the paywall | CR +15–20% |
| 2 | Bring three rows of Compare all plans onto the paywall | CR +10–20%, ARPU +3–8% |
| 3 | Put your KPMG audit and App Store rating next to the plans | CR +10–15% |
| 4 | Let the wait set up what they picked | CR +10–15% |
| 5 | Show both plans at once and spell out the 7 free days | CR +5–15%, ARPU +3–8% |

Cancel on the paywall goes straight into the app. There is no second paywall.

## Grounding

Slides, paywall, prices (Max 99,99 € / 22,99 €, Standard 49,99 € / 12,99 €), the Max vs
Standard table and the home screen come from a screen recording of the PureVPN iOS app on the
EU storefront, 22 October 2026. 4.3 from 1.2K ratings, the 7-day free trial and renewal terms,
6,500+ servers, 10 devices and the KPMG-audited no-log policy come from PureVPN's App Store
listings (France and US), 26 November 2026. The ads are from PureVPN's Meta Ad Library page,
26 November 2026. Light mode is approximated; the app showed only its dark theme.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription
apps, not measured lift for PureVPN.

## Run locally

```
python3 -m http.server 8000
```
