# ♟️ Chess Club Website

Welcome to the **Chess Club Website** — a modern, responsive site built for chess enthusiasts to connect, participate, and grow their skills. This project showcases a fictional chess club and includes interactive features such as session booking and membership sign-up.

---

## 🌟 Overview

This website serves as a hub for a chess club community. Visitors can:

- Discover club activities through a photo carousel
- Join the club via an online form
- Book sessions (e.g., lessons, tournaments, events)
- Learn about the club and its community vibe
- View services offered by the club
- Get in touch via a contact form and find the club location on a map

It is fully responsive and built with accessibility and simplicity in mind.

---

## 🎯 Intended Users

- **New or potential members** looking to join the club
- **Current members** who want to book activities or stay up to date
- **Event organizers** managing registrations
- **General visitors** curious about the club's activities and culture

---

## 📖 User Stories

### **Visitors**

The main demographic for the site is chess enthusiasts and potential members looking to learn about and engage with the club.

1. As a visitor, I would like to see what the club is about so I can decide if I want to join.
2. As a visitor, I would like to view club moments and photos so I can get a feel for the community atmosphere.
3. As a visitor, I would like to easily navigate between pages so I can find the information I need quickly.
4. As a visitor, I would like to view the club's services so I can understand what is offered (coaching, tournaments, workshops, etc.).
5. As a visitor, I would like to read about the club's strategy, lessons, community, and tournaments so I can see if it matches my interests.
6. As a visitor, I would like to find the club's address and opening hours so I can plan a visit.
7. As a visitor, I would like to see the club location on a map so I can easily find directions.
8. As a visitor, I would like to send a message via a contact form so I can ask questions or provide feedback.
9. As a visitor, I would like the site to be responsive so I can browse comfortably on my phone, tablet, or desktop.
10. As a visitor, I would like to access the club's social media links so I can follow them on Facebook, Instagram, or Twitter.

### **Members**

1. As a member, I would like to book a session (private lesson, group class, tournament entry, or facility booking) so I can reserve my spot.
2. As a member, I would like to select a preferred date and time for my booking so it fits my schedule.
3. As a member, I would like to add additional notes to my booking so I can communicate special requests.
4. As a member, I would like to join the club online by filling out a membership form so I can become part of the community.
5. As a member, I would like to select my age group when joining so the club can tailor activities to my level.
6. As a member, I would like to click the logo or club name from any page to return to the homepage so I can navigate easily.

### **Admin / Club Organisers**

1. As an admin, I would like to collect visitor names and emails through the contact form so I can respond to enquiries.
2. As an admin, I would like to collect booking details (name, email, type, date/time, notes) so I can manage session reservations.
3. As an admin, I would like to collect membership applications (name, email, age group, motivation) so I can process new members.
4. As an admin, I would like the site to present the club professionally so it attracts new members and builds trust.

---

## 🧱 Features

- 🎨 Custom responsive design with Bootstrap 5
- 📷 Carousel showcasing "Club Moments"
- 📝 Join form to collect member interest
- 📅 Booking form with datetime selection
- 📱 Mobile-friendly navigation bar
- 🧭 Clear navigation across all pages (HOME, BOOK, JOIN)
- 🎯 Accessible design and semantic HTML
- 🖼️ Hero image with call-to-action overlay
- 📍 Embedded Google Map showing club location
- 📬 Contact form for visitor enquiries
- 🔗 Clickable logo and brand name linking to homepage
- 📂 Clean project structure for scalability

---

## 📁 Folder Structure

```
📁 mile-stone-project1/
├── 📂 assets/
│   ├── 📂 css/
│   │   └── style.css
│   └── 📂 images/
│       ├── 📂 favicon/
│       │   └── [favicon files]
│       └── [all image files]
├── 📄 book.html
├── 📄 index.html
├── 📄 join.html
└── 📄 README.md
```

---

## 💡 Pages Breakdown

### `index.html` — Home Page

#### 1. 🧠 Head Section (`<head>`)
- Meta tags: UTF-8 charset, responsive viewport, SEO description/keywords/author
- Page Title: **CHESS CLUB | HOME**
- Styles: Bootstrap 5 CSS (CDN), custom stylesheet (`assets/css/style.css`)
- Favicons via favicon.io

#### 2. 🧭 Header & Navbar (`<header><nav>`)
- Responsive Bootstrap navbar with mobile toggler
- Left-aligned brand: clickable logo image + "CHESS CLUB" text (both link to `index.html`)
- Navigation links: HOME (active), BOOK, JOIN

