# Pearl Palace Reading Quest 👑🧜

A self-contained, gamified preschool reading lesson themed around princesses and mermaids. Made for early readers (~age 5).

## Play

Open `index.html` in any modern browser (iPad Safari works great), or:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

No build step. CSS and JavaScript are inline.

## Levels

1. **Welcome** — optional first name, story intro with Princess Coral
2. **Pearl Letter Hunt** — uppercase / lowercase letter recognition (~10 rounds)
3. **Sound Shells** — simple letter–sound phonics (~8 rounds)
4. **Sight Word Sparkles** — I, a, the, see, me, you, love, go, to, my (~8 rounds)
5. **Story Path** — 6-page interactive mermaid story; tap the missing word
6. **Crown Celebration** — pearl tally, reading rank, replay or palace map

You can also jump to any level from the **Palace Map**.

## Features

- Huge touch targets for tablets and phones
- Soft pink / lavender / aqua theme with CSS animations
- Pearls, stars, sparkles, and crown rewards
- Web Speech API reads prompts aloud (🔊 to hear again). Graceful if speech is unavailable
- Name + best pearl score saved in `localStorage`
- Keyboard: keys `1`–`4` choose answers; `R` / 🔊 repeats the prompt

## Hosting

Publish this folder (or just `index.html`) to any static host — GitHub Pages, Netlify, Surge, etc. — with `index.html` at the site root.
