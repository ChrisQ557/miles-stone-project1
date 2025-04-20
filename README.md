# milestone-project1

# ♟️ Chess Club Website

Welcome to the Chess Club Website — a modern, responsive site built for chess enthusiasts to connect, participate, and grow their skills. This project showcases a fictional chess club and includes interactive features such as session booking and membership sign-up.

---

## 🌟 Overview

This website serves as a hub for a chess club community. Visitors can:

- Discover club activities through a photo carousel
- Join the club via an online form
- Book sessions (e.g., lessons, tournaments, events)
- Learn about the club and its community vibe

It is fully responsive and built with accessibility and simplicity in mind.

---

## 🎯 Intended Users

- **New or potential members** looking to join the club
- **Current members** who want to book activities or stay up to date
- **Event organizers** managing registrations
- **General visitors** curious about the club’s activities and culture

---

## 🧱 Features

- 🎨 Custom responsive design with Bootstrap 5
- 📷 Carousel showcasing “Club Moments”
- 📝 Join form to collect member interest
- 📅 Booking form with datetime selection
- 📱 Mobile-friendly navigation bar
- 🧭 Clear navigation across all pages
- 🎯 Accessible design and semantic HTML
- 🖼️ Background image integration and dynamic layout
- 📂 Clean project structure for scalability

---

## 📁 Folder Structure


```
📁 mile-stone-project1/
├── 📂 assets/
│   ├── 📂 css/
│   │   └── style.css
│   ├── 📂 images/
│   │   └── [all image files]
│   |   └── 📂 favicon/
│           └── [favicon files]
├── 📄 book.html
├── 📄 index.html
├── 📄 join.html
└── 📄 README.md

```

---

## 💡 Pages Breakdown

## `index.html`

### 1. 🧠 Head Section (`<head>`)
- Meta tags:
  - UTF-8 charset
  - Responsive viewport
- Page Title: **Chess Club**
- Styles & Fonts:
  - Bootstrap 5 CSS
  - Google Fonts (Lora, Open Sans)
  - Custom Stylesheet (`styles.css`)
- Bootstrap JS bundle (included at bottom)

---

### 2. 🧭 Navigation Bar (`<nav>`)
- Sticky-top, responsive Bootstrap navbar
- Logo: “Chess Club”
- Navigation links:
  - Home
  - About
  - Services
  - Community
  - Tournaments
  - Contact

---

### 3. 🏁 Hero Section (`#hero`)
- Centered hero message
- Elements:
  - Main heading: “Welcome to Our Chess Club”
  - Supporting paragraph
  - Two buttons:
    - ✅ Book Now → `book.html`
    - ♟️ Join the Club → `join.html`

---

### 4. 📘 About Us Section (`#about`)
- Two-column layout (text + image)
- Elements:
  - Heading: “About Our Chess Club”
  - Short paragraph
  - Image of players / chess scene

---

### 5. 🎯 Services Section (`#services`)
- 3 responsive Bootstrap cards
- Services offered:
  - ♟️ Lessons
  - 🏆 Tournaments
  - 🤝 Community
- Each card has:
  - Icon
  - Heading
  - Brief description

---

### 6. 🧑‍🤝‍🧑 Community Section (`#community`)
- Layout: Image + text
- Includes:
  - Heading: “A Club for Everyone”
  - Paragraph description
  - CTA button: “Join Now” → `join.html`

---

### 7. 💬 Testimonials / Carousel (`#carouselExampleIndicators`)
- Bootstrap Carousel with indicators
- Each slide includes:
  - Testimonial quote
  - Person's name (e.g., "— Sarah M.")

---

### 8. ♟️ Tournaments Section (`#tournaments`)
- 3 tournament cards:
  - Each with:
    - Title (e.g., “Spring Blitz 2025”)
    - Date
    - Short description

---

### 9. 📬 Contact Section (`#contact`)
- Two-column layout:
  - Left: Contact form
    - Name
    - Email
    - Message
    - Send button
  - Right: Embedded Google Map (club location)

---

### 10. 🦶 Footer
- Simple centered footer
- Content:
  - “© 2025 Chess Club. All rights reserved.”

---

## `book.html`

