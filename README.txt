================================================================================
                    SCRIPTHOOKVDOTNET WEBSITE
                    Multi-Page Website Documentation
================================================================================

TABLE OF CONTENTS
-----------------
1. Introduction
2. File Structure
3. How to Run Locally
4. Customization Guide
5. Color Scheme
6. Links & URLs
7. SEO & Keywords
8. Responsive Design
9. Browser Compatibility
10. Support & Contact

================================================================================
1. INTRODUCTION
================================================================================

This is a professional, modern, responsive multi-page website built with HTML,
CSS, and JavaScript. The website is designed for ScriptHookVDotNet, a .NET
scripting platform for GTA V modding.

Features:
- Fully responsive design (mobile, tablet, desktop)
- Modern UI/UX with smooth animations
- SEO-optimized with semantic HTML
- Cross-browser compatible
- Easy to customize

================================================================================
2. FILE STRUCTURE
================================================================================

scripthookvdotnet.info2/
│
├── index.html          - Home page with hero section and features
├── about.html          - About page with mission and vision
├── contact.html        - Contact page with Google Form button
├── download.html       - Download page with system requirements
├── style.css           - All styling and responsive design
├── script.js           - Interactive elements and mobile navigation
└── README.txt          - This file (documentation)

================================================================================
3. HOW TO RUN LOCALLY
================================================================================

OPTION 1: Direct Browser Opening (Simple)
------------------------------------------
1. Navigate to the project folder
2. Double-click on "index.html"
3. The website will open in your default browser

OPTION 2: Using Live Server (Recommended for Development)
----------------------------------------------------------
If you have Visual Studio Code:
1. Install "Live Server" extension
2. Right-click on "index.html"
3. Select "Open with Live Server"
4. The website will open with auto-reload on changes

OPTION 3: Using Python HTTP Server
-----------------------------------
1. Open terminal/command prompt in project folder
2. Run: python -m http.server 8000
3. Open browser and go to: http://localhost:8000

OPTION 4: Using Node.js HTTP Server
------------------------------------
1. Install: npm install -g http-server
2. Run: http-server
3. Open the provided local URL in your browser

================================================================================
4. CUSTOMIZATION GUIDE
================================================================================

CHANGING SITE NAME & BRANDING
------------------------------
1. Open all HTML files (index.html, about.html, contact.html, download.html)
2. Find "ScriptHookVDotNet" in navigation and footer
3. Replace with your desired site name
4. Save all files

UPDATING CONTENT
----------------
1. Open the specific HTML file you want to edit
2. Locate the content you want to change (use Ctrl+F to search)
3. Edit the text between HTML tags
4. Save the file and refresh browser

MODIFYING NAVIGATION MENU
--------------------------
Location: All HTML files in the <nav> section
Example:
    <ul class="nav-menu">
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <!-- Add more menu items here -->
    </ul>

EDITING FOOTER
--------------
Location: All HTML files in the <footer> section
- Update copyright year
- Change "Designed & Developed" credit
- Add/remove social links
- Modify footer sections

================================================================================
5. COLOR SCHEME
================================================================================

Current Color Palette:
----------------------
Primary Color:    #BBFE6C (Lime Green) - Buttons, accents, highlights
Secondary Color:  #FFFFFF (White) - Backgrounds, text on dark
Dark Color:       #1E1E1E (Dark Gray/Black) - Navbar, footer, headings
Text Color:       #1E1E1E (Dark Gray/Black) - Body text
Light Gray:       #F5F5F5 - Card backgrounds
Medium Gray:      #E0E0E0 - Subtle elements

HOW TO CHANGE COLORS
--------------------
1. Open "style.css"
2. Find the ":root" section at the top
3. Modify the CSS variables:

:root {
    --primary-color: #BBFE6C;    /* Change this for primary color */
    --secondary-color: #FFFFFF;   /* Change this for secondary color */
    --dark-color: #1E1E1E;       /* Change this for dark elements */
    --text-color: #1E1E1E;       /* Change this for text color */
}

4. Save and refresh browser to see changes

================================================================================
6. LINKS & URLS
================================================================================

UPDATING EXTERNAL LINKS
-----------------------

Google Form Link (Contact Page):
- File: contact.html
- Find: https://docs.google.com/forms/d/e/1FAIpQLSd4EKhtkytt...
- Replace with your Google Form URL
- Line: Inside "btn-contact-form" button href attribute

