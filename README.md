# Personal homepage

Live site: <https://changjie-w.github.io/>

This is a plain HTML and CSS website. It does not require Jekyll, npm, or a build command.

## Edit on GitHub

1. Open the [`changjie-w.github.io`](https://github.com/changjie-w/changjie-w.github.io) repository.
2. Open `index.html` and click the pencil icon in the upper-right corner.
3. Replace the placeholder text, then click **Commit changes**.
4. Commit directly to `main`. GitHub Pages will normally update within a few minutes.

Common content to replace in `index.html`:

| Content | Search for |
| --- | --- |
| Name | `Changjie W.` |
| Initials in the avatar | `CW` |
| Short tagline | `A short introduction goes here.` |
| Location | `City, Country` |
| School or employer | `University / Company` |
| Email | `you@example.com` (replace both the visible text and `mailto:` value) |
| Google Scholar | Find the `Google Scholar` link and replace `href="#"` |
| Biography | Text inside `<section id="about">` |
| News | Text inside `<section id="news">` |
| Education | Text inside `<section id="education">` |
| CV link | Find the `CV` link in the navigation and replace `href="#"` |

## Change the appearance

Open `styles.css` in the GitHub editor. The color variables at the top control most of the design:

- `--background`: page background
- `--text`: main text color
- `--muted`: secondary text color
- `--accent`: links and highlights
- `--content-width`: maximum page width

## Preview locally

From the repository directory, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/>. Stop the server with `Ctrl+C`.
