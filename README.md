# Dixon Vimalajeewa — Academic Website

This repository contains an editable GitHub Pages website built with Jekyll. The site's main content is separated into Markdown files so that individual sections can be updated without editing the shared layout or styling.

## Main files to edit

| File | Website section |
|---|---|
| `index.md` | Homepage |
| `research.md` | Research directions |
| `publications.md` | Selected publications |
| `applications.md` | Application areas |
| `teaching.md` | Teaching and mentoring |
| `about.md` | Biography and academic timeline |
| `contact.md` | Contact information |

Shared page elements are stored in `_includes/`, the page shell is in `_layouts/default.html`, and the visual design is in `assets/css/style.scss`.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository. A repository named `yourusername.github.io` will publish at `https://yourusername.github.io`. Any other repository name will publish at `https://yourusername.github.io/repository-name/`.
2. Upload every file and folder from this package to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then click **Save**.
6. Wait a few minutes for GitHub Pages to show the published URL.

## If the site is in a project repository

For a repository such as `academic-website`, edit `_config.yml`:

```yaml
url: "https://yourusername.github.io"
baseurl: "/academic-website"
```

For a repository named `yourusername.github.io`, use:

```yaml
url: "https://yourusername.github.io"
baseurl: ""
```

## Add a new publication

Open `publications.md` and add a numbered entry beneath the appropriate year. For example:

```markdown
12. **Article title.** Author One, Author Two, and Dixon Vimalajeewa. *Journal Name*, volume, pages, year.
    <span class="pub-tags">Wavelets · Application · Statistical inference</span>
```

## Add a CV

1. Create a folder named `assets/files`.
2. Upload the CV as `Dixon_Vimalajeewa_CV.pdf`.
3. Add this button where desired:

```html
<a class="button button-primary" href="{{ '/assets/files/Dixon_Vimalajeewa_CV.pdf' | relative_url }}">Download CV</a>
```

## Preview locally (optional)

If Ruby and Bundler are installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