GitHub Repository Link:
- Files: All HTML files
- Find: https://github.com/scripthook-vdotnet
- Replace with your GitHub repository URL

Download Link:
- File: download.html
- Find: https://scripthookvdotnet.info/download/
- Replace with your download page URL
- Line: Inside "btn-download-main" button href attribute

Official Site Link:
- Files: index.html and footer sections
- Find: https://scripthookvdotnet.info/
- Replace with your official website URL

INTERNAL NAVIGATION LINKS
--------------------------
These links connect pages within the website:
- index.html (Home)
- about.html (About)
- contact.html (Contact)
- download.html (Download)

Keep these consistent across all pages for proper navigation.

================================================================================
7. SEO & KEYWORDS
================================================================================

FOCUS KEYWORDS
--------------
Current keyword: "script hook v dot net"
Location: index.html (naturally placed in content)

HOW TO ADD/MODIFY KEYWORDS
---------------------------
1. Open the HTML file
2. Add keywords naturally in paragraphs and headings
3. Link keywords to relevant URLs (if needed)
4. Avoid keyword stuffing - keep it natural

META DESCRIPTIONS
-----------------
Each page has a meta description in the <head> section:
<meta name="description" content="Your description here">

Update these for better SEO:
- Keep under 160 characters
- Include relevant keywords
- Make it compelling for click-through

PAGE TITLES
-----------
Format: [Page Name] - ScriptHookVDotNet
Example: <title>Home - ScriptHookVDotNet</title>

Update these to match your branding.

================================================================================
8. RESPONSIVE DESIGN
================================================================================

BREAKPOINTS
-----------
- Desktop: 1200px and above (default)
- Tablet: 768px - 1199px
- Mobile: Below 768px
- Small Mobile: Below 480px

TESTING RESPONSIVENESS
----------------------
1. Open website in browser
2. Press F12 to open Developer Tools
3. Click "Toggle Device Toolbar" icon (or Ctrl+Shift+M)
4. Test different screen sizes

MOBILE NAVIGATION
-----------------
The hamburger menu appears on screens below 768px.
It's automatically handled by script.js.

================================================================================
9. BROWSER COMPATIBILITY
================================================================================

SUPPORTED BROWSERS
------------------
✓ Google Chrome (latest)
✓ Mozilla Firefox (latest)
✓ Microsoft Edge (latest)
✓ Safari (latest)
✓ Opera (latest)

TESTING
-------
Test your website on different browsers to ensure consistency:
1. Open website in each browser
2. Check layout and functionality
3. Test mobile navigation
4. Verify all links work

================================================================================
10. SUPPORT & CONTACT
================================================================================

COMMON ISSUES & SOLUTIONS
--------------------------

Issue: Website not loading styles
Solution: 
- Check that style.css is in the same folder as HTML files
- Clear browser cache (Ctrl+Shift+Delete)
- Check file paths in <link> tags

Issue: Mobile menu not working
Solution:
- Ensure script.js is properly linked
- Check browser console for JavaScript errors (F12)
- Verify script.js is in the same folder as HTML files

Issue: Links not working
Solution:
- Verify URLs are correct and active
- Check for typos in href attributes
- Ensure target="_blank" for external links

CUSTOMIZATION HELP
-------------------
For specific customizations:
1. Identify the element you want to change
2. Use browser Developer Tools (F12) to inspect it
3. Find the corresponding CSS class/ID in style.css
4. Modify the styles and save

ADDITIONAL RESOURCES
--------------------
- HTML Reference: https://developer.mozilla.org/en-US/docs/Web/HTML
- CSS Reference: https://developer.mozilla.org/en-US/docs/Web/CSS
- JavaScript Reference: https://developer.mozilla.org/en-US/docs/Web/JavaScript
- Web Accessibility: https://www.w3.org/WAI/

================================================================================
                            CREDITS & LICENSE
================================================================================

Designed & Developed for the GTA V Modding Community
Font: Inter & Poppins (Google Fonts)
Icons: SVG Icons (Bootstrap Icons style)

© 2024 ScriptHookVDotNet. All rights reserved.

================================================================================
                            END OF DOCUMENTATION
================================================================================

For questions, issues, or contributions, visit:
https://github.com/scripthook-vdotnet

Thank you for using this template!
