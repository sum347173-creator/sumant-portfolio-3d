# Sumant Tiwary – 3D Portfolio

## Files
- index.html – the whole site (HTML, CSS, JS, content)
- assets/photo.jpg and assets/project-1..12.jpg – optimized images, keep the folder next to index.html
- resume.pdf – your résumé; the Résumé section's Download PDF button points to it. To update: replace resume.pdf and assets/resume.jpg (the preview image)

## Run locally
Open index.html in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000. Internet is needed for Three.js and the Kanit font; if either fails the site still works, without the 3D grid or with a fallback font.

## Edit content
Open index.html and find `const DATA=`. All text, links, skills, projects (with `details`), timeline and certificates are there.
- Project contribution and challenges: add `"contribution":"..."` and `"challenges":["..."]` inside a project's `details` and they appear in its Details dialog.
- Live demo: add a real URL as a `demo` link only if you have one (none are shown today).

## Deploy free
- Netlify Drop (app.netlify.com/drop): drag this whole folder.
- GitHub Pages: push the folder contents to a repo, then Settings > Pages > deploy from main branch.
After deploying, add an og:image meta tag with your live screenshot URL for link previews.
