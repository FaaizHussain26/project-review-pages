# Project Review Site

This folder is set up as a simple static website.

## Current pages

- `/` -> project review home
- `/realtime-speaker-brief/` -> standalone page for the uploaded HTML brief

## Fast local preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open:

- `http://localhost:8000/`

## Easy public hosting options

### GitHub Pages

1. Put this folder in a GitHub repo.
2. Push the repo.
3. In GitHub, open `Settings -> Pages`.
4. Set the deploy source to the main branch root.
5. Your site will be publicly accessible on a GitHub Pages URL.

### Netlify

1. Drag this folder into Netlify Drop, or connect a GitHub repo.
2. No build command is needed.
3. Publish the site.

### Vercel

1. Import the folder or repo into Vercel.
2. Framework preset: `Other`.
3. No build command is needed.
4. Output directory: leave blank.

## Adding more projects

For each new HTML file:

1. Create a new folder for that project.
2. Convert the provided HTML into a full `index.html`.
3. Add a card on the root `index.html` linking to it.
