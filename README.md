# Admin Dashboard

Project from [The Odin Project – Intermediate HTML and CSS course](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard).

**Live demo:** https://ayxan1110.github.io/odin-admin-dashboard/

An admin dashboard layout with a sidebar, a header and a main area that shows my own Odin projects as cards, plus announcements and trending users.

## What I used
- **CSS Grid** for the page layout (sidebar on the left, header and main on the right) and for the main area (projects column and a side column)
- A second grid for the project cards with `repeat(auto-fill, minmax(260px, 1fr))`, so the number of columns changes with the window width
- **Flexbox** inside the components: the nav links, the header, the buttons, the card footers and the trending list
- Icons from Material Design Icons as inline SVG, defined once in a `<symbol>` sprite and reused with `<use>`
- Avatars made from initials in coloured circles, so no images are needed
- A `@media` query that moves the right column below the projects on smaller screens
- Roboto from Google Fonts
