# 🏀 BallKings — Ultimate Basketball Card Game

A fully browser-based basketball card game with arcade gameplay, 600+ player cards, a live transfer market, and progression systems. No build step, no server — pure HTML/CSS/JS.

**Live at:** `https://YOUR_USERNAME.github.io/BallKings/`

---

## 📋 How to paste files into GitHub (no Git needed)

### Step 1 — Create the workflow file
- In your repo click **Add file → Create new file**
- In the name box type: `.github/workflows/deploy.yml`
- Paste the contents of `deploy.yml`
- Click **Commit changes**

### Step 2 — Create the game
- Click **Add file → Create new file**
- Name it `index.html`
- Paste the contents of `index.html`
- Click **Commit changes**

### Step 3 — Enable GitHub Pages
- Go to **Settings → Pages**
- Set **Source** to **GitHub Actions**
- Done! Your game deploys automatically in ~30 seconds.

---

## 🎮 Controls

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move | WASD / Arrow Keys | D-Pad |
| Shoot | Z or Space (hold + release) | SHOOT button |
| Pass | X | PASS button |
| Steal | C | STEAL button |
| Block | C (ball in air) | BLOCK button |

---

## 🃏 Card Variants

| Variant | Rarity | OVR Boost |
|---------|--------|-----------|
| Base | Common | +0 |
| Rookie | Uncommon | +5 |
| Elite | Rare | +12 |
| All-Star | Epic | +20 |
| Prime | Legendary | +28 |
| Legend | Ultra | +35 |
| Icon | Mythic | +44 |

All stats strictly capped 30-100. Hall of Famers get all 7 variants.

---

## 💾 Save System
Auto-saves to localStorage — no backend needed. 100% GitHub Pages compatible.
