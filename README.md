# amoghrex.vercel.app

My portfolio. One static page (`index.html`), no build step, hosted free on Vercel.

The animations (name traced in light, the headlight that follows your cursor, the scroll-speed stack band) are plain SVG, CSS and a little JavaScript at the bottom of `index.html`. They switch off for anyone who has reduced motion turned on.

- Edit text: open `index.html` and change the words. Sections are marked with `id`s (work, zeriux, experience, wins, education, stack, off).
- Add a project: copy one `<li>` inside `<ul class="proj">` and change it.
- Font: Archivo (SIL Open Font License, see `fonts/OFL.txt`), self-hosted.

Push to `main` and Vercel redeploys on its own.
