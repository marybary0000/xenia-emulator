╔═══════════════════════════════════════════════════════════════════════════╗
║                     XENIA CANARY WEBSITE - README                         ║
║                   Professional Multi-Page Website                         ║
╚═══════════════════════════════════════════════════════════════════════════╝

📋 TABLE OF CONTENTS
═══════════════════
1. Introduction
2. File Structure
3. How to Run the Website
4. How to Edit the Website
5. Color Scheme
6. SEO Keywords
7. Features
8. Browser Compatibility
9. Customization Guide
10. Troubleshooting
11. Support & Contact

═══════════════════════════════════════════════════════════════════════════

1. INTRODUCTION
═══════════════
This is a professional, responsive, multi-page website for Xenia Canary - 
an Xbox 360 emulator. The website is built using HTML5, CSS3, and JavaScript
with modern design principles, SEO optimization, and mobile responsiveness.

═══════════════════════════════════════════════════════════════════════════

2. FILE STRUCTURE
════════════════
xeniacanary3/
│
├── index.html          → Home page (SEO optimized with focus keywords)
├── about.html          → About page (Mission, Vision, About Us)
├── contact.html        → Contact page (Google Form integration)
├── download.html       → Download page (Styled download button)
├── style.css           → Main stylesheet (All styling)
├── script.js           → JavaScript (Interactivity & animations)
└── README.txt          → This file (Instructions)

═══════════════════════════════════════════════════════════════════════════

3. HOW TO RUN THE WEBSITE
═════════════════════════

Option 1: OPEN LOCALLY
----------------------
1. Navigate to the folder: D:\xeniacanary3
2. Double-click on "index.html" to open in your default browser
3. The website will load and you can navigate between pages

Option 2: LOCAL SERVER (Recommended for development)
---------------------------------------------------
If you have Python installed:

1. Open Command Prompt/Terminal
2. Navigate to the folder:
   cd D:\xeniacanary3

3. Run a local server:
   Python 3: python -m http.server 8000
   Python 2: python -m SimpleHTTPServer 8000

4. Open browser and visit: http://localhost:8000

Option 3: UPLOAD TO WEB HOSTING
-------------------------------
1. Upload all files to your web hosting via FTP/cPanel
2. Ensure index.html is in the root directory
3. Access your website via your domain name

═══════════════════════════════════════════════════════════════════════════

4. HOW TO EDIT THE WEBSITE
═══════════════════════════

EDITING CONTENT (HTML Files)
----------------------------
1. Open any HTML file (index.html, about.html, etc.) in a text editor
   Recommended editors: VS Code, Sublime Text, Notepad++

2. Find the section you want to edit
   - Content is organized in <section> tags
   - Headings use <h1>, <h2>, <h3> tags
   - Paragraphs use <p> tags

3. Make your changes and save the file

4. Refresh your browser to see the changes

EDITING STYLES (CSS)
-------------------
1. Open "style.css" in a text editor

2. Color variables are defined at the top:
   --primary-color: #004AAC
   --secondary-color: #BDD0EA
   --accent-color: #0066FF

3. To change colors, modify these values

4. To change fonts, find "font-family" properties

5. Save and refresh browser to see changes

EDITING JAVASCRIPT (Interactivity)
---------------------------------
1. Open "script.js" in a text editor

2. The file contains:
   - Mobile menu toggle
   - Smooth scrolling
   - Animation effects
   - Parallax effects

3. Edit carefully as JavaScript errors can break functionality

4. Save and refresh browser

═══════════════════════════════════════════════════════════════════════════

5. COLOR SCHEME
═══════════════

Primary Color:   #004AAC (Dark Blue)    - Headers, buttons, links
Secondary Color: #BDD0EA (Light Blue)   - Accents, backgrounds
Accent Color:    #0066FF (Bright Blue)  - Call-to-action buttons
Background:      #FFFFFF (White)        - Main background
Text Color:      #333333 (Dark Gray)    - Body text
Light Text:      #666666 (Gray)         - Secondary text
Footer:          #001f4d (Dark Blue)    - Footer background

═══════════════════════════════════════════════════════════════════════════

6. SEO KEYWORDS
═══════════════

Focus Keywords (Used throughout the site):
------------------------------------------
✓ xenia canary
✓ xenia emulator
✓ xenia canary latest version
✓ xenia canary game compatibility list
✓ xenia emulator download

These keywords are strategically placed in:
- Page titles
- Meta descriptions
- Headings (H1, H2, H3)
- Content paragraphs
- Alt text for images

═══════════════════════════════════════════════════════════════════════════

7. FEATURES
═══════════

✓ Responsive Design        - Works on desktop, tablet, and mobile
✓ Modern UI/UX            - Clean, professional design
✓ SEO Optimized           - Meta tags, keywords, semantic HTML
✓ Fast Loading            - Optimized CSS and JavaScript
✓ Mobile Menu             - Hamburger menu for mobile devices
✓ Smooth Animations       - Fade-in effects and transitions
✓ Hover Effects           - Interactive buttons and cards
✓ Cross-browser Support   - Works on all modern browsers
✓ Accessibility           - Semantic HTML, ARIA labels
✓ Google Form Integration - Contact form via Google Forms

