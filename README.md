# 🎮 Pixel Bit

> Retro pixel-art UI component library inspired by classic 8-bit and 16-bit games

[![npm version](https://img.shields.io/npm/v/pixel-bit)](https://www.npmjs.com/package/pixel-bit)
[![npm downloads](https://img.shields.io/npm/dm/pixel-bit)](https://www.npmjs.com/package/pixel-bit)
[![license](https://img.shields.io/npm/l/pixel-bit)](https://github.com/tu-usuario/pixel-bit/blob/main/LICENSE)

Bring the nostalgic feel of Game Boy, NES, and classic RPGs to your web projects with **Pixel Bit** – a lightweight CSS library featuring pixel-perfect components with retro gaming aesthetics.

---

## ✨ Features

- 🎨 **Authentic pixel-art styling** inspired by classic games
- 🎮 **Game Boy Color palette** with fire, water, electric, grass themes
- ⚡ **Lightweight** – Pure CSS, no JavaScript required
- 📦 **Easy to use** – Just add classes
- 🔧 **Customizable** – Multiple variants and sizes
- 🌐 **Framework agnostic** – Works with React, Vue, vanilla HTML, etc.
- ♿ **Accessible** – Semantic HTML compatible

---

## 📦 Installation

### Via NPM

```bash
npm install pixel-bit
```

```javascript
import "pixel-bit/dist/pixel-bit.css";
```

### Via CDN

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/pixel-bit@latest/dist/pixel-bit.css"
/>
```

---

## 🚀 Quick Start

```html
<!DOCTYPE html>
<html>
  <head>
    <link
      rel="stylesheet"
      href="https://unpkg.com/pixel-bit@latest/dist/pixel-bit.css"
    />
  </head>
  <body>
    <!-- Buttons -->
    <button class="pb-btn pb-fire pb-btn-lg">Fire Attack</button>
    <button class="pb-btn pb-water pb-btn-md">Water Splash</button>
    <button class="pb-btn pb-electric pb-btn-sm">Thunder Bolt</button>

    <!-- Input -->
    <input type="text" class="pb-input pb-grass" placeholder="Enter text..." />

    <!-- Progress Bar -->
    <div class="pb-bar hp-bar">
      <div class="pb-bar-fill" style="width: 75%;"></div>
    </div>
  </body>
</html>
```

---

## 📚 Components

### Buttons

Classic pixel-art buttons with multiple themes and sizes.

```html
<!-- Themes -->
<button class="pb-btn pb-fire">Fire</button>
<button class="pb-btn pb-water">Water</button>
<button class="pb-btn pb-electric">Electric</button>
<button class="pb-btn pb-grass">Grass</button>
<button class="pb-btn pb-ghost">Ghost</button>

<!-- Sizes -->
<button class="pb-btn pb-fire pb-btn-sm">Small</button>
<button class="pb-btn pb-water pb-btn-md">Medium</button>
<button class="pb-btn pb-electric pb-btn-lg">Large</button>

<!-- States -->
<button class="pb-btn pb-grass" disabled>Disabled</button>
```

### Input Fields

Retro-styled text inputs with Game Boy aesthetics.

```html
<input type="text" class="pb-input pb-fire" placeholder="Player name..." />
<input type="email" class="pb-input pb-water pb-input-lg" />
```

### Progress Bars

HP, MP, XP bars with smooth animations.

```html
<!-- HP Bar -->
<div class="pb-bar hp-bar">
  <div class="pb-bar-fill" style="width: 60%;"></div>
</div>

<!-- MP Bar -->
<div class="pb-bar mp-bar">
  <div class="pb-bar-fill" style="width: 80%;"></div>
</div>

<!-- XP Bar -->
<div class="pb-bar xp-bar">
  <div class="pb-bar-fill" style="width: 45%;"></div>
</div>

<!-- Loading Bar -->
<div class="pb-bar loading-bar">
  <div class="pb-bar-fill" style="width: 100%;"></div>
</div>
```

### Select Dropdowns

```html
<select class="pb-select pb-electric">
  <option>Pikachu</option>
  <option>Raichu</option>
  <option>Voltorb</option>
</select>
```

### Textareas

```html
<textarea
  class="pb-textarea pb-grass"
  placeholder="Write your message..."
></textarea>
```

### Radio Buttons

```html
<label class="pb-radio pb-radio-fire">
  <input type="radio" name="starter" />
  <span>Charmander</span>
</label>

<label class="pb-radio pb-radio-water">
  <input type="radio" name="starter" />
  <span>Squirtle</span>
</label>
```

### Toggle Switches

```html
<label class="pb-toggle pb-toggle-electric">
  <input type="checkbox" />
  <span class="slider"></span>
</label>
```

### Range Sliders

```html
<input
  type="range"
  class="range-slider range-fire"
  min="0"
  max="100"
  value="50"
/>
```

### File Upload

```html
<label class="file-upload file-water">
  Choose File
  <input type="file" />
</label>
```

---

## 🎨 Available Themes

- `pb-fire` – Red/orange (🔥)
- `pb-water` – Blue (💧)
- `pb-electric` – Yellow (⚡)
- `pb-grass` – Green (🌿)
- `pb-ghost` – Purple (👻)

---

## 📏 Available Sizes

- `pb-btn-sm` / `pb-input-sm` – Small
- `pb-btn-md` / `pb-input-md` – Medium (default)
- `pb-btn-lg` / `pb-input-lg` – Large

---

## 🎯 Use Cases

Perfect for:

- 🎮 Retro game websites
- 💼 Gaming portfolios
- 🕹️ HTML5 game UIs
- 📱 Nostalgic web apps
- 🎨 Pixel-art themed projects
- 🏆 Game jam projects

---

## 🌐 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

---

## 📖 Documentation

For detailed documentation and live examples, visit:
[GitHub Repository](https://github.com/tu-usuario/pixel-bit)

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new components
- Submit pull requests

---

## 📄 License

MIT © 

---

## 🎮 Inspired By

Classic games: Pokémon, Final Fantasy, Dragon Quest, and the golden era of 8-bit and 16-bit gaming.

---

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

---

**Made with ❤️ for retro gaming lovers**
