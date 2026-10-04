# My Portfolio Landing Page

This is the code for my personal landing page. I wanted a clean, simple way for people to scan a QR code on my resume and instantly get to my LinkedIn and GitHub profiles without any extra fluff.

👉 **Live Site:** https://snewell-cybersec.github.io/

---

## How This Was Put Together

Instead of using a generic, third-party link service, the goal was to deploy a custom, lightweight solution directly on GitHub. This project involved configuring the layout, fixing broken link paths, sorting out the formatting, and handling the live deployment on the web server.

### Simple Breakdown:
* **The Text & Links (HTML):** This handles the basic content setup to put my name on the screen and ensure the buttons accurately link to the external profiles.
* **The Style (CSS):** This controls the dark theme colors, rounds the buttons into neat capsules, and forces everything to stack into a clean vertical line so it looks right on a mobile screen.
* **The Shield Icon (SVG):** Instead of uploading a heavy image file that might look blurry, the cybersecurity shield and logos are drawn directly inside the code using mathematical coordinates to keep the page fast and lightweight.
* **The Hosting (GitHub Pages):** GitHub acts as the web server for free. It hosts the files, provides the live internet URL, and automatically keeps the connection encrypted with HTTPS.
