# I Am One, But I Am a Legion

GitHub Pages package for the browser game.

## Files
- `index.html` — main game file (required for GitHub Pages root URL)
- `404.html` — fallback page using the same game file
- `.nojekyll` — disables Jekyll processing on GitHub Pages

## How to deploy on GitHub Pages
1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Commit the files.
4. Go to **Settings** → **Pages**.
5. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`), folder `/ (root)`
6. Save.
7. Wait 1–3 minutes, then open the Pages URL shown by GitHub.

## Important
If you upload only a file with another name, GitHub Pages root URL will show `404 File not found`.
The homepage file must be named `index.html`.