### 1. 🧠 Head Section (`<head>`)
- Meta configuration:
  - Charset: UTF-8
  - Responsive viewport
  - SEO tags:
    - `description`: What the Chess Club offers
    - `keywords`: Chess-related terms
    - `author`: Chess Club Team
- Title: **CHESS CLUB | BOOK**
- Favicons via `favicon.io`
- Bootstrap 5 CSS
- Custom stylesheet: `assets/css/style.css`

---

### 2. 🧭 Header & Navbar (`<header><nav>`)
- **Navbar Contents**:
  - Brand logo + “CHESS CLUB” text
  - Mobile toggler
  - Navigation Links:
    - Home → `index.html`
    - **Book** → `book.html` (active)
    - Join → `join.html`

---

### 3. 📆 Booking Section (`<section class="booking-section">`)
- Centered heading:
  - Title: “Book a Session”
  - Subtitle: Booking prompt
- **Booking Form**:
  - Name (`<input type="text">`)
  - Email (`<input type="email">`)
  - Booking Type (`<select>`)
    - Options: Private Lesson, Group Class, Tournament Entry, Facility Booking
  - Date & Time (`<input type="datetime-local">`)
  - Additional Notes (`<textarea>`)
  - Submit button: “Submit Booking”

---

### 4. 🦶 Footer (`<footer>`)
- Dark background with white text
- Social icons (Font Awesome):
  - Facebook
  - Instagram
  - Twitter
- Copyright:
  - “© 2025 Chess Club. All rights reserved.”

---

### 5. ⚙️ Scripts
- Bootstrap Bundle JS (CDN)
- Font Awesome Kit (for icons)

---

## `join.html`

### 1. 🧠 Head Section (`<head>`)
- Meta setup:
  - Charset: UTF-8
  - Viewport: responsive
  - SEO Tags:
    - `description`: summary of the page's purpose
    - `keywords`: chess-related terms
    - `author`: Chess Club Team
- Title: **CHESS CLUB | JOIN**
- Favicons from `favicon.io`
- Bootstrap 5 CSS
- Custom CSS (`style.css`)

---

### 2. 🧭 Header & Navbar (`<header><nav>`)
- **Navbar** includes:
  - Logo image + title: “CHESS CLUB”
  - Mobile-friendly toggler
  - Links:
    - Home → `index.html`
    - Book → `book.html`
    - **Join** → `join.html` (active)

---

### 3. 📝 Join Form Section (`<section class="join-section">`)
- Centered content with dark background & white text
- Heading: “Join the Chess Club”
- Subheading: form prompt

### 🧾 Form Fields
- Full Name (`<input type="text">`)
- Email Address (`<input type="email">`)
- "Why do you want to join?" (`<textarea>`)
- Membership Type (`<select>`)
  - Options: Regular, Student, Family
- Submit Button: “Submit Application”

---

### 4. 🦶 Footer (`<footer>`)
- Dark background, white text
- Social media icons (using Font Awesome):
  - Facebook
  - Instagram
  - Twitter
- Copyright:
  - “© 2025 Chess Club. All rights reserved.”

---

### 5. ⚙️ Scripts
- Bootstrap JS Bundle
- Font Awesome Kit (for social icons)

---

## 🧰 Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- Responsive Design principles
- Fonts used: Google fonts "Roboto", sans-serif, and "Lora",  serif.
  

---

## 🌐 How to Use

1. **Clone or download the project**
   ```bash
   git clone https://github.com/miles-stone-project1

Navigate to the folder and open index.html in your browser
No build step or dependencies needed — it's pure HTML/CSS with Bootstrap CDN.

---

🎨 Customization
You can easily adapt this template for:

Real local chess clubs

Other community or hobby groups

Event-based organizations needing a simple web presence

To update content:

Modify text in .html files

Update images in assets/images/

Customize layout/colors in assets/css/style.css

---

📬 Contact

Built with care by Christopher Quinones.

Want to collaborate, suggest features, or report bugs? Open an issue or contact via email.

[E-mail](mailto:517996@waes.ac.uk)

---

🙌 Acknowledgements

- Bootstrap 5

- favicon.io

- pexels.com and unsplush.com for demo images




