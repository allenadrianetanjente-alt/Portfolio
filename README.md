# Portfolio

Allen Adriane Tanjente — Portfolio

A single-page portfolio site for an Information Systems student, built with plain HTML/CSS/JS (no framework, no build step).

Live sections: About · Skills & Tools · Projects & Accomplishments · Contact

✨ Features
-Sticky nav that compacts on scroll, with a mobile hamburger menu.

-Animated hero with a scrolling stock-ticker strip and a duotone portrait that colorizes on hover.

-Scroll-reveal animations on each section (respects prefers-reduced-motion).

-Skills & Tools grid (Programming 💻, Business & Finance 📈, Design 🎨) with emoji-tagged skill chips.

-Project cards with animated slideshows — each project (Booking Automation, Trading, Java Programs) has a small built-in slideshow illustrating the work:
  Auto-plays as soon as the page loads.
  
  Bigger prev/next arrow buttons and larger dots for manual switching.
  
  Hover-and-hold on a picture speeds up the auto-cycle; release returns to normal pace.
  
  Frames are drawn with pure CSS/SVG — easy to swap for real screenshots (see comment in the <script> block near the slideshow logic).
  
-Working contact form — submits directly to allentanjente08@gmail.com via FormSubmit (no backend required).

-Social links — LinkedIn, GitHub, and email, styled as circular buttons in the footer.

🛠️ Tech
-HTML5 / CSS3 (CSS variables, Grid, Flexbox)
-Vanilla JavaScript (no dependencies)
-Bootstrap Icons via CDN
-Google Fonts: Space Grotesk, Inter, IBM Plex Mono
-FormSubmit for contact form delivery

No build tools, no npm install — just open portfolio.html in a browser, or deploy as a static site.

🚀 Deploying
Works on any static host. Easiest option is GitHub Pages:

1. Push this repo to GitHub.
2. Go to Settings → Pages.
3. Set the source branch to main (or master) and folder to /root.
4. Your site will be live at https://allenadrianetanjente-alt.github.io/Portfolio/

Rename portfolio.html to index.html if you want it to load at the root URL automatically.

⚠️ One-time setup: activate the contact form
The contact form uses FormSubmit to forward messages to allentanjente08@gmail.com, but FormSubmit requires a one-time confirmation:

1. Deploy or open the site and submit the contact form once (with any test message).
2. Check allentanjente08@gmail.com for an email from FormSubmit asking you to activate this form.
3. Click the confirmation link.

After that, every future submission is delivered straight to that inbox — no further setup needed.

📝 Still to personalize
  -Replace profile.jpg with a real photo (currently a placeholder path).
  -Point each project's "View project" link at the real repo, file, or live demo (currently #).
  -Swap the illustrative slideshow frames for real screenshots of each project, if you have them.

📂 Structure
portfolio.html   → the entire site (HTML + CSS + JS in one file)

📄 License
Personal portfolio — feel free to fork the structure for your own site, but please don't reuse Allen's name, photo, or project content directly.