═══════════════════════════════════════════════════════════════════════════

8. BROWSER COMPATIBILITY
════════════════════════

Fully Compatible:
✓ Google Chrome (Latest)
✓ Mozilla Firefox (Latest)
✓ Microsoft Edge (Latest)
✓ Safari (Latest)
✓ Opera (Latest)

Mobile Browsers:
✓ Chrome Mobile
✓ Safari iOS
✓ Samsung Internet
✓ Firefox Mobile

Minimum Requirements:
- Modern browser with CSS Grid support
- JavaScript enabled
- Screen resolution: 320px or higher

═══════════════════════════════════════════════════════════════════════════

9. CUSTOMIZATION GUIDE
══════════════════════

CHANGE WEBSITE COLORS
---------------------
1. Open "style.css"
2. Find the ":root" section at the top
3. Change color values:
   --primary-color: #YOUR_COLOR;
   --secondary-color: #YOUR_COLOR;
4. Save and refresh

CHANGE LOGO TEXT
---------------
1. Open any HTML file
2. Find: <a href="index.html" class="logo">Xenia Canary</a>
3. Replace "Xenia Canary" with your text
4. Repeat for all HTML files
5. Save and refresh

ADD NEW PAGES
------------
1. Copy any existing HTML file (e.g., about.html)
2. Rename it (e.g., newpage.html)
3. Edit the content
4. Add link in navigation:
   <li><a href="newpage.html">New Page</a></li>
5. Add the same link to all other pages
6. Save all files

CHANGE LINKS
-----------
Find these links in the HTML files and update as needed:

Official Site:
https://xeniacanary.org/

GitHub:
https://github.com/xeniacanaryhub

Download Page:
https://xeniacanary.org/downloads/

Contact Form:
https://docs.google.com/forms/d/e/1FAIpQLSeQ1peOAUw7VAcqiYNlE6hgaQxBsk_ZkeOc9iX7oxP4PygZ-A/viewform?usp=header

CHANGE FONTS
-----------
1. Open "style.css"
2. Find "font-family" in the body section
3. Change to your preferred font:
   font-family: 'Your Font', sans-serif;
4. For Google Fonts, add in HTML <head>:
   <link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">

═══════════════════════════════════════════════════════════════════════════

10. TROUBLESHOOTING
═══════════════════

Problem: Pages don't link properly
Solution: Ensure all HTML files are in the same folder

Problem: CSS styles not showing
Solution: Check that style.css is in the same folder as HTML files

Problem: JavaScript not working
Solution: Check that script.js is in the same folder
         Check browser console (F12) for errors

Problem: Mobile menu not working
Solution: Ensure JavaScript is enabled in browser
         Check that script.js is properly linked

Problem: Images not showing
Solution: Verify image paths are correct
         Ensure images are in the correct folder

Problem: Forms not submitting
Solution: Check Google Form link is correct
         Ensure form link is not expired

═══════════════════════════════════════════════════════════════════════════

11. SUPPORT & CONTACT
════════════════════

For questions or support:

Official Website: https://xeniacanary.org/
GitHub: https://github.com/xeniacanaryhub
Contact Form: Use the contact page on the website

Website Developer Notes:
- Built with HTML5, CSS3, JavaScript
- No external frameworks required
- All files are standalone and portable
- Works offline (except external links)
- Optimized for performance and SEO

═══════════════════════════════════════════════════════════════════════════

📝 QUICK REFERENCE
═════════════════

Main Files:
- index.html     = Home page
- about.html     = About page  
- contact.html   = Contact page
- download.html  = Download page
- style.css      = All styles
- script.js      = All scripts

Key Sections to Edit:
- Navigation: Lines with <nav> tag
- Hero Section: Lines with class="hero"
- Content: Lines with class="section"
- Footer: Lines with <footer> tag

Colors (in style.css):
- Primary: #004AAC
- Secondary: #BDD0EA
- Accent: #0066FF

═══════════════════════════════════════════════════════════════════════════

✨ TIPS FOR SUCCESS
══════════════════

1. Always backup files before editing
2. Test on multiple browsers after changes
3. Check mobile view (resize browser or use dev tools)
4. Validate HTML: https://validator.w3.org/
5. Validate CSS: https://jigsaw.w3.org/css-validator/
6. Use browser dev tools (F12) to debug issues
7. Keep files organized in one folder
8. Use descriptive file names
9. Comment your code for future reference
10. Test all links before publishing

═══════════════════════════════════════════════════════════════════════════

🎉 Thank you for using this website template!
   For more information, visit: https://xeniacanary.org/

═══════════════════════════════════════════════════════════════════════════

Last Updated: 2024
Version: 1.0
License: Open Source

═══════════════════════════════════════════════════════════════════════════
