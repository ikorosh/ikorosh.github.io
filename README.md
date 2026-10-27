# Portfolio Website

My personal portfolio website, available in German and English. It introduces me, lists my projects with links to the code, and shows my skills and contact details.

Live site: https://ikorosh.github.io

## What it contains

- Two pages: index.html (German) and en.html (English), linked to each other
- Sections for projects, skills (including languages) and contact
- A responsive layout that works on phones and desktop screens
- Basic accessibility: semantic HTML, a language attribute on each page, and a visible focus outline for keyboard navigation

## Technology

Plain HTML and CSS. There is no JavaScript, no framework and no build step. The site is hosted with GitHub Pages directly from the main branch.

## Run it locally

Download or clone the repository and open index.html in a browser. No installation is needed.

## Project structure

index.html   German page
en.html      English page
style.css    shared styles for both pages
## Design decisions

- Two separate pages instead of a language switcher, so no JavaScript is needed.
- The CSS uses a few color variables at the top, so colors can be changed in one place.
- The text is limited to a readable width and centered, and the navigation wraps on small screens.

## Known limitations

- The page is simple and has no images or screenshots yet.
- Content is duplicated between the two pages, so changes have to be made twice.

## Planned

- Add new projects to both pages when they are finished
- Check the pages with an accessibility checker