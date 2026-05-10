# Nexus Hotel 

A startic website for **Nexus Hotel**, a wood-fired dining experience rooted in Nairobi, Kenya. The site bridges heritage Kenyan farming with modern culinary artistry, offering visitors a window into the restaurant's story, services, team, and reservation system.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Accessibility](#accessibility)
- [Technologies Used](#technologies-used)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Overview

Nexus Hotel is a Nairobi-based fine dining restaurant specializing in wood-fired cuisine inspired by local produce from the Rift Valley. This website serves as the restaurant's digital presence, showcasing its services, kitchen team, and a reservation enquiry form.

---

## Features

- **Hero Section** — A compelling value proposition introducing the restaurant's identity and ethos.
- **Services Section** — Highlights two core offerings: Fine Dine-In and Bespoke Catering.
- **Team Section** — Profiles of key staff including the Head Chef, Executive Chef, and Master Sommelier, with a behind-the-scenes kitchen video.
- **Reservation Form** — A structured booking form with client-side validation including:
  - Required field enforcement
  - Email format validation
  - Kenyan phone number format (`0XXXXXXXXX`) via regex pattern
  - Date picker
  - Special requests textarea
- **Footer** — Social media links (Instagram & Facebook) and copyright information.

---

## Project Structure

```
nexus-hotel/
|-- index.html
|-- assets/
    |-- images/
    |   |-- faisal-BS4Zeq7xDRk-unsplash.jpg       # Fine dine-in service image
    │   |-- lucas-law-KDVGz-qnHfc-unsplash.jpg     # Catering service image
    │   |-- rc-cf-FMh5o5m5N9E-unsplash.jpg         # Head Chef Mr Wong
    │   |-- febrian-zakaria-SiQgni-cqFg-unsplash.jpg # Executive Chef Samuel
    │   |-- gilbert-pagunaling-hSw71lns6HI-unsplash.jpg # Master Sommelier Mike David
    |-- videos/
        |-- Food_Reel_-_Darío_Idoate(720p).mp4     # Kitchen culture reel
```

---

## Getting Started

No build tools or dependencies required. This is a plain HTML project.

1. **Clone or download** the repository.
2. Ensure the `assets/` folder is in the same directory as `index.html`.
3. Open `index.html` in any modern web browser.

```bash
git clone https://github.com/JeromeJason-dev/nexus-hotel.git
cd nexus-hotel
open index.html
```

---

## Accessibility

This project was built with accessibility in mind:

- Semantic HTML5 elements (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<figure>`)
- ARIA labels on navigation and social media links
- `alt` text on all images
- `role="contentinfo"` on the footer
- Form labels properly associated with their inputs via `for`/`id` pairs
- Logical heading hierarchy (`h1` → `h2` → `h3`)

---

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure and content |
| Browser-native validation | Form input validation |
| MP4 video | Kitchen culture media embed |

> No CSS or JavaScript frameworks are used — this is a pure HTML project.

---

## Future Improvements

- [ ] Add CSS styling for a polished visual design
- [ ] Connect the reservation form to a backend or email service 
- [ ] Add a menu/gallery page
- [ ] Integrate a live booking/calendar system

---

## License

This project is licensed under the MIT license


## Author
**Jason Ngariu**

* Github: https://github.com/JeromeJason-dev
* Email: jasonnem048@gmail.com