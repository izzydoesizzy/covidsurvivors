# COVID Survivors Project

> An oral history project documenting the lived experience of COVID-19 survivorship through rapid response video collection, community support, and public archiving.

![Status](https://img.shields.io/badge/status-archived-lightgrey)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Live Demo

[https://izzydoesizzy.github.io/covidsurvivors](https://izzydoesizzy.github.io/covidsurvivors)

## Overview

The COVID Survivors Project is a community-driven oral history initiative that collects self-recorded video testimonials from people who experienced COVID-19 infection or lost immediate family members to the virus. The site explains the project's mission -- "remember, reflect, record" -- provides structured video prompts for contributors, and connects to a YouTube channel for viewing submissions. Featured on Product Hunt, the project focuses on preserving authentic first-person narratives for both present-day solidarity and future historical reference.

## Features

- Hero section with project logo, tagline ("remember, reflect, record"), and call-to-action buttons for video submission and viewing
- Product Hunt badge integration showcasing the project's launch
- Detailed "About the Project" section explaining the scope of survivorship documentation
- Multi-slide Bootstrap carousel walking through the mission, sharing ethos, importance, format, and future plans
- Six structured video prompt categories: Introduction, Symptoms, Recovery Journey, Mental Health, Support Network, and Government Response
- Google Forms integration for video submission uploads
- YouTube channel integration for viewing published testimonials
- Contact section with email and London, UK mailing address
- Social media links: Facebook, Twitter, Instagram, Reddit, YouTube
- Responsive fixed-top navbar with smooth scrolling navigation
- Slick slider, WOW.js scroll animations, and Magnific Popup
- Google Analytics tracking
- CNAME configured for custom domain (covidsurvivorsproject.com)
- Downloadable prompt questions PDF guide

## Screenshots

<!-- ![Screenshot](screenshot.png) -->

## Tech Stack

- HTML5
- CSS3 (Bootstrap 4, Animate.css, custom styles)
- jQuery 3.3
- Slick Slider
- WOW.js (scroll animations)
- Magnific Popup (lightbox)
- Counter Up (animated counters)
- Waypoints
- Font Awesome
- Google Analytics
- Hosted on GitHub Pages

## Getting Started

### Run Locally

No build step required:

1. **Clone the repository**
   ```bash
   git clone https://github.com/izzydoesizzy/covidsurvivors.git
   cd covidsurvivors
   ```

2. **Open in browser**
   ```bash
   open index.html
   # or use a local server:
   npx serve .
   ```

### Deploy to GitHub Pages

1. Push to the `master` branch
2. Go to Settings > Pages > Source: Deploy from branch
3. Site live at `https://izzydoesizzy.github.io/covidsurvivors`

## Project Structure

```
covidsurvivors/
├── index.html              # Main landing page
├── archive.html            # Archive page
├── blog.html               # Blog page
├── covid-splash.jpg        # Social sharing image
├── promptquestions.pdf      # Downloadable video prompt guide
├── CNAME                   # Custom domain config
├── css/
│   ├── bootstrap.min.css   # Bootstrap 4
│   ├── main.css            # Primary styles
│   ├── custom.css          # Custom overrides
│   └── plugins/            # Animate.css, Slick, Magnific Popup
├── js/
│   ├── main.js             # Main application logic
│   ├── bootstrap.min.js    # Bootstrap JS
│   └── plugins/            # jQuery, Slick, WOW, Counter Up, etc.
└── img/                    # SVG illustrations, logo, icons
```

## Tags

`fun-project` `landing-page`

## Created

2020-05

## Status

Legacy -- Built during the COVID-19 pandemic as a rapid response community project.

## Author

**Izzy Piyale-Sheard** -- [@izzydoesizzy](https://github.com/izzydoesizzy)
