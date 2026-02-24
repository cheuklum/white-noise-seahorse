# White Noise Website

A simple, beautiful white noise generator that runs entirely in your browser.

## Features
- Clean, minimal design
- Volume control
- Uses Web Audio API (no external files needed!)
- Mobile-friendly

## Test Locally

Just open `index.html` in your browser and click Play!

## Deploy to GitHub Pages

### Step 1: Create a GitHub repository
```bash
cd /Users/saho/Documents/fmm-garage/white-noise-site
git init
git add .
git commit -m "Initial commit: white noise generator"
```

### Step 2: Create repo on GitHub
1. Go to https://github.com/new
2. Name it `white-noise` (or whatever you want)
3. Don't initialize with README (we already have files)
4. Click "Create repository"

### Step 3: Push to GitHub
```bash
# Replace YOUR-USERNAME with your GitHub username
git remote add origin https://github.com/YOUR-USERNAME/white-noise.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** tab
3. Click **Pages** in the left sidebar
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait ~1 minute

Your site will be live at: `https://YOUR-USERNAME.github.io/white-noise/`

## How it works

The site uses the Web Audio API to generate white noise by creating a buffer filled with random values. No audio files needed!
