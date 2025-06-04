# 🌩️ NimbusCSS

A custom CSS framework built with Sass. Includes theme styles and utility classes for rapid HTML development.

---

## 📦 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/NimbusCSS.git
   cd NimbusCSS
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the CSS:
   ```bash
   npm run build
   ```

---

## 🚀 Usage

In your HTML, include:

```html
<link rel="stylesheet" href="dist/style.css">
```

Use classes like:
```html
<h1 class="text-bold text-center">Title</h1>
<button class="btn-primary">Click Me</button>
<div class="m-2 p-2 border">Utility Box</div>
```

---

## 🎨 Customization

Modify theme variables in `scss/abstracts/_variables.scss`, for example:

```scss
$primary-color: #2a9d8f;
$font-size-base: 1rem;
$border-radius: 8px;
```

Then rebuild using:

```bash
npm run build
```

---

## 📂 Project Structure

- `scss/` – Sass source
  - `abstracts/` – variables
  - `base/` – resets
  - `components/` – buttons, forms, tables
  - `utilities/` – spacing, borders, text
- `dist/` – compiled CSS
- `index.html` – usage demo

---

## 👥 Authors

Team: Your Names Here  
Instructor: [Your Instructor Name]
