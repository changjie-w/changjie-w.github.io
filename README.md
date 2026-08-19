# Changjie W. Personal Page

Live site: <https://changjie-w.github.io/>

This site uses [Jekyll](https://jekyllrb.com/) and the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template, which is based on Minimal Mistakes.

## Edit on GitHub

You can edit the site without installing anything:

1. Open a file in this repository.
2. Click the pencil icon.
3. Make your changes and click **Commit changes**.
4. Commit to `main`; GitHub Pages will rebuild the site automatically.

The most useful files are:

| File | What to edit |
| --- | --- |
| `_config.yml` | Name, sidebar biography, location, employer, email, profile links, and site title |
| `_pages/about.md` | Homepage introduction, news, education, projects, and service |
| `_pages/cv.md` | CV page |
| `_data/navigation.yml` | Top navigation links |
| `images/profile.svg` | Current placeholder portrait |
| `_includes/footer/custom.html` | Extra footer content such as the Sitemap link |

To use a real portrait, upload an image such as `images/profile.jpg`, then change this line in `_config.yml`:

```yaml
avatar: "profile.jpg"
```

To publish a PDF résumé, upload it as `files/cv.pdf` and link to `/files/cv.pdf` from `_pages/cv.md` or `_data/navigation.yml`.

## Preview locally

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve --config _config.yml,_config_local.yml
```

Open <http://localhost:4000/>. Changes to `_config.yml` require restarting Jekyll.
