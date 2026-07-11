# The Underground — Study Network Builder

A gamified study/habit tracker themed on the London Underground (1863–present).
Log honest hours toward *your* goal — an exam, course, project, thesis, or skill —
and each study day opens the next real Tube station in chronological order. Complete
all **272 stations** and the Underground is crowned #1 in the world.

It is a single self-contained `index.html` file: all images, the subway chime, the
station data, and every line diagram are embedded. No build step, no dependencies,
nothing to install. Progress saves automatically in your browser.

## Play it online (GitHub Pages)

1. Create a new GitHub repository (public), e.g. `study-tube`.
2. Upload **`index.html`** and **`.nojekyll`** to the repository root
   (drag-and-drop via *Add file → Upload files*, then *Commit*).
3. Go to **Settings → Pages**.
4. Under *Build and deployment*, set **Source: Deploy from a branch**,
   **Branch: `main`**, **Folder: `/ (root)`**, then **Save**.
5. Wait ~1 minute, then open the URL GitHub shows you, e.g.
   `https://<your-username>.github.io/study-tube/`

That's it. Because it's served over `https://`, the "Every Tube Station Song" video
in the Guide tab plays inline too (locally it opens on YouTube instead).

> The `.nojekyll` file tells GitHub Pages to serve the file exactly as-is.
> Keep it in the repo root.

## Run it locally

Just double-click `index.html` — it works offline. The only difference is the Guide-tab
video opens on YouTube in a new tab rather than playing embedded (a browser security
rule for local files, not a bug).

## Make it yours

On first run, a short setup lets you name your goal and pick your focus areas.
Everything is editable later under **Settings**: your goal, focus areas/topics,
the scoring bands, and the 272-day target. Use **Reset** to start a fresh campaign.

## Notes

- Progress is stored in your browser (localStorage) for the site/file you open it from.
  Different URLs (e.g. local file vs GitHub Pages) keep separate progress.
- The eleven line route diagrams in the Guide tab are © londontubemap.org, kept with
  their attribution intact.
