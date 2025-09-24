# Hani's Digital Portfolio - An iOS 26 "Liquid Glass" Concept  

Welcome to the repository for my personal portfolio, a forward-thinking project designed to be more than just a website—it's an **immersive digital experience**.  

This portfolio reimagines the personal showcase as a **futuristic iOS concept**, featuring a sophisticated "liquid glass" UI that emphasizes **depth, light, and interactivity**.  

🌐 **[View Live Demo](https://hanibinfaisalahammad2025.vercel.app/)**  

---

## 📸 Screenshots  

### Desktop View (Light & Dark)  
*(Add screenshots here)*  

### Mobile View (Light & Dark)  
*(Add screenshots here)*  

---

## 💡 Core Concept: *Your Work, In Its Element*  

The guiding principle of this project was to create a canvas that doesn’t just *show* work, but **brings it to life**.  

Traditional portfolios often feel static. This one aims to feel like a **personal operating system**, where the visitor can interact with your journey and skills in a **fluid, intuitive way**.  

The design language is inspired by a **speculative iOS 26**, using translucent, layered materials (*Aura Glass*) to create a sense of space and focus.  

---

## ✨ Key Features  

- **Sophisticated Liquid Glass UI**  
  Built with a custom *Aura Glass* effect using `backdrop-filter` for a translucent, layered appearance.  

- **Fully Responsive, Dual-Layout Design**  
  - 📱 **Mobile**: Presented inside a simulated iPhone shell for an authentic native-app feel.  
  - 💻 **Desktop**: Content reflows into a spacious professional layout.  

- **System-Aware Light & Dark Mode**  
  Automatically adapts to the user’s OS preference, with a manual toggle option.  

- **Interactive Modals**  
  Clean, animated modals for *About Me*, *Hobbies*, and more.  

- **“My Journey” Timeline**  
  Academic and professional milestones displayed in a clear, elegant timeline.  

- **3D Perspective Cards**  
  Projects tilt and react to cursor movement for an engaging, tactile experience.  

- **Single-File Architecture**  
  All HTML, CSS, and JavaScript live inside one `index.html` for ultimate portability.  

---

## 🛠️ Tech Stack  

- **HTML5** → Structure and content  
- **Tailwind CSS** → Utility-first styling for rapid, responsive design  
- **Vanilla JavaScript** → Interactivity (theme switcher, modals, 3D effects)  
- **Google Fonts** → *Inter* for modern, Apple-inspired typography  

---

## ⚡ Getting Started  

This project is 100% front-end. No build dependencies.  

```bash
# Clone the repository
git clone https://github.com/Hani-Bin-Faisal-Ahammad/Liquid-Glass-Portfolio.git

# Navigate into the directory
cd Liquid-Glass-Portfolio

# Open index.html in your browser
# (Recommended: use VS Code + Live Server extension)

```
---
## 🖌️ Customization Guide

All content is inside index.html for quick edits.
---
1. Profile Information

* Profile Picture: Replace the src in the `<img>` tag in the hero and About Me modal.

* Name & Title: Update the `<h1>` and `<p>` tags in the hero section.

* About Me Text: Edit the `<p>` inside the `#about-modal`.
---
2. "My Journey" Timeline

Each milestone is a `.timeline-item`. Edit year, title, and description.
```bash
<div class="timeline-item">
  <div class="absolute">2024</div>
  <h3 class="font-bold">Higher Secondary</h3>
  <p class="text-sm">Indian School Bahrain (CBSE)</p>
</div>
```
---
3. Projects

Each project is a `.project-card`. Replace with your own links, images, and descriptions.
```
<a href="https://your-project-link.com" target="_blank" class="project-card">
  <img src="assets/project1.png" alt="Project Thumbnail">
  <h4>My Project</h4>
  <p>Tech Stack</p>
</a>
```
---
4. Hobbies, Achievements & Skills

* Skills: Edit `<div class="glass-pane">Python</div>`

* Hobbies: Edit the `<li>` elements in their respective modals.
---
5. Resume / CV

Place your resume PDF in `assets/resume.pdf.`

```
<a href="assets/resume.pdf" download="Hani_Bin_Faisal_Resume.pdf">
  Download CV
</a>
```
---
6. Social & Contact Links

Update the dock icons and `mailto:` link.
```
<a href="https://github.com/Hani-Bin-Faisal-Ahammad" target="_blank">GitHub</a>
<a href="mailto:your-email@gmail.com">Get in Touch</a>

```
---
## 📂 Folder Structure
```
Liquid-Glass-Portfolio/
│
├── index.html        # Main file (HTML + CSS + JS)
├── assets/           # Images, resume, and other static files
│   ├── profile.jpeg
│   ├── resume.pdf
│   └── project1.png
└── README.md
```
---
## 📜 License

This project is open-source and free to use. If you use it, consider giving credit.
---
## 🚀 Built with creativity, code, and a touch of futuristic design by Hani Bin Faisal Ahammad
