# Pearl Palace Reading Quest 👑🧜

A self-contained, gamified preschool reading lesson themed around princesses and mermaids. Made for early readers (~age 5).

## Play

Open `index.html` in any modern browser (iPad Safari works great), or:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

No build step. CSS and JavaScript are inline.

## Levels (full quest order)

1. **Sound Shells** — letter–sound phonics warm-up (6 rounds)
2. **Sight Word Sparkles** — find / listen-and-find sight words (8 rounds, word set 1)
3. **Bubble Pop** — pop the floating bubble with the spoken word (8 rounds, sets 1–2)
4. **Treasure Chest Match** — memory match of sight-word pairs (2 boards, 6 matches, sets 2–3)
5. **Magic Mirror** — read the word yourself, tap the picture it means (6 rounds)
6. **Seashell Sentences** — tap word shells in order to build a sentence, read aloud (6 rounds)
7. **Story Path** — 6-page mermaid story; tap the missing word
8. **Crown Celebration** — pearl tally, first-try stars, rank, replay or Palace Map

Any level can be replayed on its own from the **Palace Map**.

## Sight words (25, introduced in three waves)

- Set 1: I, a, the, see, me, you, love, go, to, my
- Set 2: is, it, in, can, we, like, and, up
- Set 3: look, here, play, red, big, said, no

## Features

- Huge touch targets for tablets and phones
- Soft pink / lavender / aqua theme with CSS animations
- Pearls, stars, sparkles, and crown rewards
- Web Speech API reads prompts aloud (🔊 to hear again). Graceful if speech is unavailable
- Name + best pearl score saved in `localStorage`
- Keyboard: keys `1`–`9` choose the Nth answer / chest / shell; `R` / 🔊 repeats the prompt

## Hosting

Publish this folder (or just `index.html`) to any static host — GitHub Pages, Netlify, Surge, etc. — with `index.html` at the site root.
