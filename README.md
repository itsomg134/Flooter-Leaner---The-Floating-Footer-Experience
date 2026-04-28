#  Flooter Leaner — The Floating Footer Experience

**Flooter Leaner** is a modern, minimalist UI component & webpage template that redefines the traditional website footer. Instead of a standard static footer that sits at the bottom of the document flow, **Flooter Leaner** uses a sleek **fixed-position glassmorphism bar** that stays accessible at all times — floating gracefully above your content.

> *“A footer that floats, stays lean, and never interrupts.”*

![Preview Placeholder](https://via.placeholder.com/800x400?text=Flooter+Leaner+Demo)

---

## Concept

The name **Flooter Leaner** combines:

- **Flooter** = Floating + Footer  
- **Leaner** = Minimal footprint, clean design, no bloat

It sits at the bottom edge of the viewport with rounded corners, backdrop blur, and adaptive responsiveness. Whether you're building a portfolio, a SaaS landing page, a blog, or an admin dashboard — this pattern keeps essential links and branding always one scroll away, without eating screen real estate.

---

##  Key Features

| Feature               | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
|  **Truly Floating**  | Fixed-position footer with `bottom` / `left` / `right` offsets — never overlaps content awkwardly |
|  **Glassmorphism**   | `backdrop-filter: blur()` + translucent background for modern aesthetic     |
|  **Fully Responsive**| Stacks vertically on mobile, touch-friendly, stays within thumb reach      |
|  **Ultra-lightweight** | Pure CSS + minimal optional JS (no frameworks, no heavy dependencies)    |
|  **Customizable**    | Easy to tweak colors, blur intensity, border radius, link styles           |
|  **Lean by Default** | Only essential links, brand mark, and copy — no unnecessary fluff          |
|  **Interactive**     | Hover effects, optional toggle button to demonstrate "leaner" mode         |

---

##  Live Demo

You can copy the full HTML/CSS code into any `.html` file and open it in your browser. The demo includes:

- Hero section with tagline  
- Feature cards explaining the concept  
- Scrollable content area to see the footer always in place  
- "Lean Mode" toggle button that dynamically compacts the footer style  

---

##  How to Use

### 1. Quick Start (Standalone HTML)

Copy the complete HTML code from the [`index.html`](#) (or from the demo above) into a new file, save as `index.html`, and open it in any modern browser.

```bash
# Example
$ git clone https://github.com/yourname/flooter-leaner.git
$ cd flooter-leaner
$ open index.html
```

### 2. Extract Only the Footer Component

If you only want the **flooter** itself, copy the `<footer class="flooter-leaner">` block and its associated CSS rules (from the `<style>` section). Minimum required CSS:

```css
.flooter-leaner {
    position: fixed;
    bottom: 1.2rem;
    left: 1.2rem;
    right: 1.2rem;
    background: rgba(18, 28, 35, 0.85);
    backdrop-filter: blur(12px);
    border-radius: 2rem;
    /* ... other styles from the example */
}
```

Make sure your `<body>` has `padding-bottom` to avoid content being hidden behind the fixed footer:

```css
body {
    padding-bottom: 5rem;
}
```

### 3. Customization Tips

- **Change colors**: Edit the `background` property of `.flooter-leaner` and link `color`.
- **Adjust blur intensity**: Modify `backdrop-filter: blur(…)`.
- **Control spacing**: Tweak `bottom`, `left`, `right`, and `padding`.
- **Responsive breakpoint**: The media query at `max-width: 680px` optimizes for small screens.
- **Replace links**: Update the `.footer-links` `<a>` tags with your own URLs.

---

##  Project Structure (Single File)

Since **Flooter Leaner** is delivered as a single, self-contained HTML document, there's no complex build step:

```
flooter-leaner/
├── index.html          # Complete demo with styles, structure, and optional JS
└── README.md           # This file
```

---

##  Philosophy & Design Notes

- **Accessibility first**: The footer uses semantic HTML and sufficient color contrast.
- **Non-intrusive**: Even though it’s fixed, the footer doesn’t block main actions or content thanks to generous body padding and floating margins.
- **Performance**: No external libraries, minimal reflows, smooth animation.
- **“Lean Mode” concept**: The included JavaScript toggles an even more compact style, showing how adaptable the pattern is.

---

##  Visual Highlights

- Rounded floating card appearance (border-radius: 2rem)
- Translucent background that adapts to scrolling content
- Soft shadow + subtle border for depth
- Hover transitions on links and buttons

---

##  Browser Support

| Chrome | Firefox | Safari | Edge |
|--------|---------|--------|------|
|  latest |  latest |  latest |  latest |

*`backdrop-filter` is supported in all modern browsers. For older browsers, the footer gracefully degrades to a solid semi-transparent background.*

---

##  License

MIT — Use it freely in personal and commercial projects. Attribution is appreciated but not required.

---

##  Contributing

Since this is a minimalist pattern, feel free to fork and create your own variants. If you find a bug or have an idea to make it even **leaner**, open an issue or pull request.

---

##  Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)

Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)

Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)

LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)

Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)
