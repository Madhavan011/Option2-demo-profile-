# Option2-demo-profile-
Written Project Report: Website Demonstration
📌 Project Title: Responsive Portfolio Website

👤 Student Name: Madhavan

🔹 1. Project Overview
This project is a personal portfolio website designed to showcase my work and skills. The site includes the following pages:

Landing Page with hero section and call-to-action

About Me section with a short bio

Gallery with a JavaScript-enhanced image grid

Contact Page with a form

Navigation bar with accessibility enhancements

The goal of the site is to create a clean, responsive, and accessible user experience that works well across devices and screen sizes.

🔹 2. Site Hosting (if available)
Hosted link: https://your-username.github.io/portfolio
(Replace with your actual link if hosted)

🔹 3. W3 Validator Compliance ✅
All HTML pages were tested using the W3C Validator. No errors were found.

Evidence:

Screenshot of validated home page: ✅

Screenshot of validated contact form page: ✅

(Attach your screenshots or add them to the end of the document)

🔹 4. Responsive Design 📱💻
The site uses mobile-first CSS with media queries. It adapts smoothly across:

Mobile devices (360px and up)

Tablets

Desktops (up to 1440px)

Evidence:

Screenshot: mobile view of the landing page

Screenshot: tablet view of the gallery

Screenshot: desktop view of contact page

(Attach screenshots or demonstrate via video)

🔹 5. Well-Styled with CSS 🎨
CSS features used:

flexbox and grid for layout

:focus, :hover states for accessibility and interactivity

@media for responsive breakpoints

Consistent margin/padding and hierarchy using rem and em units

Clean color scheme and spacing (no inline styles)

Sample CSS Snippet:

css
Copy code
nav ul {
  display: flex;
  justify-content: space-around;
  list-style: none;
}

@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }
}
🔹 6. My 4 Extras 🌟
Skip to Main Content Link
A visually hidden but keyboard-accessible skip link is included for screen readers and keyboard users.

html
Copy code
<a href="#main" class="skip-link">Skip to Main Content</a>
Interactive Gallery
Gallery items can be clicked to expand using JavaScript.

javascript
Copy code
document.querySelectorAll('.gallery img').forEach(img => {
  img.addEventListener('click', () => {
    img.classList.toggle('expanded');
  });
});
Keyboard Navigation (tabindex)
All interactive elements (nav links, form fields, gallery) include tabindex and aria-label where needed.

HTML5 Contact Form with Validation
Built-in input validation with required fields and input types.

html
Copy code
<input type="email" required placeholder="Your email">
📎 Attachments to Upload
This PDF write-up

Screenshots of:

W3 Validator success results

Responsive layout on multiple screens

CSS file (optional)

Project link (if hosted)

Now, I’ll generate this report as a downloadable PDF for you.

Your Website Project Report PDF is ready for download:

📄 Click here to download Website_Project_Report_Madhavan.pdf

You can upload this PDF along with:

Screenshots (for validator + responsiveness)

A link to your hosted site (if available)

CSS files or extras code (if required)

Let me know if you want a version that includes those screenshots or help with the video version too. 







