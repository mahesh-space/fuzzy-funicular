# 🎞️ Gallery Coverflow Slider

> *A beautifully animated, interactive image gallery with a stunning coverflow card effect. Build your visual story without leaving your browser.*

---

## ✨ What is This?

**Gallery Coverflow Slider** is a modern, elegant image gallery experience inspired by Apple's iconic Coverflow interface. It brings your photos to life with:

- 🎨 **3D-like Card Animations** — images scale, rotate, and fade as they move through the gallery
- 🖼️ **Responsive Design** — works flawlessly on desktop, tablet, and mobile
- 🚀 **Smooth Autoplay** — watch your gallery loop with visual progress indicators
- ✏️ **Editable Metadata** — add titles and locations directly on each image card
- 📤 **Multiple Upload Methods** — drag-and-drop, file picker, or paste image URLs
- 🌐 **Browser-Only** — your images never leave your computer (no servers, no uploads)
- ⌨️ **Full Controls** — keyboard arrows, mouse clicks, touch swipes, and scroll wheel navigation

---

## 🎯 Features

### 🎬 Interactive Navigation
- **Arrow buttons** on either side to browse forward and backward
- **Keyboard arrows** for desktop users
- **Touch swipes** on mobile devices
- **Mouse wheel scrolling** to navigate smoothly
- **Direct card clicks** to jump to any image instantly

### 🎨 Visual Design
- Warm, elegant color palette with custom CSS variables
- Smooth cubic-bezier animations for natural motion
- Grayscale effect on non-active cards for visual hierarchy
- Gradient overlay on card captions for readability
- Responsive typography that scales with viewport

### ⏱️ Autoplay System
- Automatic slide progression with configurable duration
- Visual progress ring that fills as the timer counts down
- Play/pause toggle to control autoplay
- Auto-restart after manual navigation
- Pause on hover, resume on mouse leave

### 📝 Content Management
- Edit card titles and location text directly (click to edit)
- Remove individual slides with one click
- Upload multiple images at once
- Paste image URLs from anywhere on the web
- Visual feedback for drag-and-drop uploads

### 📱 Responsive & Accessible
- Mobile-first design approach
- Touch-friendly button sizes
- Keyboard navigation support
- ARIA labels for screen readers
- Accessible color contrast ratios

---

## 🚀 Getting Started

### No Installation Required!
Simply open `index.html` in any modern web browser. That's it!

### Adding Images

**Option 1: Upload from Computer**
1. Click **"+ Add Images"** button
2. Either drag images into the zone or click to browse
3. Select one or multiple images from your device

**Option 2: Paste Image URL**
1. Click **"+ Add Images"** button
2. Switch to the **"Paste URL"** tab
3. Paste a direct link to an image
4. Click **Add** (or press Enter)

### Customizing Your Gallery

- **Edit the title:** Click the main heading to change it
- **Edit the kicker:** Click "CURATED COLLECTION" to customize
- **Edit slide titles:** Click the image title on any card
- **Edit locations:** Click the location text on any card

---

## 💻 Technology Stack

- **HTML5** — semantic structure
- **CSS3** — modern animations, variables, and responsive design
- **Vanilla JavaScript** — no dependencies, pure functionality
- **FileReader API** — local image file processing
- **CSS Grid & Flexbox** — flexible layouts

---

## 🎭 How It Works

### The Coverflow Effect
Cards are positioned absolutely and transformed based on their offset from the center:
- **Center card**: Full size (1x scale), fully opaque, in focus
- **Adjacent cards**: Slightly smaller (0.82x), dimmed, partially visible
- **Distance cards**: Much smaller (0.68x), grayscale, barely visible

### Smart Rendering
Only 5 cards are rendered at any time (current ±2), keeping performance smooth even with hundreds of images.

### Data Persistence
All your images and metadata live in the browser's memory while the tab is open. Everything stays private and local—nothing touches the internet.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `←` Left Arrow | Previous image |
| `→` Right Arrow | Next image |
| `Scroll Wheel` | Navigate through gallery |

---

## 🎨 Customization

The gallery uses CSS variables for easy theming. Edit the `:root` section in the `<style>` tag:

```css
:root {
  --bg: #f3efe6;              /* Main background */
  --bg-warm: #f8e6cc;         /* Warm accent background */
  --ink: #201e1a;             /* Primary text */
  --accent: #dd8a3e;          /* Orange accent */
  --accent-2: #c46f28;        /* Darker orange */
  /* ...more variables... */
}
```

---

## 📦 What You Get

```
fuzzy-funicular/
└── index.html          # Everything in one file (20KB)
```

That's all! A single, self-contained HTML file with embedded CSS and JavaScript.

---

## 🌟 Use Cases

- 📸 **Portfolio galleries** — showcase your photography or design work
- 🎪 **Event albums** — present vacation photos or event highlights
- 🏢 **Product showcase** — display product images in an interactive way
- 🎓 **Presentation tool** — present visuals without leaving the browser
- 🎨 **Art collections** — curate and present artwork

---

## 🔒 Privacy First

Your images are processed locally in your browser using the FileReader API. They are never:
- Uploaded to any server
- Stored in the cloud
- Transmitted over the internet
- Logged or tracked

Everything stays on your device—your privacy is guaranteed.

---

## 🌐 Browser Support

Works on all modern browsers that support:
- CSS Grid & Flexbox
- CSS Variables
- FileReader API
- ES6 JavaScript

**Tested on:** Chrome, Firefox, Safari, Edge (latest versions)

---

## 📝 Future Ideas

Potential enhancements:
- Export gallery as a shareable HTML file
- Save/load gallery state to localStorage
- Fullscreen image viewing
- Keyboard shortcuts cheat sheet
- Gallery animation speed controls
- Image filtering/effects

---

## 👨‍💻 Made with ❤️

Created as a creative experiment in web design and animation. No frameworks, no build tools, no bloat—just pure web magic.

---

## 📄 License

Free to use, modify, and share. Do whatever you want with it!

---

**Ready to create your visual story?** Open `index.html` and start adding your images! 🎬✨
