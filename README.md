# EJ Fourth Trimester Guardian: team website

A static site for GitHub Pages that the CCSE C-Day program can link to.

## Update the content

Edit **`team.js`** only. Any field left as `""` is hidden on the page.

- **Photos:** add square images (at least 400 × 400 px) to `images/` and set `photo: "images/yourname.jpg"`.
- **Internship badge:** set `seekingInternship: true` and, if you like, describe it in `internshipNote`.
- **Projects:** add `{ name, description, link }` entries to `projects`.
- **Project section:** edit the `PROJECT` block at the top of `team.js` once the project is selected.

## Publish on GitHub Pages

1. On GitHub, create a **public** repository, for example `guardian-team`.
2. Upload `index.html`, `team.js`, `.nojekyll`, `README.md` and the `images` folder
   (**Add file > Upload files**, then **Commit changes**).
3. Go to **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**,
   **Branch** to `main` and the folder to `/ (root)`, then click **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/guardian-team/`.
   Send that link to the C-Day organizers.

Every later commit to `team.js` or `images/` updates the live site within a few minutes.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server` in this folder and visit http://localhost:8000.
