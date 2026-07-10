# 🎉 Birthday Site

A single-page birthday site — bright, playful, and interactive. No build step, no dependencies.

## 1. Personalize it

Open `index.html` in VS Code and edit these spots:

| What | Find this | Line area |
|---|---|---|
| Page title | `<title>Happy Birthday, Sunshine! 🎉</title>` | top of `<head>` |
| Her name in the big headline | `[Her Name]` | Hero section |
| The letter | the 3 `<p>` placeholders inside `<div class="letter-body">` | Letter section |
| Sign-off | `[Your Name]` | end of letter card |
| Surprise message after blowing the candle | text inside `<div class="surprise-msg">` | Cake section |

Tip: keep the letter honest and specific — a real memory or inside joke will land better than generic lines.

### Optional add-ons (ask me if you want these built in)
- A photo gallery / slideshow
- A countdown timer to her actual birthday
- Background music that plays on load
- A password/PIN gate so only she can open it

## 2. Preview locally

No build tools needed — just open the file:

```bash
open index.html        # Mac
start index.html       # Windows
```

Or run a tiny local server (recommended, avoids some browser quirks):

```bash
npx serve .
```

## 3. Deploy to Vercel

**Option A — Vercel CLI (fastest)**
```bash
npm i -g vercel
cd birthday-site
vercel
```
Follow the prompts (pick any project name). Vercel auto-detects it as a static site — no config needed. Run `vercel --prod` when you're happy with it to get your final live link.

**Option B — GitHub + Vercel dashboard**
1. Push this folder to a new GitHub repo.
2. Go to https://vercel.com/new and import the repo.
3. Leave all settings as default (Framework Preset: "Other") and click Deploy.
4. You'll get a live URL like `your-project.vercel.app` to send her.

## File structure
```
birthday-site/
  index.html   ← everything lives here (HTML + CSS + JS)
  README.md
```
