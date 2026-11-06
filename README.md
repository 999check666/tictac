# 8×8 Three-in-a-Row

A small two-player browser game. Black and Green take turns filling empty squares. The first player to connect three squares horizontally, vertically, or diagonally wins.

## Files

- `index.html` — the complete game. React and Babel are loaded from CDNs, so this file does not need a build step.
- `README.md` — this guide.

## Run the game

Open `index.html` in a browser while connected to the internet. The game loads React and Babel from online CDNs.

## Publish with GitHub Pages

1. Create a **public** GitHub repository.
2. Add both `index.html` and `README.md` to the top level of the repository (not inside a folder). The file named `index.html` is essential: GitHub Pages uses it as the home page.
3. Commit the files to the `main` branch.
4. In the repository, open **Settings** → **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then click **Save**.
7. Wait a few minutes. GitHub will show the published site address in the Pages settings.

The site needs an internet connection in visitors’ browsers because React and Babel come from CDNs. Everything in a public repository can be viewed by anyone, so do not put passwords, API keys, or private information in it.
