# Building a Web Presentation with Reveal.js  

**Warsaw Management University**  
**Student:** Enver Gidici  
**Student ID:** 77797  

> An overview of creating modern web presentations using Reveal.js, Quarto documentation, and deployment via GitHub Pages.

![Reveal.js logo](https://revealjs.com/images/logo/reveal-symbol.svg)

---

## Agenda

1. Assignment description & objectives  
2. What is Reveal.js?  
3. Installation & basic setup  
4. Authoring slides with Markdown  
5. Quarto & Reveal.js integration  
6. Publishing on GitHub Pages  
7. Summary & references  

---

## 1. Assignment Overview

**Goal**

- Use **Reveal.js** to build an online presentation  
- Base the content on the following sources:
  - Reveal.js installation guide  
  - Quarto Reveal.js presentations documentation  
  - Reveal.js demo presentation  

**Requirements**

- At least **5 slides**  
- **Non-default theme** (e.g. `moon`, `solarized`)  
- Use **Markdown** for content  
- Include **horizontal and vertical navigation**  
- Publish via **GitHub Pages** and provide:
  - Public URL  
  - Source links  
  - Screenshots of the presentation  

---

## 2. What is Reveal.js?

- A **HTML-based presentation framework**  
- Presentations run directly in the **web browser**  
- Slides are created using:
  - Standard HTML  
  - Or **Markdown**, which is easier and cleaner  

---

--  

### Key Features of Reveal.js

- Horizontal and vertical slide navigation  
- Multiple built-in **themes** and transitions  
- Support for:
  - Markdown  
  - Speaker notes  
  - Code highlighting  
  - Plugins and extensions  

> This makes Reveal.js well suited for technical and academic presentations.

---

## 3. Installation & Basic Setup

From the official **installation guide**:

- **Option 1 – Basic download**
  - Download the latest release as a ZIP file  
  - Extract the folder  
  - Edit `index.html` and add your slides  
  - Open the file in a browser  

- **Option 2 – Node.js workflow**
  - Clone the repository  
  - Run `npm install`  
  - Use `npm start` for a local development server  

---

--  

### Minimal HTML Structure

A simple Reveal.js page contains:

```html
<div class="reveal">
  <div class="slides">
    <section>First slide</section>
    <section>Second slide</section>
  </div>
</div>
