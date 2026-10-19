# Spring Scroll Race · 春游竞速

A self-contained browser racing game inspired by 《虢国夫人游春图》. All game code, Phaser, and original-painting image crops are embedded in `index.html`. Supports single-player vs AI and local two-player racing. This static edition does not include online rooms.

## Publish with GitHub Desktop and GitHub Pages

1. In GitHub Desktop, sign in to your GitHub account.
2. Choose **File → Add Local Repository**, then select this `spring-race-github` folder.
3. Commit the three files with a summary such as `Publish playable game`.
4. Choose **Publish repository**. Use a public repository for GitHub Pages on GitHub Free.
5. Open the repository on GitHub → **Settings → Pages**.
6. Choose **Deploy from a branch → main → /(root)**, then **Save**.
7. Use the URL displayed by GitHub Pages once the deployment completes. `/index.html` also opens the game directly.

No build command, npm installation, backend, or environment variables are required. The `.nojekyll` file tells Pages to serve the already-built HTML.

## Controls

Player 1: W/S change lane, D/A accelerate/brake, Space jump, Shift dash, E use item.
Local player 2: I/K change lane, L/J accelerate/brake, U jump, O dash, P use item.
