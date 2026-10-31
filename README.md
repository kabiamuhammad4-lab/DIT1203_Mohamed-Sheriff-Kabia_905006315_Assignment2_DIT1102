# GreenHarvest

A responsive five-page-plus website for **GreenHarvest**, a small business that connects farmers and buyers in Sierra Leone.
It is my work for **DCOMP 204 Web Design, Assignment 2** (HTML, CSS and a responsive website) at Limkokwing University of Creative Technology, Sierra Leone.

- **Student:** Muhammad Kabia
- **Lecturer:** Amadu Kamara
- **Technologies:** HTML5 and CSS3 only (no JavaScript, no frameworks)

The website turns my Assignment 1 wireframes (sitemap, user journeys and Figma prototype) into a real website.

## Pages

| Page | File | What it does |
| --- | --- | --- |
| Home | `index.html` | Hero, numbers, about preview, featured crops, services, testimonials and latest tips |
| About Us | `about.html` | Our story, mission, vision, values and the team |
| Our Crops | `crops.html` | The major feature: crop cards with category buttons and page numbers |
| Services | `services.html` | Buy crops, sell your harvest, delivery and storage, how it works and FAQ |
| Farming Tips | `tips.html` | Featured article, article cards with topic buttons and a newsletter form |
| Contact | `contact.html` | Message form, contact details and a map |

## Features

- **Responsive:** works on mobile, tablet and desktop. The layout changes at 900px and 600px, and there is a menu button on small screens.
- **CSS-only filters:** the category buttons on Our Crops and Farming Tips use hidden radio buttons and CSS, so no JavaScript is needed.
- **CSS-only extras:** the phone menu and the FAQ open and close with CSS only.
- **Accessible:** skip link, clear keyboard focus, alt text on every picture, labelled form fields, one `h1` per page and good colour contrast.
- **Fast:** images are resized, picture sizes are set in the HTML and lower pictures load lazily.
- **Same look on every page:** one stylesheet, one header and one footer.

## Design choices

- **Colours:** deep leaf green for the brand, chilli red for small accents like prices, and a pale green-grey for sections.
- **Fonts:** Bricolage Grotesque for headings and Atkinson Hyperlegible for text. Atkinson was made to be easy to read, which helps people on small phone screens. If the fonts cannot load, the browser uses Segoe UI, Tahoma or Verdana.
- **Pattern:** the faint diagonal stripes on the dark green areas look like rows of crops in a field.

## Folder structure

```
GreenHarvest/
  index.html
  about.html
  crops.html
  services.html
  tips.html
  contact.html
  css/
    style.css
  images/          photos, logo and icons
  screenshots/     desktop, tablet and phone screenshots of every page
  README.md
  .gitignore
```

## How to run it

1. Download or clone this repository.
2. Open the folder in VS Code.
3. Open `index.html` in a browser. You can also use the Live Server extension and click "Go Live".

The website needs an internet connection for two small things only: the Google Fonts and the map on the Contact page.

## Screenshots

Screenshots of every page on desktop, tablet and phone are in the `screenshots` folder.

| Page | Desktop | Tablet | Phone |
| --- | --- | --- | --- |
| Home | `home-desktop.jpg` | `home-tablet.jpg` | `home-mobile.jpg` |
| About Us | `about-desktop.jpg` | `about-tablet.jpg` | `about-mobile.jpg` |
| Our Crops | `crops-desktop.jpg` | `crops-tablet.jpg` | `crops-mobile.jpg` |
| Services | `services-desktop.jpg` | `services-tablet.jpg` | `services-mobile.jpg` |
| Farming Tips | `tips-desktop.jpg` | `tips-tablet.jpg` | `tips-mobile.jpg` |
| Contact | `contact-desktop.jpg` | `contact-tablet.jpg` | `contact-mobile.jpg` |

## Notes

- The prices, numbers, quotes and contact details are sample content for the assignment.
- The Contact form and the newsletter form do not send messages yet (`action="#"`). Sending needs a server, which is outside this assignment.
- Photos were supplied by the project team.
