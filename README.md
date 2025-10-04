# Personal Portfolio – Haider Raza

A responsive 4-page portfolio (Home, About, Projects, Contact) built with semantic HTML5 and CSS3. No Flexbox was used (per course rules). The site showcases my background, selected projects, and a contact form with HTML5 validation.

---

## 📁 Project Structure

```
index.html
about.html
projects.html
contact.html
main.css       # global theme, typography, gradients
mobile.css     # ≤ 600px
tablet.css     # 601–1024px
laptop.css     # 1025–1366px
Image.jpg
poster.jpg
Video.mp4
```

---

## ✅ Features
- Semantic HTML structure using <header>, <nav>, <main>, <section>, <article>, <footer>
- About page: profile image and intro video (45–60s) with poster
- Projects page: 5 projects with 2–3 sentence descriptions
- Contact form: validation on name, email, phone (10-digit), comments
- Footer with email + copyright
- Fully responsive across mobile, tablet, and laptop

---

## 🎨 GUI / Interface

### a) Responsiveness
- **≤ 600px (phones):** Chosen because most phones are ~600px wide, ensuring compatibility with the majority of devices.
- **601–1024px (tablets):** Fits common tablet resolutions in both portrait and landscape.
- **1025–1366px (laptops):** Matches the most common laptop screen sizes, ensuring readable layouts without wasted space.

Separate CSS files are used for each viewport (`mobile.css`, `tablet.css`, `laptop.css`) to adjust typography, navigation layout, and content width.

### b) Gradients
- **Header gradient:** green blend applied to all headers for consistency  
  - `#56ab2f → #a8e063`
- **Footer gradient:** blue blend applied to all footers  
  - `#2193b0 → #6dd5ed`
- These gradients were chosen from Adobe Color and applied across all 4 pages to maintain a unified look and feel.

### c) Color Scheme
The palette was generated with Adobe Color and includes:
- Header gradient: `#56ab2f → #a8e063`
- Footer gradient: `#2193b0 → #6dd5ed`
- Supporting text/background colors defined as CSS variables in `:root` inside `main.css`.

---

## 🧪 Validation & Testing
- **HTML:** W3C Markup Validation Service
- **CSS:** W3C CSS Validation Service
- **Links:** W3C Link Checker
- **Spelling:** Editor spell-check
- **Accessibility:** WAVE tool (checked alt text, contrast, and form labels)

---

## 🚀 Deployment
- Hosted on **GitHub Pages** for version control and live demo.
- To view locally, open `index.html` in any modern browser.

---

## 📄 Credits / Notes
- All HTML/CSS authored by Haider Raza.
- No external CSS frameworks or Flexbox used (per course requirement).
- Gradients and color variables implemented with standard CSS custom properties.
