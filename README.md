# Table Talk 🦃

A lightweight, family-friendly icebreaker app for the dinner table. It's one HTML file with no sign-ups, ads or tracking.

**Live:** https://mklaer86-create.github.io/Table-talk/

## How to use
- **✨ New question** makes up a brand-new question by mixing fun pieces (foods, animals, places, superpowers…)
- **Skip →** pulls the next question from the hand-written list
- **← Back** returns to earlier questions · **Copy** copies the current one
- Tap the category buttons to choose what kind of questions you get

## Editing questions
Everything is in `index.html`:
- `QUESTIONS` is the hand-written list, grouped by category
- `G` holds the word lists the generator mixes (add your family's favorite foods!)
- `TEMPLATES` holds the question patterns, each tagged with the categories it fits

## Tests
`node test.js` (needs Playwright) clicks every button and category in a real browser.
