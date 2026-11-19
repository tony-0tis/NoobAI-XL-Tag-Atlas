# NoobAI-XL Tag Atlas

**A lightweight, multilingual booru tag reference for anime image generation.**

[Live Demo](https://huggingface.co/spaces/donkilluminatti/noobai-xl-tag-atlas) | [Download Archive](https://github.com/tony-0tis/NoobAI-XL-Tag-Atlas/archive/refs/heads/main.zip)

## About

NoobAI-XL Tag Atlas is a free reference tool created to make searching and understanding booru-style tags easier.

It currently includes **2,926 tag entries across 24 categories**, with descriptions in English, Russian, and Chinese.

The project prioritizes simplicity: no build tools, no backend, no database, and no complex installation.

## Features

- Search tags by name or description
- Browse thematic categories
- Copy tags by clicking them
- Show or hide NSFW categories
- Switch between EN / RU / ZH
- Responsive layout
- Maintain tags and translations through a separate JSON catalog
- Edit catalog data using a standalone HTML editor

## Project Structure

```text
noobai-tag-atlas/
├── index.html
├── catalog.json
└── editor.html
```

## Running the Atlas

**Online:** https://0t.is/noodai_atlas/

**Locally:**

1. Download the project files.
2. Open `index.html` in your browser.
3. If the browser restricts loading local JSON files, manually select `catalog.json`.

An internet connection is required for the Vue 2 and BootstrapVue CDN dependencies.

## Editing the Catalog

Open `editor.html`, import `catalog.json`, and edit tags, descriptions, categories, or translations.

Export the updated JSON file and replace the previous catalog.

## Languages

- English
- Russian
- Simplified Chinese

Some translations are still being refined. Contributions and corrections are welcome.

## Credits

- **Idea and author:** Tony Outis
- **Implementation:** ChatGPT (OpenAI)

## Disclaimer

This is an independent community reference, not an official NoobAI-XL project. The presence of a tag in the catalog does not guarantee that every model will interpret it as intended.

## License

License to be determined.
