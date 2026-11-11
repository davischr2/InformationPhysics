# Information Physics

A complete single-page, build-free static site. No framework, package install, tracking, or external assets. Styles and JavaScript are included in index.html. The supplied hero artwork is in hero.png. Uses the system sans-serif font.

## Preview
Open index.html in a browser, or run `python -m http.server 8080` in this folder and visit http://localhost:8080.

## Upload to GitHub Pages
1. Create a GitHub repository.
2. Upload the contents of this folder to the root of its main branch. Include all files in this folder, including the logo, favicon, and touch-icon assets.
3. In the repository, open Settings > Pages. Select Deploy from a branch, then main and /(root). Save.
4. Use the Pages URL displayed by GitHub after deployment finishes. All asset paths also work on repository subpaths.

## Conversation requests
The form opens the visitor's email application with a prepared message addressed to davischr2@gmail.com. The visitor must send that email. It does not claim delivery or store submissions in the browser. The page includes native validation, a honeypot, and an honest status message. A configured email app is required; a fallback address is displayed after Send.

To change the recipient, edit the recipient constant near the end of index.html. This public client-side address is visible in the source. For automatic delivery without an email app, connect a form service or server endpoint; never place private API keys in this static repository.

## Custom domain
No CNAME is included because domain ownership and DNS were not configured. Once the domain is ready, set informationphysics.ai in GitHub Pages settings and configure the DNS records GitHub supplies. Enable HTTPS after verification.

## Content
The public page has no navigation, secondary pages, platform names, mechanism descriptions, demos, trials, or invented customer claims. The user-supplied artwork is a visual metaphor labeled Velocity, Provenance, and Security.

## Brand assets
The approved Convergence logo uses two ivory forms and a cyan bottom form converging to the right, enclosed by a white rounded-square outline on deep navy. logo.svg is the scalable master. favicon.svg, favicon.ico (16/32/48 pixels), individual PNG favicons, apple-touch-icon.png (180 pixels), and logo-512.png are included. The header pairs the symbol with the company name horizontally.
