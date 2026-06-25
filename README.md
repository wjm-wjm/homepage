# Jiangming Wang — Personal Homepage

A clean, modern, single-page personal homepage built with pure HTML, CSS and a tiny bit of vanilla JavaScript. Ready to be deployed to **GitHub Pages**.

🌐 **Live demo (after deploy):** `https://<your-username>.github.io/<repo>/`

---

## ✨ Features

- Modern hero section with animated gradient avatar
- Smooth-scroll, sticky navigation with active-section highlighting
- 🌙 Light / Dark mode toggle (preference saved to `localStorage`)
- Sections: About · Research Interests · Publications · Experience · Awards · Contact
- Fully responsive (desktop, tablet, mobile)
- No build step, no framework — just open `index.html`
- Accessible: respects `prefers-reduced-motion`

## 📁 File Structure

```
wjm_wjm/
├── index.html      # main page content
├── style.css       # all styles (light + dark)
└── README.md       # this file
```

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository, e.g. `wjm-wjm.github.io` (for a user site) or any `<repo>` (for a project site).
2. Push the contents of this `wjm_wjm/` folder to the repository root:

   ```bash
   git init
   git add .
   git commit -m "init: personal homepage"
   git branch -M main
   git remote add origin git@github.com:<your-username>/<repo>.git
   git push -u origin main
   ```

3. Open **Settings → Pages** → set **Source** to `main` branch / `root`.
4. Wait a minute and visit your URL ✨.

## 🛠️ Customize

- Change the avatar initials in `index.html` (search for `JW` inside `.avatar-inner`).
- Replace the placeholder Google Scholar link with your actual profile URL.
- Add or remove publications inside the `<ul class="pub-list">` block.
- Tweak colors via CSS variables at the top of `style.css` (`--primary`, `--accent`, `--gradient`).

## 👤 About

I am **Jiangming Wang**, a researcher at **Tencent Youtu Lab**, working on computer vision and machine learning. My research interests include **multimodal large language models**, **image forensics**, **deepfake detection**, and **AIGC detection**.

- 📧 51215901073@stu.ecnu.edu.cn
- 🐙 https://github.com/wjm-wjm/

## 📄 License

Feel free to fork and adapt. Content (text, publications, photos) © Jiangming Wang.
