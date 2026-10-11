VIBU PERSONAL WEBSITE
=====================

Files:
- index.html: website content
- style.css: dark purple/blue responsive design
- script.js: mobile navigation and current year

PREVIEW ON YOUR COMPUTER
1. Extract this ZIP.
2. Open index.html in a browser.

ADD YOUR PHOTO
The current hero uses a safe placeholder, not a real photo.
To add your photo:
1. Put a photo named profile.jpg in this folder.
2. In index.html, replace the <div class="portrait-placeholder"> ... </div> block
   with: <img class="profile-photo" src="profile.jpg" alt="Vibu">
3. Add this to style.css:
   .profile-photo { width:100%; height:100%; min-height:370px; object-fit:cover; position:absolute; inset:0; }

PUBLISH ONLINE WITH GITHUB PAGES
1. Sign in to GitHub and create a new public repository named vibu-website.
2. Upload index.html, style.css, and script.js (and profile.jpg only if you want it public).
3. In repository Settings -> Pages, choose Deploy from a branch, select main and /(root), then Save.
4. Wait for GitHub Pages to publish and follow the URL shown in Settings -> Pages.

PRIVACY
Do not publish your home address, personal phone number, school timetable, ID numbers,
passwords, or other private details. Review all text and photos before making the repository public.
Update the example project cards with real projects when you have them.
