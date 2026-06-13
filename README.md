# Florida Through a Caribbean Lens

Static GitHub Pages site for Luis Tapia's proposed mixed-media art project.

## Files

- `index.html` — main website page
- `styles.css` — visual design and responsive layout

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example: `florida-caribbean-lens`.
2. Upload `index.html` and `styles.css` to the root of the repository.
3. Go to repository `Settings` → `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/root`, then save.
6. Wait a minute or two for GitHub Pages to publish.

## Editing content

Open `index.html` and edit the text between the HTML tags. Work sample cards are in the section with `id="works"`.

## Adding images later

Create a folder named `images`, upload your artwork images, then replace each placeholder block:

```html
<div class="work-image placeholder">Image</div>
```

with:

```html
<img class="work-image" src="images/example.jpg" alt="Artwork title by Luis Tapia">
```

