# Deploy this page

Your site is ready to deploy. `index.html` is set as the main page so the root URL works on any host.

**Repo:** [github.com/Abhi12-lab/valentine-cat](https://github.com/Abhi12-lab/valentine-cat)  
**Live URL after GitHub Pages:** https://abhi12-lab.github.io/valentine-cat/

---

## Option 1: GitHub Pages (free, no extra sign-up)

1. **Push this folder to a GitHub repo** (if you haven’t already):
   ```bash
   git add .
   git commit -m "Add Valentine cat page"
   git push origin main
   ```

2. **Turn on GitHub Pages**
   - Open the repo on GitHub → **Settings** → **Pages**
   - Under **Source**, choose **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → **Save**

3. **Your site will be live at:**  
   **https://abhi12-lab.github.io/valentine-cat/**

---

## Option 2: Netlify Drop (instant, free)

1. Go to **[app.netlify.com/drop](https://app.netlify.com/drop)**
2. Sign in with GitHub/Email (one-time)
3. **Drag and drop** the whole `valentine special` folder onto the page
4. Netlify will give you a live URL right away

---

## Option 3: Surge (from terminal)

1. In a terminal, from this project folder, run:
   ```bash
   npx surge .
   ```
2. When asked, sign in or create a Surge account (email + password)
3. Accept the suggested domain or type one (e.g. `valentine-cat.surge.sh`)
4. Your site will be live at the URL Surge prints

---

## After deploying

- **GitHub Pages:** Updates go live when you push to the same branch.
- **Netlify:** Re-drag the folder to update, or connect the repo for auto-deploys.
- **Surge:** Run `npx surge .` again from this folder to update the same URL.
