# Big Yellow Duck: The Cybertruck That Forgot How to Behave

Big Yellow Duck is not a quiet portfolio page. It is a bright, bilingual showcase for Derrick's high-voltage Cybertruck persona: part machine, part meme, part rolling photo magnet, and fully committed to duck-speed chaos.

## Visit The Site

- English: [derrickng1024.github.io/DerrickNg_Cybertruck](https://derrickng1024.github.io/DerrickNg_Cybertruck/)
- Simplified Chinese: [derrickng1024.github.io/DerrickNg_Cybertruck/index_cn.html](https://derrickng1024.github.io/DerrickNg_Cybertruck/index_cn.html)

## What Is Inside

This is a static bilingual website with:

- A bold English homepage in `index.html`
- A Simplified Chinese version in `index_cn.html`
- A personality-heavy About section for Big Yellow Duck and Derrick
- A gallery wall for people who crossed paths with the Cybertruck
- Contact links for photos, questions, business, banter, or duck-fueled brilliance

No build system is required. The site runs directly in the browser and is ready for GitHub Pages.

## Project Structure

```text
.
├── index.html          # English site
├── index_cn.html       # Simplified Chinese site
├── about_images/       # Main Cybertruck and Derrick images
└── gallery_images/     # Gallery feature photos
```

## Local Preview

Open either file directly in a browser:

```text
index.html
index_cn.html
```

For a local server preview, run one of these from the project folder:

```bash
python -m http.server 8000
```

Then visit:

- English: `http://localhost:8000/`
- Simplified Chinese: `http://localhost:8000/index_cn.html`

## Updating The Duck

To add a new gallery feature:

1. Put the image in `gallery_images/`.
2. Add a new `.gallery-person` block to both `index.html` and `index_cn.html`.
3. Keep the name, image path, and alt text aligned across both language versions.

To update the About section:

1. Edit the English copy in `index.html`.
2. Mirror the same story and energy in `index_cn.html`.
3. Keep the tone bold, playful, self-aware, and slightly unhinged. This is Big Yellow Duck, not a dealership brochure.
