# 👤 Personal Profile Website

A clean, single-page personal profile website built with **HTML** and **CSS**. It introduces Stephen Omotoso with a name, short bio, profile avatar, a list of hobbies/interests, and contact information — all using semantic HTML5 elements for clear structure and accessibility.

---

## 🌐 Live Preview

Open `profile.html` directly in any modern browser — no server or build step required.

---

## 📁 Project Structure

```
Personal-Profile-Web-Page/
├── profile.html   ← The complete single-page profile site
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
```

---

## 💻 Full Source Code

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stephen Omotoso - Personal Profile</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: #0f172a;
            color: #e2e8f0;
            line-height: 1.6;
            padding: 40px 20px;
        }

        .container {
            max-width: 640px;
            margin: 0 auto;
            background: #1e293b;
            border-radius: 16px;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }

        header {
            text-align: center;
            margin-bottom: 30px;
        }

        .avatar {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            background: linear-gradient(135deg, #6366f1, #8b5cf6);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 56px;
            font-weight: bold;
            color: white;
            margin: 0 auto 16px auto;
            border: 4px solid #4f46e5;
            box-shadow: 0 4px 12px rgba(99, 102, 241, 0.4);
        }

        .avatar-label {
            font-size: 12px;
            color: #64748b;
            margin-top: -8px;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 28px;
            color: #f8fafc;
        }

        .tagline {
            color: #94a3b8;
            font-size: 16px;
            margin-top: 4px;
        }

        section {
            margin-top: 28px;
        }

        h2 {
            font-size: 18px;
            color: #a5b4fc;
            border-bottom: 1px solid #334155;
            padding-bottom: 8px;
            margin-bottom: 12px;
        }

        p {
            color: #cbd5e1;
        }

        ul {
            list-style: none;
            padding-left: 0;
        }

        ul li {
            background: #0f172a;
            padding: 10px 14px;
            border-radius: 8px;
            margin-bottom: 8px;
            color: #e2e8f0;
        }

        .contact-info a {
            color: #93c5fd;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            margin-top: 32px;
            font-size: 13px;
            color: #64748b;
        }
    </style>
</head>

<body>

    <div class="container">

        <header>
            <div class="avatar">SO</div>
            <p class="avatar-label">(Profile photo)</p>
            <h1>Stephen Omotoso</h1>
            <p class="tagline">Student &amp; Aspiring Web Developer</p>
        </header>

        <section id="about">
            <h2>About Me</h2>
            <p>
                Hi, I'm Stephen! I'm based in Lagos, Nigeria, and I'm currently learning web development,
                starting with HTML and CSS. I enjoy building things with code and exploring how websites
                are put together. This page is one of my first projects as I work on sharpening my
                front-end skills.
            </p>
        </section>

        <section id="hobbies">
            <h2>Hobbies &amp; Interests</h2>
            <ul>
                <li>Building side projects and exploring new frameworks</li>
                <li>Watching action movies and series</li>
                <li>Mentoring and tutoring upcoming developers</li>
            </ul>
        </section>

        <section id="contact" class="contact-info">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:stephenomotos@gmail.com">stephenomotos@gmail.com</a></p>
            <p>GitHub: <a href="https://github.com/Bamzy123" target="_blank">github.com/Bamzy123</a></p>
        </section>

        <footer>
            &copy; 2026 Stephen Omotoso. All rights reserved.
        </footer>

    </div>

</body>

</html>
```

---

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
2. Open `profile.html` in your browser — double-click the file or drag it into a browser window.
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
