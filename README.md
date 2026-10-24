# Zib & the Fuzzy Friends

A gentle, colorful skills game for kids, made with neurodivergent kids (ADHD, autism) in mind. Zib, a fuzzy rainbow alien puppet, guides kids through eight short games. There is no losing, no countdown to lose to, and no score that goes down. Wrong answers get a kind hint.

**Play:** open `index.html`, or visit the GitHub Pages site for this repo.

## The eight games

| Planet | Skill it practices |
|---|---|
| Balloon Breathing | Slow belly breathing (about 4 seconds in, 5 out), then a body check-in |
| Feelings Faces | Reading faces, naming feelings, choosing a safe coping idea |
| Gold Star Catch | Paying attention (tap only gold) and waiting (freeze on red) |
| First, Then | Putting everyday routines in order |
| Squeeze & Melt | Tensing and relaxing one body part at a time |
| Copy Cat Lights | Working memory and taking turns |
| Kind Words | Everyday social choices: joining in, asking for a turn, sorry, thank you |
| Time to Switch | Transitions, with a visual timer and a goodbye to each activity |

Each finished game earns a star, and every two stars unlocks a new fuzzy friend.

## Languages and voices

- English, Español, Français, Português and 中文 (pick on the start screen).
- Three character voices: **Zib** (squeaky alien), **Luna** (calm and gentle) and **Gus** (gentle giant). Every line is pre-recorded in all five languages, so it sounds the same on every device. The device's built-in voice is available as a backup in the Grown-up corner.

## For grown-ups

The gear button opens the Grown-up corner: Calm mode (softer colors, less motion, no confetti), Read to me, Sounds, language, voice, and notes on what each game practices. Progress is saved only in the browser on that device.

This is a practice game, not a treatment. A child's doctor, occupational therapist or counselor can suggest the skills that fit them best.

## Files

- `index.html`: the whole game in one page (no build step).
- `voices/<lang>.json`: which line is where in each audio file.
- `voices/<lang>_<character>.mp3`: the recorded lines for each language and character.

## Hosting on GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save. The site appears at `https://<user>.github.io/<repo>/` within a minute or two.

## Credits

- Voices were generated offline with [Kokoro-82M](https://github.com/hexgrad/kokoro) (Apache-2.0) using voice files from [kokoro-js](https://www.npmjs.com/package/kokoro-js) (Apache-2.0); character pitch and pace effects were added with FFmpeg.
- Fonts: Fredoka and Nunito from Google Fonts (SIL Open Font License).
- Fuzzy friends, art and code: original to this project.