#### 3. 🏁 Hero Section
- Full-width hero image with centered white text overlay
- Heading: "MASTER YOUR GAME"

#### 4. 📢 Call-to-Action Section (`#cta`)
- Dark background with white text
- Heading: "Ready to Take Your Game to the Next Level?"
- Two buttons: "Book Now" → `book.html`, "Join the Club" → `join.html`

#### 5. 📘 About Us Section
- Centered text section
- Heading: "About Us"
- Paragraph introducing the club and its mission

#### 6. 🧩 Grid Section (Strategy, Lessons, Community, Tournaments)
- 4-column responsive grid (collapses on smaller screens)
- Each card includes an image, heading, description, and an ordered list of highlights

#### 7. 📷 Carousel — Club Moments
- Bootstrap carousel with 5 slides of club activity photos
- Previous/Next navigation controls

#### 8. 🎯 Services Section (`#services`)
- 3 service cards: 1-on-1 Coaching, Online Tournaments, Workshops & Seminars
- 1 additional card: Coffee Shop with detailed list
- Each card has a Font Awesome icon, heading, and description

#### 9. 📬 Contact Section (`#contact`)
- Contact form: Name, Email, Message, Send button
- Address card with: club address, embedded Google Map, opening hours, email, and phone

#### 10. 🦶 Footer
- Dark background, white text
- Social media links: Facebook, Instagram, Twitter (Font Awesome icons)
- Copyright: "© 2025 Chess Club. All rights reserved."

---

### `book.html` — Book a Session

#### 1. 🧠 Head Section (`<head>`)
- Same meta/favicon/Bootstrap/CSS setup as index.html
- Page Title: **CHESS CLUB | BOOK**

#### 2. 🧭 Header & Navbar
- Same navbar structure; BOOK link is active

#### 3. 📆 Booking Section
- Background image with dark overlay form
- Heading: "Book a Session"
- Subtitle: "Reserve your spot for lessons, tournaments, or events!"
- Form fields:
  - Your Name (`text`)
  - Email Address (`email`)
  - Booking Type (`select`): Private Lesson, Group Class, Tournament Entry, Facility Booking
  - Preferred Date & Time (`datetime-local`)
  - Additional Notes (`textarea`)
  - Submit button: "Submit Booking"

#### 4. 🦶 Footer
- Same as index.html footer

---

### `join.html` — Join the Club

#### 1. 🧠 Head Section (`<head>`)
- Same meta/favicon/Bootstrap/CSS setup as index.html
- Page Title: **CHESS CLUB | JOIN**

#### 2. 🧭 Header & Navbar
- Same navbar structure; JOIN link is active

#### 3. 📝 Join Section
- Background image with dark overlay form (right-aligned)
- Heading: "Join the Club"
- Subtitle: "Become part of our chess-loving community!"
- Form fields:
  - Full Name (`text`)
  - Email Address (`email`)
  - Age Group (`select`): Under 12, 13–17, 18–30, 30+
  - Tell Us About Yourself (`textarea`)
  - Submit button: "Join Now"

#### 4. 🦶 Footer
- Same as index.html footer

---

## 🧰 Technologies Used

- **HTML5** — Semantic markup and page structure
- **CSS3** — Custom styling and layout
- **Bootstrap 5** — Responsive grid, components, and utilities
- **Font Awesome** — Social media and service icons
- **Google Fonts** — "Roboto" (sans-serif) and "Lora" (serif)
- **Google Maps Embed** — Club location map

---

## 🌐 How to Use

1. **Clone or download the project**
   ```bash
   git clone https://github.com/ChrisQ557/miles-stone-project1.git
   ```

2. Navigate to the folder and open `index.html` in your browser.

3. No build step or dependencies needed — it's pure HTML/CSS with Bootstrap CDN.

---

## 🎨 Customisation

You can easily adapt this template for:

- Real local chess clubs
- Other community or hobby groups
- Event-based organisations needing a simple web presence

To update content:

- Modify text in `.html` files
- Update images in `assets/images/`
- Customise layout/colours in `assets/css/style.css`

---

## 📬 Contact

Built with care by **Christopher Quinones**.

Want to collaborate, suggest features, or report bugs? Open an issue or contact via email.

[517996@waes.ac.uk](mailto:517996@waes.ac.uk)

---

## 🙌 Acknowledgements

- [Bootstrap 5](https://getbootstrap.com/)
- [favicon.io](https://favicon.io/)
- [Font Awesome](https://fontawesome.com/)
- [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/) for demo images
- [Google Fonts](https://fonts.google.com/)
- [Google Maps](https://maps.google.com/) for embedded map
