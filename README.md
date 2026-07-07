# Image Grid Layout Component

This repository contains my completed clean CSS Grid solution to the [Image Grid Layout](https://roadmap.sh/projects/image-grid) challenge on roadmap.sh.

## Project Overview
The objective of this project is to create an asymmetrical gallery structure using structural **HTML5 markup and vanilla CSS Grid rules**. It provides hands-on mastery over complex grid layout properties (`grid-column`, `grid-row`), image bounding handles (`object-fit: cover`), and viewport breakpoints.

## Features & Requirements Met
- **Asymmetrical Grid Mapping:** Employs precise row and column span groupings to create a bento-box puzzle flow matching the reference layout mockup perfectly.
- **Aspect-Ratio Safety Enforced:** Uses `object-fit: cover` to ensure high-resolution landscape images fit inside their variable box containers without stretching or squishing.
- **Micro-Animation Micro-Interactions:** Includes smooth lifting states (`translateY`) and elegant internal zoom animations on hover to elevate engagement.
- **Adaptive System Dark Mode:** Coordinates global designs using CSS variables bound to preference media states (`prefers-color-scheme`).
- **Responsive Mobile Collapsing:** Uses tailored `@media` rules to transition from a 4-column layout to a single-column stack on compact viewports.

## Setup & Preview
To preview this project locally:
- Clone this repository to your local machine.
- Ensure your local directory includes the required asset resources.
- Open index.html directly inside any modern web browser.