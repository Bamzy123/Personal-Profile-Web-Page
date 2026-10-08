# 👤 Personal Profile Website

A clean, single-page personal profile website built with **HTML** and **CSS**. It introduces Stephen Omotoso with a name, short bio, profile avatar, a list of hobbies/interests, and contact information — all using semantic HTML5 elements for clear structure and accessibility.

---

## 🌐 Live Preview

Open `index.html` directly in any modern browser — no server or build step required.

---

## 📁 Project Structure

```
Personal-Profile-Web-Page/
├── index.html     ← The complete single-page profile site
└── README.md      ← Project documentation (this file)
```

---

## ✨ Features

- **Semantic HTML5** — uses `<header>`, `<section>`, and `<footer>` for meaningful structure
- **Profile Avatar** — initials-based circular avatar with a gradient background
- **About Me** — short personal bio
- **Hobbies & Interests** — styled unordered list
- **Contact Info** — clickable email (`mailto:`) and GitHub links
- **Dark Theme** — modern dark colour palette using CSS custom values
- **Responsive Layout** — centred card layout that adapts to any screen size
- **No dependencies** — pure HTML + CSS, zero frameworks or libraries

---

## 🧱 Page Structure (Semantic HTML)

```
<body>
  <div class="container">
    <header>          ← Name, avatar, tagline
    <section#about>   ← Bio paragraph
    <section#hobbies> ← Hobbies & interests list
    <section#contact> ← Email and GitHub links
    <footer>          ← Copyright notice
  </div>
</body>

## 🎨 Colour Palette

| Role              | Colour    | Hex       |
|-------------------|-----------|-----------|
| Page background   | Dark navy | `#0f172a` |
| Card background   | Slate     | `#1e293b` |
| Headings          | Off-white | `#f8fafc` |
| Body text         | Light grey| `#cbd5e1` |
| Section headings  | Indigo    | `#a5b4fc` |
| Avatar gradient   | Purple    | `#6366f1` → `#8b5cf6` |
| Links             | Sky blue  | `#93c5fd` |

---

## 🚀 Getting Started

1. **Clone or download** this repository.
2. Open `index.html` in your browser — double-click the file or drag it into a browser window.
3. Customise the name, bio, hobbies, and contact details directly in the HTML file.

---

## 🛠️ Customisation Tips

- **Avatar**: Replace the `SO` initials inside `<div class="avatar">` with your own initials, or swap the `<div>` for an `<img>` tag pointing to a real photo.
- **Colours**: All colours are plain CSS values — search and replace any hex code to retheme the page instantly.
- **Hobbies**: Add or remove `<li>` elements inside `<section id="hobbies">`.
- **Contact links**: Update the `href` attributes in `<section id="contact">` with your own email and GitHub URL.

---

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
