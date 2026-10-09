# Spot the Scam by Coded Female

Eight everyday cyber security scenarios. Investigate fictional messages, choose a safer next step and learn the reasoning behind every answer.

[Play Spot the Scam](https://codedfemale-dev.github.io/spot-the-scam/) · [Coded Female](https://codedfemale.com)

## Play

Open `index.html`, or visit the online game. There is no installation or build step. Choose one answer per scenario, read the explanation, then continue. Hints are optional and do not reduce your score. Both scenarios and answer options shuffle each round. Download your field notes or replay at the end.

## Skills demonstrated

- Vanilla JavaScript: data-driven rendering, stable answer IDs, Fisher–Yates shuffling, guarded state transitions and downloadable results.
- Responsive CSS using Coded Female's gold, charcoal and cream identity, with Open Sans, Playfair Display and Rokkitt font families.
- Accessible interactions: native buttons and disclosures, focus management, visible focus, progress, live announcements and text labels alongside colour feedback.
- Educational design: plausible choices, independent verification, a legitimate notification, non-judgemental feedback and practical takeaways.

## Files and remixing

| File | Purpose |
| --- | --- |
| `index.html` | Page structure and introduction |
| `style.css` | Responsive presentation |
| `questions.js` | Fictional scenarios, answer IDs and shuffle helper |
| `script.js` | Quiz state, feedback, review and download |
| `tests.cjs` | Data integrity and shuffle checks |

To add a question, copy a scenario in `questions.js`, give it a unique ID, provide three options with unique IDs, and set `correct` to the intended option ID. Keep addresses fictional, displayed as text rather than clickable links. Question order must not carry meaning. The interface derives the round length from the question bank.

Run `node --test tests.cjs` to check question integrity and shuffling.

## Privacy and accessibility

No sign-up, analytics, remote answer storage or local storage. Answers exist only in page memory and reset on reload. Google Fonts supplies the existing website font families; system fallbacks work when unavailable. Fictional addresses use `.example`. No suspicious link, QR code or attachment is functional. The favicon is a game magnifier, not a replacement brand logo.

No timer. Hints are free. The game supports mouse, touch and keyboard. It avoids treating a score as proof that someone is secure. Real scams can fool anyone.

## Guidance

This is an introductory practice game, not a certification or an incident-response service. For work accounts, follow organisational policy.

Content was checked against primary guidance on 9 October 2026:

- [NCSC: spotting scams](https://www.ncsc.gov.uk/collection/phishing-scams/spot-scams)
- [NCSC: reporting suspicious emails](https://www.ncsc.gov.uk/collection/phishing-scams/report-scam-email)
- [CISA: multi-factor authentication](https://www.cisa.gov/audiences/small-and-medium-businesses/secure-your-business/require-multifactor-authentication)

## Licence

MIT. See `LICENSE`. Contributions and remixes welcome.
