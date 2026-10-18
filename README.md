# BooQafé: Book-Themed Café 
Website A multi-section website for **BooQafé**, a fictional café where coffee meets books. Built with **HTML and CSS** (no frameworks, no JavaScript) as the midterm project for the **Web Development** course, Information Systems, Tarumanagara University, September to October 2025. 

**Live demo:** https://[username].github.io/booqafe-website/ 

![BooQafé home page](screenshots/home.png) 

## Pages and Sections 

**Home page** 
| Section | What it contains | 
|---|---| 
| Hero | Background image with dark overlay, headline, play button that opens a video modal, and an order form layout (coffee type, date, pickup time, size) | 
| Introduction | Café story with a "Come Visit Us!" card showing Drinks, Food, and Books | | Promo: *A Taste of Fiction* | Four promo cards that lift on hover | 
| Menu: *Flavors That Speak* | Six menu cards (beverages and food) with price, description, size, and serving options | 
| About: *Stories Over Coffee* | Café description and reservation button | 
| Testimonials | Three customer feedback cards | 
| *Sip. Read. Belong.* | Three experiences: Open Reading Space, Book & Coffee Subscription, Community & Event Space | 
| Banner and footer | Call to action, About, Information, Experience, and contact details | 

**Contact page** (`contact.html`): Contact page and auction site message submission 

## What I Practiced 
- Page layout with **Flexbox**, floats, and relative/absolute positioning
- Image overlays using the `::before` pseudo-element
- A play button triangle drawn with pure CSS borders
- A **video modal without JavaScript**, using the `:target` selector
- Hover effects with `transition` and `transform` (card lift, image zoom, sliding buttons)
- A fixed navigation bar with a box shadow
- A consistent visual identity: navy `#191970`, cream `#F5F5DC`, sienna `#A0522D`, slate `#708090`, with Georgia, Verdana, and Times New Roman

## Tech Stack 
HTML5 · CSS3

## Getting Started 
1. Clone the repository: ```bash git clone https://github.com/[username]/booqafe-website.git ```
2. Open `index.html` in your browser. No installation or build step is needed.

## Project Structure
booqafe/
├── index.html      # home page
├── contact.html    # contact page
├── BooQafe.css     # all styles
└── img/            # logo, promo, menu, and banner images

## Known Limitations and Planned Improvements 
- **Not responsive yet.** Many sizes use fixed pixel widths. Next step: add media queries and relative units.
- **Some elements are visual only:** the order form, the "Buy Now" and "Read More" buttons, and the carousel dots do not have any behavior yet. Next step: add JavaScript or connect them to real pages.
- **Some images are loaded from external sites** and may break if the source changes. Next step: host them locally.
- **Placeholder text** is still used in one section of the introduction card.

## Credits and Notes 
- BooQafé is a **fictional** café. Names, testimonials, address, phone number, and email are sample content.
- Some images in `img/` [logo, promo, background and menu visuals] were **generated with AI (ChatGPT)**. The page layout and styling were coded for this project.
- Other images and icons come from free-license sources [Unsplash, Pexels, Vecteezy] and belong to their respective owners.

## Author 
**Tracy Prycillia Kusmana**
