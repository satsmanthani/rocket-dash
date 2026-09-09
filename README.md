# 🚀 Rosie's Rocket Dash

A colorful arrow-key space rocket game! Dodge tumbling space rocks, grab shiny stars for points, and collect shield & speed power-ups.

**Controls:** Arrow keys (↑ ↓ ← →). On phones/tablets, use the on-screen buttons or swipe/drag the rocket.

## How to play
Open `index.html` in any web browser — no install needed.

## Deploy to GitHub Pages (step by step)

1. **Create a new GitHub repository**
   - Go to https://github.com/new
   - Name it something like `rocket-dash` (any name works)
   - Choose "Public"
   - Click **Create repository**

2. **Upload the game files**
   - On your new repo's page, click **"Add file" → "Upload files"**
   - Unzip this download on your computer, then drag in `index.html` and `README.md`
   - Click **"Commit changes"**

3. **Turn on GitHub Pages**
   - In your repo, go to **Settings → Pages** (left sidebar)
   - Under "Build and deployment" → "Source", choose **Deploy from a branch**
   - Branch: select `main` (or `master`) and folder `/ (root)`
   - Click **Save**

4. **Play!**
   - Wait about 1 minute, then refresh the Settings → Pages screen
   - You'll see a link like: `https://YOUR-USERNAME.github.io/rocket-dash/`
   - Open that link — your game is live for anyone to play! 🎉

### Alternative: using git command line
```bash
git init
git add index.html README.md
git commit -m "Add Rosie's Rocket Dash game"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/rocket-dash.git
git push -u origin main
```
Then enable Pages as described in step 3 above.

## Customizing
Everything (HTML, CSS, JavaScript) lives in the single `index.html` file, so it's easy to tweak:
- Change colors in the `COLORS` array or CSS gradients
- Adjust `rocket.speed` for faster/slower flying
- Change spawn rates in `spawnInterval` to make it easier or harder

Have fun, space captain! 🌟
