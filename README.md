# Foodie — Restaurant Concept Website

A student midterm assignment project: a concept website for a home-style restaurant, built with pure HTML5 + CSS3. No build tools or dependencies — just open it in a browser.

## About the Project

Foodie is a concept website for a cozy home-style restaurant. The target audience is city residents looking for a comfortable place for lunch or dinner. The site aims to:

- Showcase the restaurant's menu and signature dishes
- Present the atmosphere and the team behind the food
- Let guests book a table online and get in touch

## Pages

| Page | File | Content |
|------|------|---------|
| Home | `foodie-home.html` | Hero banner, popular dish cards, project intro |
| Menu | `foodie-menu.html` | Main courses, starters & salads, desserts |
| About | `foodie-about.html` | Restaurant story, atmosphere, team, ingredients |
| Reservation | `foodie-reservation.html` | Booking form (name, date, time, guests, special requests) |
| Contact | `foodie-contact.html` | Address, phone, opening hours, message form |

## Tech Stack

- **HTML5** — semantic structure, native form validation (`required`, `type="email"`, date/time inputs)
- **CSS3** — Flexbox + Grid layouts, CSS variables, transitions, media queries
- **Google Fonts** — Poppins typeface
- **Images** — Unsplash stock photos

## Design

The color palette is defined once as CSS variables in `foodie.css` (`:root`):

| Variable | Value | Usage |
|----------|-------|-------|
| `--primary` | `#e63946` | Headings, prices, buttons |
| `--dark` | `#1d1d1d` | Header and footer backgrounds |
| `--cream` | `#fff8f0` | Page background |
| `--accent` | `#ffb703` | Logo highlight, nav hover states |

## Features

- Shared navigation bar across all five pages with an automatic active-page highlight (`active` class)
- Dish cards with a hover lift + shadow transition
- Menu list styled as "dish name — dotted line — price" with space-between alignment
- Reservation and contact forms with friendly inputs and HTML5 validation
- Responsive design: the card grid auto-fits columns; below 640px the navigation stacks vertically and headings shrink

## Project Structure

```
midterm project/
├── foodie-home.html          # Home page
├── foodie-menu.html          # Menu page
├── foodie-about.html         # About page
├── foodie-reservation.html   # Reservation page
├── foodie-contact.html       # Contact page
└── foodie.css                # Shared stylesheet for the whole site
```

## Getting Started

No dependencies to install — just double-click `foodie-home.html` to open it in a browser.

Optionally, run a local server:

```bash
# Python 3
python -m http.server 8000
```

Then visit <http://localhost:8000/foodie-home.html>.

## Notes

This is a student course project (Midterm Assignment). The two forms are for display purposes only — there is no backend, so submissions are not actually sent anywhere.

© 2026 Foodie Restaurant
