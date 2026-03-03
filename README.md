# Sivaramakrishnan M - Professional Resume Website

This is a structured professional resume website built using Jekyll.

## Structure

- Only the **About** section is visible on first load.
- Other sections (Education, Internships, Publications, Conferences, Certifications, Skills) are accessible through the sidebar click navigation.
- Clean white/grey background with black, blue, olive green, and gold accent colors.
- Default font: Times New Roman.
- Responsive sidebar layout.
- No duplication of resume formatting — structured presentation only.

## Folder Structure

/
│── index.md
│── _config.yml
│── README.md
│── assets/
│     └── style.css
│── _layouts/
│     └── default.html

## How to Deploy on GitHub Pages

1. Create a new repository on GitHub.
2. Upload all files from this folder.
3. Go to Settings → Pages.
4. Under "Source", select:
   - Branch: main
   - Folder: / (root)
5. Save.

Your site will be live at:
https://yourusername.github.io/repository-name/

## Local Testing (Optional)

If you have Ruby and Jekyll installed:

```
bundle install
bundle exec jekyll serve
```

Then open:
http://localhost:4000
