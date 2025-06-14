# Responsive HTML/CSS Layout for Embedding in WordPress

This project showcases how to build a clean, responsive, dark-themed layout using only HTML and CSS, optimized for embedding in WordPress blogs via the HTML widget.

---

##  Objective

The goal was to create a reusable visual component that:

- Requires no JavaScript or external libraries
- Looks professional on all devices (desktop, tablet, mobile)
- Is self-hosted and embeddable via `<iframe>` into CMS platforms

---

##  Project Structure



responsive_embed_page/
* ├── index.html   # Full responsive HTML page
* ├── README.md    # You are here



---

##  Technologies Used

- HTML5 (semantic structure)
- CSS3 (Grid + Flexbox layout, animations)
- Custom styling: dark theme (`#0F1735`), hover effects, and badge components
- Responsive design with media queries
- Code blocks styled using `monospace` fonts for visual clarity

---

##  Key Features

-  Dark visual theme with gradient overlays
-  Responsive layout: multi-column on desktop, stacked on mobile
-  Modular sections: hero, phases, features, deployment grid
-  Fully iframe-compatible for WordPress and other CMS integrations
-  Lightweight: no external CSS, JS, or image assets required

## Developer Strategy

- Self-contained HTML with embedded CSS
- Easily editable structure and styling
- Organized into modular sections for reuse and clarity



##  Embed in WordPress (HTML Widget or Elementor)

1. **Host the page** on GitHub Pages or any static server  
   Example:  
   `https://your-username.github.io/responsive_embed_layout/`

2. **Paste this code into your WordPress HTML widget:**
````
html
<iframe src="https://your-username.github.io/responsive_embed_layout/"
        width="100%" height="1200" style="border:none;">
</iframe>
````

3. You can also pest the full code on the HTML Widget 


---

##  Reusability

You can adapt this layout for:

* Visual documentation and project walkthroughs
* Embed static or styled content across CMS platforms
* Build visual product sections or portfolios
* Landing pages or feature explainers
* Static HTML sections for WordPress, SharePoint, Power Pages, or Teams Tabs
* Extend layouts for info pages, changelogs, or announcements

---

##  License

Licensed under the **MIT License**,  free for commercial and non-commercial use.

---

##  Author

**Jean-Claude Munyakazi**

* [responsive_embed_layout Overview Blog](https://munyakazi.org/iso-iec-27002/)
* [Live Demo](https://jeanclaudemunyakazi.github.io/responsive_embed_layout/)
* [Author Portfolio](https://munyakazi.org)

> “Built from scratch to look good everywhere.”
