# NOTES

## 07 DEC 2023

- Added working page links to each page
- I was provided two SVGs of each planet. One is the full planet, one shows the layer composition of each planet. Must figure out how to toggle between the two using CSS. Will add each planet SVG to respective page.
- Noticed that the planet svg shadowing for neptune is a little off. Will revisit later.

## 15 APR 2024

- Picked this project back up.
- Adjusted font.
- Added the stars svg and background color across all pages.
- Removed text decoration from hyperlinks. Added an on-hover effect to change the text color on hover.
- Worked primarily on the index page. Managed to stack the planet svg on top of the layer composition svg, I think. Will need to add a hover effect to toggle between the two, as well as the padding and margins to make it sit where I need it to.
- Added classes to the planet SVGs to make them responsive. Also added classes to planet names, planet descriptions and source for the same reason.
- I GOT THE SVG LAYERING AND ON HOVER TO WORK!
- Updated each page with SVG layering and on hover effect.
- Turned "Wikipedia" into a hyperlink to the desired page. Will have to apply this to all 3 wikipedia links on each page. The class structure I did might have to change to avoid overlap. Will revisit.

## 17 APR 2024

- Worked on index.html and styles.css only.
- Added the source svg to the wikipedia links.
- Added set borders around the planet facts, as well as got the font size closer to end goal.
- Created a hamburger menu for planet overview, internal structure, and surface geology. On click displays corresponding information.

## 21 APR 2024

- Worked on index.html and styles.css only.
- Finally figured out how to get tab navigation where I wanted it.
- Wrote a script tag to display only the planet overview on page load, then displays each section on click.
- Two days ago I fixed the on hover for the svg element so that the on hover only works on the planet image, not the whole container.

## 22 AUG 2024

- Picking up where I left off. I have began transferring individual planet data to index template and last worked on Earth.
- I need to finish transferring the data for the remaining planets.
- Noticed that my hover transition on planet svgs in not functioning for any planets other than Mercury. Addressing now.
- SVG on hover wasn't working becuase I didn't have the classes on the svg elements. Fixed.
