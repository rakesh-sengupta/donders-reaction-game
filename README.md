# Donders' Three Reactions

A six-minute reaction-time experiment for the Interlude session of
*Introduction to Neuroscience* (Krea University). It recreates
F. C. Donders' subtraction method (1868):

- **Game A** (simple): respond to a blue circle.
- **Game C** (one shape): respond to the blue circle, not to an orange square.
- **Game B** (choice): a different response for each shape.

At the end, each student sees their median reaction times for the three
games and two differences: C − A (telling the shapes apart) and B − C
(choosing the response).

**Privacy:** nothing is saved or sent. All data stay in the student's
browser tab and disappear when it is closed.

## Files

| File | What it is |
|---|---|
| `index.html` | The experiment (one page) |
| `lib/jspsych-7.3.4.min.js` | jsPsych 7.3.4 (MIT licence), stored locally so the page does not depend on a CDN |
| `lib/plugin-html-button-response-1.2.0.min.js` | jsPsych button plugin (MIT licence) |
| `lib/LICENSE-jsPsych.txt` | jsPsych licence |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publishing on GitHub Pages

1. On GitHub, create a new **public** repository, e.g. `donders-reaction-game`.
2. Upload everything in this folder, keeping the `lib/` folder.
   The `.nojekyll` file is hidden on most computers: upload it too if you can,
   but the site still works without it.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose
   **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at
   `https://<your-username>.github.io/donders-reaction-game/`.

## Credits

Built with jsPsych (de Leeuw, J. R., 2015, *Behavior Research Methods* 47, 1–12).
Fonts: Atkinson Hyperlegible and IBM Plex Mono, from Google Fonts
(the page falls back to system fonts if these cannot load).
