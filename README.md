# Single-Box Prize Wheel

A static, image-only, weighted prize wheel for GitHub Pages.

The visible game screen contains only:

- One regular square image box
- One arrow
- One Spin button

During a spin, the single box rapidly cycles through the uploaded images and stops on the weighted result.

The customization drawer and recent-results panel remain completely hidden until opened with the floating buttons in the upper-right corner.

## Features

- True 1×1 image wheel
- Weighted random results
- Add, remove, duplicate, and reorder choices
- Upload an image for every choice
- Set an individual probability weight for every choice
- Customize the background, square box, borders, arrow, button, drawer, accent, and text colors
- Optional result popup, admin labels, percentages, history, sound, and confetti
- Browser saving through IndexedDB with localStorage fallback
- Export/import the full setup, including uploaded images
- Optional public `wheel-config.json`
- No framework, backend, database, or build process required

## Publish through GitHub Pages

1. Create a new GitHub repository.
2. Extract the ZIP.
3. Upload these files to the repository root:
   - `index.html`
   - `styles.css`
   - `app.js`
   - `.nojekyll`
   - `README.md` is optional
4. Commit the files.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Choose the `main` branch and `/ (root)`.
8. Click **Save**.

The address will normally be:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## Publish your customized wheel for everyone

1. Open the published website.
2. Open the gear button and customize the wheel.
3. Open **Behavior**.
4. Click **Export wheel file**.
5. Rename the downloaded file to `wheel-config.json`.
6. Upload it beside `index.html` in the GitHub repository.
7. Commit the change.

New visitors will receive that published configuration. Existing local browser changes take priority until **Clear local changes** is selected.
