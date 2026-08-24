# Kirjo

A colour-sorting puzzle. Pour a colour onto the same colour or into an empty
vial; a vial is finished when it is full of one colour. Three rules, 500
hand-measured levels across five chapters, and a par on every one of them that
is the true minimum — proved by search, not estimated.

No ads, no accounts, no analytics. Helpers are for the stuck, never the price
of admission.

**App Store:** coming soon
**Website & support:** https://dresende.github.io/kirjo/
**Privacy policy:** https://dresende.github.io/kirjo/privacy.html

This repository hosts Kirjo's public website (GitHub Pages). It is plain
hand-written HTML with no build step and no dependencies, the same as Sikku's.

`privacy.html` is the page the app links to from **Settings → i → Privacy
policy**, so the URL is compiled into a shipped build: `AboutSheet.swift` in
the (private) app repo holds it as a constant. Moving or renaming this file
breaks a link inside every copy of the app already installed.

The palette mirrors `Shared/Theme.swift` in the app repo — the link colour is
chapter one's sunrise, `#FFC46B`. The claims in `privacy.html` mirror what the
app actually does: `PuzzleModel`'s iCloud sync, `GameCenter`'s opt-in, `Store`'s
consumables and `Chime`'s synthesised audio. If any of those change, this page
changes with them.

Questions or feedback: [dresende@thinkdigital.pt](mailto:dresende@thinkdigital.pt)
