# Public Assets

This repository is used to host publicly accessible assets (e.g. images) that can be fetched via exposed URLs.

## Purpose

Instead of embedding large or frequently used media files directly into project files, this repo provides a central place to store and serve assets via direct links (URLs). This is useful for web projects, markdown files, or any application that needs external asset references.

## Usage

To use an image or asset from this repo, simply copy the raw file URL. For example:

https://raw.githubusercontent.com/your-username/public-assets/main/images/example-image.png

You can embed it in:

### Markdown

```markdown
![Alt Text](https://raw.githubusercontent.com/your-username/public-assets/main/images/example-image.png)
```

### HTML
```html
<img src="https://raw.githubusercontent.com/your-username/public-assets/main/images/example-image.png" alt="Example Image">
```

## Structure

Organize files in folders (e.g., images/, audio/, videos/, etc.) to keep things tidy.

## Notes

This repo should only contain static, publicly shareable assets.

Avoid uploading sensitive or private files.
