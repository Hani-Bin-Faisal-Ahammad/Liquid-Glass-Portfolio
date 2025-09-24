Hani's Digital Portfolio - An iOS 26 "Liquid Glass" Concept
Welcome to the repository for my personal portfolio, a forward-thinking project designed to be more than just a website—it's an immersive digital experience. The concept reimagines the personal portfolio as a custom version of a futuristic iOS, built with a sophisticated "liquid glass" UI that emphasizes depth, light, and interactivity.View the Live DemoScreenshotsThe portfolio features a fully adaptive design that offers a unique experience on both desktop and mobile.Desktop View (Dark & Light)Mobile View (Dark & Light)Core Concept: Your Work, In Its ElementThe guiding principle of this project was to create a canvas that doesn't just show work, but brings it to life. Traditional portfolios often feel static. This one aims to feel like a personal operating system, where the visitor can interact with your journey and skills in a fluid, intuitive way.The design language is inspired by a speculative iOS 26, using translucent, layered materials (Aura Glass) to create a sense of space and focus.Key FeaturesSophisticated Liquid Glass UI: Built with a custom "Aura Glass" effect that uses backdrop-filter to create a beautiful, translucent, and layered appearance on all interactive elements.Fully Responsive, Dual-Layout Design:On Mobile: The portfolio is presented within a simulated iPhone shell for an authentic, native-app feel.On Desktop: The shell disappears, and the content reflows into a spacious, professional layout that takes full advantage of the screen real estate.System-Aware Light & Dark Mode: Seamlessly switches between a crisp, premium light theme and a sleek, modern dark theme. It respects the user's OS preference by default but can also be toggled manually.Interactive Modals: Key sections like "About Me" and "Hobbies" are accessible through tiles that expand into beautifully animated modals, keeping the main interface clean and focused."My Journey" Timeline: A clean, elegant timeline that visually represents your academic and professional milestones, with years neatly aligned for readability.3D Perspective Cards: Project cards that react to the user's cursor, tilting in 3D space to create an engaging, tactile experience.Single-File Architecture: The entire application—HTML, CSS, and JavaScript—is contained within a single index.html file for ultimate portability and simplicity.Tech StackThis project was built from the ground up with a focus on modern, lightweight web technologies.HTML5: For the core structure and content.Tailwind CSS: For a utility-first approach to styling, enabling rapid and responsive design.Vanilla JavaScript: For all interactivity, including the theme switcher, modal logic, and 3D card effects. No frameworks needed.Google Fonts: Using the "Inter" font family for a clean, modern, and highly readable UI, consistent with Apple's design language.Getting StartedBecause this is a pure front-end project with no build dependencies, running it locally is incredibly simple.Clone the repository:git clone [https://github.com/Hani-Bin-Faisal-Ahammad/Liquid-Glass-Portfolio.git](https://github.com/Hani-Bin-Faisal-Ahammad/Liquid-Glass-Portfolio.git)
Navigate to the directory:cd your-repo-name
Open the file:Simply open the index.html file in your web browser. For the best experience (to avoid any potential browser CORS issues with local files), it's recommended to use a simple local server. If you have VS Code, the Live Server extension is a great option.Customization GuideThis portfolio is designed to be easily customized. All content is located directly in the index.html file.1. Profile InformationProfile Picture: Replace the src in the <img> tag within the hero section and the "About Me" modal.<!-- Hero Section Image -->
<img src="[https://hanibinfaisalahammad.vercel.app/profile.jpeg](https://hanibinfaisalahammad.vercel.app/profile.jpeg)" ...>
Name & Title: Edit the <h1> and <p> tags in the hero section.<h1 class="text-3xl ...">Hani Bin Faisal</h1>
<p class="text-md ...">Software Developer</p>
About Me Text: Find the "About Me" modal (id="about-modal") and edit the final <p> tag.2. "My Journey" TimelineEach entry is a div with the class timeline-item. To add, edit, or remove an entry, modify these blocks within the <section id="storyline">.<div class="timeline-item ...">
    <div class="absolute ...">2024</div> <!-- Year -->
    <h3 class="font-bold ...">Higher Secondary</h3> <!-- Title -->
    <p class="text-sm ...">Indian School Bahrain (CBSE)</p> <!-- Subtitle -->
</div>
3. Projects ("Perspective")Each project is an <a> tag with the class project-card. Update the href to link to your project and change the <h4> and <p> for the name and description. The image is a placeholder from placehold.co—replace it with your own project thumbnail.<a href="[https://your-project-link.com](https://your-project-link.com)" target="_blank" class="project-card ...">
    <img src="path/to/your/project-image.png" ...>
    <h4 ...>Your Project Name</h4>
    <p ...>Tech Stack</p>
</a>
4. Hobbies, Achievements & SkillsThese sections are clearly marked. You can edit the text directly. For hobbies, the "Top 10" lists are inside their respective modals (id="anime-modal", etc.).<!-- Example for a skill -->
<div class="glass-pane ..."><p>Python</p></div>

<!-- Example for a hobby list item -->
<li>Attack on Titan</li>
5. Resume/CVFind the "Resume" section (id="resume"). To link your resume, replace the href="#" in the download button with a direct link to your PDF file.<a href="path/to/your/resume.pdf" download="Hani_Bin_Faisal_Resume.pdf" ...>
    Download CV
</a>
6. Social & Contact LinksDock Icons: Update the href for each <a> tag inside the dock div.<a href="[https://github.com/hanibinfaisal](https://github.com/hanibinfaisal)" ...>
    <!-- GitHub SVG Icon -->
</a>
"Get in Touch" Button: Update the mailto: link with your email address.<a href="mailto:your-email@gmail.com" ...>
    Get in Touch
</a>
