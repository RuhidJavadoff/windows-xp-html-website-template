Windows XP Desktop Simulator (Demo)
This project is a demo application aiming to recreate the nostalgic look and some basic functionalities of the classic Windows XP desktop environment using web technologies (HTML, CSS, and JavaScript). This project is for entertainment and experimental purposes.

Features
Windows XP Style Loading Screen: Classic XP boot screen and loading bar when the page opens.

Desktop Interface: Classic XP "Bliss" wallpaper and desktop icons.

Draggable Icons (Drag & Drop): Ability to drag and drop desktop icons to different positions using a mouse or touch.

Icon Position Saving: The last positions of the icons are saved in the browser's local storage (localStorage).

Start Button & Simple Menu: Functional "Start" button that opens a simple menu upon clicking (with items like "Sample 1", "Sample 2").

Context Menu (Right Click / Long Press):

An XP-style context menu opens on right-clicking the desktop (or long-pressing on mobile).

Screen Sizes (Scaling): Option to change the display scale of desktop elements from 50% to 300%.

Lock Icon Arrangement: A toggle function to lock/unlock the dragging of icons.

Scaling and lock states are saved in browser storage.

Taskbar:

Classic XP taskbar at the bottom of the screen.

Functional real-time clock.

System Notification: An XP-style notification balloon appears in the bottom-right corner after the loading screen finishes.

Linked Icons: Desktop icons link to various web pages you define.

Responsive Design: Adapts to different screen sizes (desktop, tablet, mobile).

Technologies Used
HTML5

CSS3 (Custom styles)

JavaScript (Vanilla JS)

How to Use / Run
This is a fully client-side project.

Download or clone the project files from GitHub.

Open the main index.html file in any modern web browser.

Currently, the CSS and JavaScript code are embedded directly within the index.html file. Optionally, you can extract them into separate style.css and script.js files and link them in the HTML as follows:

<head>
    ...
    <link rel="stylesheet" href="style.css">
    ...
</head>
<body>
    ...
    <script src="script.js"></script>
</body>

Screenshots
Here are some screenshots from the project:

1. Loading Screen and Desktop View:


2. Start Menu, Context Menu, and Notification:


Customization
Icons and Links: Edit the div.desktop-icon elements within the .desktop-item-container in index.html to change icon images, names, and links.

Start Menu Content: Modify the populateStartMenu() function in script.js (or the <script> block in HTML) and the #start-menu HTML structure to change the Start Menu contents.

Background: Change the background-image property of the body element in style.css (or the <style> block in HTML) to customize the desktop background.

Support This Project / Donate
If you like this project and want to support its development, you can make a small donation through the following channels. Your support will help in adding new features and further improving the project.

Donate via My Website:

Visit Donate Page
(Please replace https://ruhidjavadoff.site/donate with the exact URL of your donate page if it's different)

Donate via PayPal:

To: ruhidjavadoff@gmail.com

PayPal.Me/RuhidJavadoff
(If you have a PayPal.Me username, replace "RuhidJavadoff" with it.)

Donate with PayPal (USD)
(You can change the currency code (USD) as needed, e.g., EUR or AZN)

Thank you for your support!

Author / Contributors
Main Idea and Requirements: Ruhid Javadov

Website: ruhidjavadoff.site

Code Generation and Assistance: Google Gemini (AI Assistant)

Future Development Ideas (Potential Additions)
Functional "All Programs" menu.

Opening, closing, and dragging windows for simulated applications.

More detailed context menu options (e.g., "Refresh", "New Folder").

Active program tabs on the taskbar.
