# sadhana-site

Personal academic website for Sadhana Thirumangai, built on the [minimal-academic-website](https://github.com/onpix/minimal-academic-website) template by onpix.

## Live site

Once deployed: `https://sthirkal.github.io`  
*(replace `sthirkal` with your actual GitHub username)*

## How to deploy

1. Create a new GitHub repository named **`<your-username>.github.io`** (e.g. `sthirkal.github.io`).
2. Push this repo's contents to it:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/sthirkal/sthirkal.github.io.git
   git push -u origin main
   ```
3. In your repo on GitHub, go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**.
5. Set the branch to **`main`** and the folder to **`/ (root)`**.
6. Click **Save**. Your site will be live in ~60 seconds.

## Customisation

Everything is in `index.html` — it's a single self-contained file using [Tailwind CSS](https://tailwindcss.com/) via CDN. No build step needed.

- **Profile photo** — replace the `src` in the `<img>` tag at the top with a direct URL to your photo (or add a local image file to the repo).
- **Add a publication** — duplicate a `bg-gray-100` card inside the Publications section (currently the section is omitted since you have no publications yet — add it when you do).
- **Update experience / achievements** — edit the relevant `<li>` or card blocks directly in `index.html`.
