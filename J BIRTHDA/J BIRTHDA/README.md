# Birthday page

Open `index.html` in a browser (or run `npx serve .` in this folder).

## Flow
1. Lantern background video + "Click here" button
2. Lantern rise transition, then full-screen dog video with "Open it" button
3. Envelope (tap to open), then the letter with a video slot

## Files
- `index.html` - the whole page (HTML, CSS and JS in one file)
- `assets/bg.mp4` - background video (door and lanterns)
- `assets/dog.mp4` - dog with the "Open It" letter
- `assets/poster.jpg` - first frame shown before the background video loads
- `assets/music.mp3` - birthday instrumental (plays from the door opening until the lanterns blow up; replace with any mp3 under the same name)
- `assets/letter.mp4` - birthday video inside the letter

## Running Locally
- The local server is running at: `http://localhost:3000`
- To run anytime: `npm run dev` or `npx serve . -l 3000`

## Deploy to Vercel

### Option 1: Via Vercel CLI (Fastest)
Run the following in the project terminal:
```bash
npx vercel
```
Follow the one-time interactive login prompt in your browser. For production deployment:
```bash
npx vercel --prod
```

### Option 2: Via GitHub (Recommended for automated updates)
1. Initialize git and push this project to GitHub.
2. Go to [vercel.com](https://vercel.com) and click **"Add New..." > "Project"**.
3. Import your GitHub repository and click **Deploy**.

