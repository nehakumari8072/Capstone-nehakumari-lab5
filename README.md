# Foodie - Food Delivery Website

**Theme:** Food Delivery App
**Course:** Web Dev I - Lab Assignment 5 (Capstone - Responsive Website Project)
**Student:** Neha Kumari, Section D, KR Mangalam University

## Description
Foodie is a responsive, static food delivery landing page built using only HTML5 and CSS3.

## Sections Implemented
- **Header / Navigation:** logo, menu links, Login/Sign Up buttons, "Skip to main content" link, mobile menu toggle
- **Hero Banner:** title, tagline, "Order Now" button, hero image, location search form
- **Browse by Category:** Pizza, Burgers, Sushi, Indian, Chinese, Desserts
- **Featured Restaurants:** restaurant cards with image, cuisine and rating
- **Promo Offers:** three offer cards
- **Testimonials:** customer review cards
- **App Download:** aside section
- **Footer:** contact links, newsletter form, social icons (SVG), copyright

## Breakpoints Used
| Device  | Width        | Layout change                                   |
|---------|--------------|-------------------------------------------------|
| Desktop | 1024px and up| 4-column restaurant grid, 6-column categories   |
| Tablet  | up to 1024px | 2-column restaurants, 3-column categories        |
| Tablet  | up to 768px  | Single-column grids, header stacks, menu toggle  |
| Mobile  | up to 480px  | Smaller root font, 2-column categories           |

## Layout Techniques
- **Flexbox:** header, hero, search form, footer
- **CSS Grid:** categories, restaurant cards, offers, testimonials
- **CSS Variables** (`:root`) for colors, fonts and spacing
- Relative units (`rem`, `%`) and a root font-size
- Hover effects, `transition: all 0.25s ease`, and a keyframe animation (`fadeSlide`) on the hero

## How to Open (Local)
1. Download or clone this repository.
2. Open the `foodie` folder.
3. Double-click `index.html` to open it in your browser (or use "Open with Live Server" in VS Code).

## GitHub Pages Link (optional)
https://nehakumari8072.github.io/capstone-neha-kumari-lab5/

## Folder Structure
```
capstone-neha-kumari-lab5/
├── index.html
├── style.css
├── README.md
└── images/
    ├── hero.jpg
    ├── pizza-palace.jpg
    ├── burger-hub.jpg
    ├── sushi-world.jpg
    └── spice-route.jpg
```