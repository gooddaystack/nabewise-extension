# NabeWise

The browser extension names the official NabeWise neighborhood on a listing. It is not a listings site, and it is not a coupon tool.

Install it from a store. Do not treat this repository as the download.

- [Chrome Web Store](https://chromewebstore.google.com/detail/nabewise/bopfajaffpbokanocajiiahmodjhmdcc?hl=en)
- [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/nabewise/oeopfiofngdclhncbpmdbidenploaaaa)
- Site: [nabewise.com](https://nabewise.com)
- Privacy: [nabewise.com/privacy](https://nabewise.com/privacy)

## What it does

Version 1.2 reads the visible title and address on a listing page in the browser, matches that text to an official neighborhood, and shows a card. A click opens `https://nabewise.com/{city}/{slug}`.

It runs on:

- Zillow
- StreetEasy
- Apartments.com
- HotPads
- Realtor.com

It does not run on every site.

## What stays on your machine

The neighborhood list ships with the extension. Matching happens locally. Listing text is not sent to nabewise.com. A city filter, if you set one, stays in `chrome.storage.local` on that browser.

The live policy is [nabewise.com/privacy](https://nabewise.com/privacy). A short copy is in [PRIVACY.md](PRIVACY.md).

## This repository

This is the public note for 1.2.0: the manifest, the background worker, and the privacy note. The website source stays in a separate private repository. There is no installable zip here.
