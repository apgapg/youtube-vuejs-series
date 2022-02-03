---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
drawings:
  persist: false
---

# Welcome to Github Fundamentals

DIY by Ayush P Gupta

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Topics

This series covers following topics:

- ✅ Creating Github Account
- ✅ Installing Git and Creating new Repository
- ✅ Cloning a Repository
- ⬜ Knowing Working Tree and Staging Files
- ⬜ Adding a README.md
- ⬜ Committing your work
- ⬜ Uploading new project to Github

---
# try also 'default' to start simple

theme: default

# random image from a curated Unsplash collection by Anthony

# like them? see https://unsplash.com/collections/94734566/slidev

# background: https://source.unsplash.com/collection/94734566/1920x1080

# apply any windi css classes to the current slide

class: 'text-center'

# https://sli.dev/custom/highlighters.html

highlighter: shiki

# show line numbers in code blocks

lineNumbers: false

# some information about the slides, markdown enabled

drawings:
persist: false

---

# Welcome to Github Fundamentals

### Vue(3) + Vite + Tailwindcss = ❤️

<div style="display:flex; justify-content: space-evenly;">
  <img src="data:image/png;base64,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" alt="img" height="100"/> 
  <img src="https://vitejs.dev/logo.svg" alt="img" height="150" width="150" />
  <img src="https://cdn.worldvectorlogo.com/logos/tailwind-css-1.svg" alt="img" height="100" width="200" />
</div>

**VueJs:** Website Framework

**Vite:** Bundler like Webpack

**Tailwind:** CSS Framework

---

# About Me

### Ayush P Gupta

Github: https://github.com/apgapg

Twitter: https://twitter.com/ayushpgupta

Linkedin: https://www.linkedin.com/in/ayushpgupta/