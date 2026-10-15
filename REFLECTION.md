# Reflection

## 1. HTTP Request Path
When a user types `https://RubinK21.github.io` into a browser:
1. **DNS Lookup:** The browser queries DNS servers to translate `RubinK21.github.io` into the IP address of GitHub's hosting server.
2. **TCP/TLS Handshake:** The browser establishes a secure connection with GitHub's server on port 443.
3. **HTTP GET Request:** The browser sends an `GET / HTTP/1.1` request to the server.
4. **Server Response:** GitHub Pages locates `index.html` at the root directory and sends an HTTP 200 OK response with the HTML document payload.
5. **Rendering & Additional Requests:** The browser parses `index.html`, discovers external resources (`style.css`, `assets/profile.jpg`), and issues subsequent HTTP GET requests to fetch them before rendering the full page.

## 2. AI Attribution

No AI model were used in the physical assistance of writing the Website's code. Only for answering logic and specific syntax oriented questions ("which order 'h1' ,'table', '...' should go in the .html?" and other questions revolving the matter).


# REFLECTION October 14, 2026

## 1. flex-direction: row vs column 
the difference between the row and column for flex-direction is when using row (the default), arranges flex items horizontally, left to right (like a row moving across the screen). flex-direction: column arranges them vertically, top to bottom. I used row for the desktop nav bar so the logo and links sit side by side, and switched to column inside the 768px media query so the nav links stack vertically on mobile.


## 2. Why relative units over fixed px
Relative units scale based on the viewport or parent element, so layouts adapt smoothly across different screen sizes. Fixed px values stay the same regardless of screen size, which can cause text or elements to be too large on mobile or too small on desktop. Using relative units avoids content overflowing or becoming unreadable on smaller screens.


## 3. AI Attribution
No AI model were used in the physical assistance of writing the Website's code. Only for answering logic and specific syntax oriented questions.