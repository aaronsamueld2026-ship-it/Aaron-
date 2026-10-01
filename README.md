# Force Field — Five Forces Strategy Lab

A standalone classroom game built with HTML, CSS, JavaScript, and p5.js WEBGL. Students investigate Porter's Five Forces in an interactive 3D industry map, complete five strategy challenges, and play two Tamil traditional game inspired bonus rounds:

- **Pallanguzhi:** allocate 12 strategy seeds across five competitive pressures.
- **Aadu Puli Aattam:** place goat blockers to defend the profit gate against two rival routes.

These bonus rounds adapt resource sowing and blocking strategy for the business lesson; they are not intended to reproduce every regional rule variation.

## Run locally

Open `index.html` in a modern browser. The 3D map loads p5.js from jsDelivr, so an internet connection is needed for the WebGL scene. The force buttons remain usable if the library cannot load.

## Deploy on Netlify

This is a static site with no build step or packages to install. Connect the GitHub repository in Netlify, leave the build command blank, and set the publish directory to `.` (the project folder containing `index.html`). The included `netlify.toml` sets these defaults and basic response headers.
