# NACHOS

A single page restaurant site, hand written in HTML, CSS and JavaScript. No framework, no build step.

## What is here

- Hero section with the restaurant name
- Menu section with dish photography
- Responsive navigation that collapses to a menu icon on small screens
- Navbar that changes on scroll
- Section reveal styling in `style.css`
- Fonts from Google Fonts (Inter and Poppins) and icons from Font Awesome

## Files

```
index.html    Markup for the whole page
style.css     All styling, including the media query for mobile
main.js       Menu toggle and scroll state for the navbar
images/       Hero, logo, section and three dish photos
```

## Running it

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploying

Any static host works: GitHub Pages, Netlify, Vercel or Cloudflare Pages. The one rule is that the `images` folder ships with the HTML.

## Notes for a next pass

1. The commented out navbar block is still in `index.html`, so remove it before showing the source to a client.
2. Dishes and prices are static text. A menu that a restaurant can update without touching code is the first thing a real client asks for.
3. There is one media query in the stylesheet, so the layout between tablet and desktop widths is worth checking.

## Author

Enoch Philip Dibal, https://devenoch.cv
