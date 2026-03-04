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

## 👀 View the Project
- [View the deployed website](https://chrisq557.github.io/miles-stone-project1/)

---

## 👀 View the Project

- [View the deployed website](https://chrisq557.github.io/miles-stone-project1/)

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

## 🧪 Testing

### Manual Testing

The following tests were carried out manually across all pages of the Chess Club website to ensure functionality, usability, and responsiveness.

| **Test Group** | **Test Label** | **Action** | **Expected Outcome** | **Outcome** |
|---|---|---|---|---|
| **Navigation / UX** | Logo home link | From any page, click the Chess Club logo in the header. | The user will be taken back to the home page. | PASS |
| | Brand name home link | From any page, click the "CHESS CLUB" text in the header. | The user will be taken back to the home page. | PASS |
| | HOME nav link | From any page, click the HOME link in the navbar. | The user will be taken to the home page. | PASS |
| | BOOK nav link | From any page, click the BOOK link in the navbar. | The user will be taken to the booking page. | PASS |
| | JOIN nav link | From any page, click the JOIN link in the navbar. | The user will be taken to the join page. | PASS |
| | Active nav link highlight | Visit each page and check the active nav link. | The current page's nav link should be visually highlighted as active. | PASS |
| | Mobile navbar toggler | On a mobile viewport, click the hamburger menu icon. | The navigation links should expand/collapse. | PASS |
| | Responsive layout | Resize the browser window from desktop to mobile. | The layout should adapt responsively without breaking or horizontal scrolling. | PASS |
| **Home Page** | Hero section display | Visit the home page. | The hero image should display with the "MASTER YOUR GAME" heading centred over it. | PASS |
| | Book Now CTA button | From the home page, click the "Book Now" button in the CTA section. | The user will be taken to the booking page. | PASS |
| | Join the Club CTA button | From the home page, click the "Join the Club" button in the CTA section. | The user will be taken to the join page. | PASS |
| | Button hover effect | From the home page, hover over the CTA buttons. | The buttons should display a visible hover effect. | PASS |
| | About Us section | Scroll to the About Us section on the home page. | The section should display the club description text clearly. | PASS |
| | Grid section display | Scroll to the Strategy, Lessons, Community, and Tournaments grid. | All four cards should display with images, headings, descriptions, and ordered lists. | PASS |
| | Grid responsive layout | View the grid section on mobile, tablet, and desktop. | Cards should stack on mobile (1 column), display 2 columns on tablet, and 4 columns on desktop. | PASS |
| **Carousel** | Carousel auto-play | Visit the home page and observe the Club Moments carousel. | The carousel should automatically cycle through the 5 slides. | PASS |
| | Carousel next button | Click the next (right arrow) button on the carousel. | The carousel should advance to the next slide. | PASS |
| | Carousel previous button | Click the previous (left arrow) button on the carousel. | The carousel should go back to the previous slide. | PASS |
| | Carousel images display | View each slide in the carousel. | All 5 images should load and display correctly. | PASS |
| **Services** | Services section display | Scroll to the Our Services section on the home page. | The 1-on-1 Coaching, Online Tournaments, Workshops & Seminars, and Coffee Shop cards should display. | PASS |
| | Service icons display | View the services cards. | Each card should display its Font Awesome icon correctly. | PASS |
| **Contact** | Contact form display | Scroll to the Get in Touch section on the home page. | The contact form with Name, Email, and Message fields should be visible. | PASS |
| | Contact form required fields | Click "Send Message" without filling in any fields. | The user should be prompted to fill in the first required field. | PASS |
| | Contact form invalid email | Enter an invalid email (without @) and attempt to submit. | The browser should prompt the user to enter a valid email address. | PASS |
| | Contact form submit with valid data | Fill in all fields with valid data and click "Send Message". | The form should submit without errors. | PASS |
| | Google Map display | Scroll to the Visit Us section on the home page. | The embedded Google Map should load and display the club location. | PASS |
| | Address & opening hours | View the Visit Us card on the home page. | The club address, opening hours, email, and phone number should be displayed. | PASS |
| | Email link | Click the email address link in the contact section. | The user's default email client should open with the club email pre-filled. | PASS |
| | Phone link | Click the phone number link in the contact section. | The device should initiate or prompt a phone call to the club number. | PASS |
| **Booking Form** | Booking page display | Navigate to the Book page. | The booking form should display with all fields: Name, Email, Booking Type, Date & Time, and Notes. | PASS |
| | Booking type dropdown | Click the Booking Type dropdown on the Book page. | The options Private Lesson, Group Class, Tournament Entry, and Facility Booking should be shown. | PASS |
| | Date & time picker | Click the Preferred Date & Time field on the Book page. | A date and time picker should appear allowing the user to select a date and time. | PASS |
| | Submit with empty required fields | Click "Submit Booking" without filling in any fields. | The user should be prompted to fill in the first missing required field. | PASS |
| | Submit with missing name | Fill in all fields except Name and click "Submit Booking". | The user should be directed to fill in the Name field. | PASS |
| | Submit with missing email | Fill in all fields except Email and click "Submit Booking". | The user should be directed to fill in the Email field. | PASS |
| | Submit with invalid email | Enter an invalid email and attempt to submit the booking form. | The browser should prompt the user to enter a valid email address. | PASS |
| | Submit with missing booking type | Fill in all fields except Booking Type and click "Submit Booking". | The user should be directed to select a booking type. | PASS |
| | Submit with missing date/time | Fill in all fields except Date & Time and click "Submit Booking". | The user should be directed to fill in the date and time field. | PASS |
| | Submit without optional notes | Fill in all required fields, leave Notes empty, and click "Submit Booking". | The form should submit without any issues. | PASS |
| | Submit with all fields valid | Fill in all fields with valid data and click "Submit Booking". | The form should submit successfully. | PASS |
| **Join Form** | Join page display | Navigate to the Join page. | The join form should display with all fields: Full Name, Email, Age Group, and Tell Us About Yourself. | PASS |
| | Age group dropdown | Click the Age Group dropdown on the Join page. | The options Under 12, 13–17, 18–30, and 30+ should be shown. | PASS |
| | Submit with empty required fields | Click "Join Now" without filling in any fields. | The user should be prompted to fill in the first missing required field. | PASS |
| | Submit with missing name | Fill in all fields except Full Name and click "Join Now". | The user should be directed to fill in the Full Name field. | PASS |
| | Submit with missing email | Fill in all fields except Email and click "Join Now". | The user should be directed to fill in the Email field. | PASS |
| | Submit with invalid email | Enter an invalid email and attempt to submit the join form. | The browser should prompt the user to enter a valid email address. | PASS |
| | Submit with missing age group | Fill in all fields except Age Group and click "Join Now". | The user should be directed to select an age group. | PASS |
| | Submit without optional textarea | Fill in all required fields, leave "Tell Us About Yourself" empty, and click "Join Now". | The form should submit without any issues. | PASS |
| | Submit with all fields valid | Fill in all fields with valid data and click "Join Now". | The form should submit successfully. | PASS |
| **Footer** | Footer display | Scroll to the bottom of any page. | The footer should display with social media icons and copyright text. | PASS |
| | Facebook link | Click the Facebook icon in the footer. | A new tab/window should open to the Facebook website. | PASS |
| | Instagram link | Click the Instagram icon in the footer. | A new tab/window should open to the Instagram website. | PASS |
| | Twitter link | Click the Twitter icon in the footer. | A new tab/window should open to the Twitter website. | PASS |
| | Social links open in new tab | Click any social media icon in the footer. | The link should open in a new tab (target="_blank"). | PASS |
| | Copyright text | View the footer on any page. | The text "© 2025 Chess Club. All rights reserved." should be displayed. | PASS |
| **Browser Compatibility** | Chrome | Open the website in Google Chrome. | All pages should render correctly with full functionality. | PASS |
| | Firefox | Open the website in Mozilla Firefox. | All pages should render correctly with full functionality. | PASS |
| | Safari | Open the website in Safari. | All pages should render correctly with full functionality. | PASS |
| | Edge | Open the website in Microsoft Edge. | All pages should render correctly with full functionality. | PASS |

---

## 📬 Contact

Built with care by **Christopher Quinones**.

Want to collaborate, suggest features, or report bugs? Open an issue or contact via email.

[517996@waes.ac.uk](mailto:517996@waes.ac.uk)

---

## 🙌 Acknowledgements

<<<<<<< HEAD
---

## User Experience

### User Information

#### Typical Users
The main users of the site will be:
- Visitors (general public curious about the club)
- Prospective Members (people interested in joining)
- Current Members (people attending activities and booking sessions)
- Club Admins (organizers maintaining content and events)

#### User Stories

##### Visitors
1. As a visitor, I want to quickly understand what the club offers so I can decide if it matches my interests.
2. As a visitor, I want to browse photos and testimonials so I can get a feel for the club community.
3. As a visitor, I want clear navigation so I can easily find the Book and Join pages.
4. As a visitor on mobile, I want a responsive layout so I can comfortably view content on my phone.

##### Prospective Members
1. As a prospective member, I want to access a Join form so I can express interest in becoming a member.
2. As a prospective member, I want to understand membership options so I can choose the one that fits me.
3. As a prospective member, I want reassurance about how my details are used so I feel comfortable submitting the form.

##### Current Members
1. As a current member, I want to book sessions (lessons, tournaments, events) so I can plan my participation.
2. As a current member, I want available dates and times to be clear so I can schedule without confusion.
3. As a current member, I want to provide notes (e.g., preferences) in the booking form so organizers can prepare.

##### Club Admins
1. As a club admin, I want the site structure to be simple so I can update content (text/images) without complex tooling.
2. As a club admin, I want clear navigation labels so new visitors can find key actions (Book, Join) without support.
3. As a club admin, I want consistent styling across pages so the club brand looks professional.

---

## 🚀 Deployment

### Local Setup

#### Prerequisites
- A code editor (e.g., VS Code, Sublime Text)
- A web browser (Chrome, Firefox, Safari, etc.)
- Git (for version control and cloning the repository)

#### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/mile-stone-project1.git
   cd mile-stone-project1
   ```

2. **Open the Project**
   - Open the project folder in your code editor
   - Alternatively, navigate to the project directory in your terminal

3. **Start a Local Server**
   - Using Python (recommended for simplicity):
     ```bash
     # Python 3.x
     python -m http.server 8000
     # Or Python 2.x
     python -m SimpleHTTPServer 8000
     ```
   - Using Node.js (if installed):
     ```bash
     npx http-server
     ```

4. **Access the Website**
   - Open your web browser and navigate to:
     - `http://localhost:8000` (for Python)
     - `http://localhost:8080` (for Node.js)
   - You should now see the Chess Club website

5. **Development**
   - Edit HTML files (`index.html`, `book.html`, `join.html`)
   - Modify CSS styles in `assets/css/style.css`
   - Add or update images in `assets/images/`
   - Refresh your browser to see changes

### GitHub Deployment

#### Steps to Deploy on GitHub

1. **Create a GitHub Repository**
   - Go to [GitHub.com](https://github.com) and sign in
   - Click the **+** icon and select **New repository**
   - Name it `mile-stone-project1` (or your preferred name)
   - Add an optional description
   - Choose **Public** for open-source or **Private** for restricted access
   - Click **Create repository**

2. **Initialize Git in Your Local Project** (if not already done)
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Chess Club Website"
   ```

3. **Add Remote Origin**
   ```bash
   git remote add origin https://github.com/yourusername/mile-stone-project1.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Choose the branch: **main** (or **master**)
   - Select the folder: **/ (root)**
   - Click **Save**
   - Your site will be available at: `https://yourusername.github.io/mile-stone-project1/`

5. **Verify Deployment**
   - Wait 1-2 minutes for GitHub Pages to build and deploy
   - Visit your GitHub Pages URL to confirm the site is live
   - Check the **Deployments** tab in your repository for status

#### Making Updates After Deployment

1. **Make local changes** to your HTML, CSS, or images
2. **Commit and push** your changes:
   ```bash
   git add .
   git commit -m "Update: [description of changes]"
   git push origin main
   ```
3. **GitHub Pages will automatically redeploy** within minutes

### Deployment Troubleshooting

- **Site not appearing on GitHub Pages?**
  - Ensure the repository is public (or Pages is enabled for private repos)
  - Check that the branch and folder settings are correct in Pages settings
  - Wait a few minutes and refresh your browser

- **Changes not reflecting?**
  - Clear your browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
  - Check the GitHub Actions tab for any build errors
  - Verify your commit was successfully pushed

---

## 🙌 Acknowledgements

- [Bootstrap 5](https://getbootstrap.com/)
- [favicon.io](https://favicon.io/)
- [Font Awesome](https://fontawesome.com/)
- [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/) for demo images
- [Google Fonts](https://fonts.google.com/)
- [Google Maps](https://maps.google.com/) for embedded map
