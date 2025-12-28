# Light Ambassador — Portfolio

A clean, responsive personal portfolio site showcasing video editing, social media management, and content strategy work.

## 🚀 Quick overview
- **Built with:** HTML, CSS (no build step)
- **Purpose:** Showcase services, portfolio, testimonials, and contact links

## 🔍 Features
- Responsive hero, about, services, portfolio, tools, testimonials, and contact sections
- Easy to customize content and images
- Small green availability dot added to the hero badge (see **Styling / status dot**)

## 🛠️ Local preview
- Open `index.html` in your browser
- Or run a simple server (recommended for testing):
  - Python: `python -m http.server 8000` and open `http://localhost:8000`
  - VS Code: Use the Live Server extension and open `index.html`

## 🔧 Where to edit
- `index.html` — page content and structure
- `style.css` — global styles and layout
- `images/` — media assets

## ✨ Styling / status dot
A small green dot indicating availability was added as a CSS pseudo-element:
```css
.badge::before {
  content: "";
  width: 0.5rem;
  height: 0.5rem;
  background: #16a34a;
  border-radius: 50%;
  display: inline-block;
  box-shadow: 0 0 0 4px rgba(22,163,74,0.08);
}
```
Modify that rule in `style.css` to change size, color, or spacing.

## 📁 Project structure
```
index.html
style.css
images/
README.md
```

## 🤝 Contributing
- Make changes on a branch, open a PR, include a short description of what you changed.
- For small edits you can also edit files directly and open an issue explaining the change.

## 📜 License
No license specified — add a `LICENSE` file if you want to set one (e.g., MIT).

## ✉️ Contact
- Email: adepitanrapheal@gmail.com
- WhatsApp: https://api.whatsapp.com/send/?phone=2347010237138

---
Made with ❤️ — let me know if you want extra sections (changelog, live demo link, screenshots).