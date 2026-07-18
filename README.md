# 🎈 Kids Videos — Little Learners

A cheerful little library of playful, video-style learning pages for toddlers.
The homepage shows a **tile grid**; tapping a tile opens that lesson full-screen.

**Live site:** https://omisabnis5.github.io/kids-videos/

## Lessons

| Tile | Page | Path |
|------|------|------|
| 🔤 ABC Alphabets | Watch a friendly crayon draw every capital letter A–Z | [`/alphabets/`](alphabets/) |
| 🔢 123 Numbers | Draw & count numbers over a range you choose (1–10, 1–20, 1–30, 1–50, or custom) | [`/numbers/`](numbers/) |
| 🦁 The Lion & the Mouse | A picture-book story-time video of the classic fable, scene by scene | [`/lion-and-mouse/`](lion-and-mouse/) |
| 🔺 Shapes | _coming soon_ | — |
| 🌈 Colors | _coming soon_ | — |

## ABC Tracing Time!

An auto-playing alphabet show for ~3-year-olds. A googly-eyed crayon draws every
**capital letter A–Z** stroke by stroke on real kindergarten writing lines, with:

- 🗣️ a cheerful, kid-friendly voice that changes what it says each letter
- 🎵 the ABC song, slide-whistle "wheee!"s, crayon-scribble sounds and boing-pops
- ✨ sparkle trails, dancing letters, and confetti-star celebrations
- 🍎 "A is for Apple!" picture words for every letter
- ⏮️ ⏯️ ⏭️ 🔁 big toddler-friendly controls, plus an A–Z picker
- 🌗 light & dark themes, and Voice / Sounds toggles for quiet time
- 🏠 a Home button back to the tile grid

### For grown-ups
The numbered dots show stroke order. Pause on any letter and let your child trace
it in the air, on your palm, or on paper with a chunky crayon.

> Tip: the voice sounds friendliest in Chrome or Edge on a phone/tablet, which have
> higher-quality built-in voices.

## Structure

```
index.html                 → homepage tile grid
alphabets/index.html       → the ABC tracing lesson
numbers/index.html         → the counting & number-tracing lesson
lion-and-mouse/index.html  → "Lion and the Mouse" picture-book story
lion-and-mouse/img/        → the story's classic illustrations
```

## 🦁 The Lion & the Mouse — Story Time!

An auto-playing, 8-scene retelling of Aesop's famous fable, built for toddlers and
preschoolers — told with **classic public-domain storybook illustrations** that actually
depict each moment of the story:

- 🖼️ real book art for every scene — the sleeping lion (Aunt Louisa's chromolithographs),
  the pleading mouse (Paul Bransom), the lion caught in the net (Milo Winter) — with a
  gentle Ken-Burns drift and crossfades so the pictures feel alive
- 🗣️ a storyteller voice that reads each scene sentence by sentence (so words are never
  cut off), using the most natural voice the device has
- 🔔 gentle sound effects that fit each scene — soft snores while the lion sleeps, a mouse
  squeak, a big roar, nibbling, and a happy cheer at the end
- ⏮️ ⏯️ ⏭️ 🔁 big toddler-friendly controls, plus a scene picker
- 🌗 light & dark themes and Voice / Sounds toggles for quiet time
- 🏠 a Home button back to the tile grid
- 🖼️ an illustration-credits panel — every picture is from Wikimedia Commons and in the
  public domain (classic 19th–early-20th-century book art)

> Note on the voice: it uses the browser's built-in text-to-speech, so it sounds most
> natural in Chrome or Edge. For the warmest story time, turn the voice off and read the
> captions aloud yourself.

**Moral:** _even the smallest friend can be the greatest help._

Every page is a single self-contained HTML file — no build step, no dependencies.
To add a new lesson: create `mylesson/index.html` and add a matching tile on the homepage.
