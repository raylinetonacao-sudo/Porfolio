# Porfolio
☕ Raei's Coffee — Portfolio & Café Website

A cute, cozy, and responsive coffee shop website for Raei's Coffee, featuring a soft purple aesthetic, handcrafted coffee branding, menu showcase, café story, gallery, reservations, contact information, and dark mode.

✨ Features

🎨 Cute purple café aesthetic with a cozy, modern design

📱 Fully responsive layout for desktop, tablet, and mobile

🌙 Dark mode with theme preference saved in localStorage

☕ Hero section with café branding and call-to-action buttons

🌸 Café experience section highlighting the shop's atmosphere

📖 About / Our Story section

🧁 Menu section with drinks, pastries, descriptions, and prices

🖼️ Gallery section for showcasing café moments

📅 Reservation form with:

Name

Email

Date

Time

Number of guests

Occasion

Special requests

🔔 Reservation confirmation toast

📍 Contact and opening-hours section

📲 Mobile navigation menu

⚡ Built with plain HTML, CSS, and JavaScript — no frameworks required

🛠️ Technologies

HTML5 — page structure and semantic content

CSS3 — styling, responsive layouts, animations, themes, and gradients

JavaScript — interactivity, dark mode, navigation, and reservation form handling

LocalStorage — remembers the user's selected theme

📁 Project Structure
raeis-coffee/
│
├── index.html
└── README.md


The entire website is currently contained in index.html, including the CSS and JavaScript.

🚀 Getting Started
1. Clone or download the project

Download the project files or clone the repository:

git clone <your-repository-url>

2. Open the project

Navigate into the project directory:

cd raeis-coffee

3. Run the website

Because this is a static HTML website, no build process or package installation is required.

Simply open:

index.html


in your browser.

For a better development experience, you can also use a local development server such as VS Code's Live Server extension.

🎨 Customization
Café Information

Update the placeholder information in the Visit Us section:

<p>Add your café address here.</p>


You can replace it with your actual café address.

Opening Hours

Modify the opening hours inside the contact section:

<p>
  Mon–Fri: 8 AM–8 PM<br>
  Sat–Sun: 9 AM–9 PM
</p>

Contact Details

Replace the sample email and phone number:

<p>
  hello@raeiscoffee.com<br>
  +63 900 000 0000
</p>

Menu

The menu items and prices can be edited directly in the HTML.

Example:

<div class="menu-item">
  <div>
    <strong>Raei's Signature Latte</strong><br>
    <small>Velvety espresso, steamed milk & house sweetness</small>
  </div>
  <strong class="price">₱165</strong>
</div>

📅 Reservations

The current reservation form is a front-end demonstration.

When submitted, it displays a confirmation message:

Reservation request received! ✨

No reservation data is currently sent to a server or booking platform.

To make reservations functional, the form can later be connected to:

A custom backend

Google Forms

A booking platform

Firebase

Supabase

An email service

A restaurant reservation API

🌙 Dark Mode

The website includes a light and dark theme.

The selected theme is saved using:

localStorage.setItem('raeis-theme', ...)


This allows the user's theme preference to remain after refreshing the page.

📱 Responsive Design

The website adapts to smaller screens using CSS media queries.

On mobile devices:

Desktop navigation becomes a menu button

Multi-column layouts become single-column layouts

The hero illustration moves above the text

Forms become easier to use on narrow screens

Gallery and feature cards stack vertically

🔮 Possible Future Improvements

Some ideas for expanding the project:

 Add real café photography

 Connect the reservation form to a backend

 Add real-time table availability

 Add an online ordering system

 Add menu categories and filtering

 Add customer reviews

 Add Google Maps integration

 Add Instagram feed integration

 Add animated page transitions

 Add accessibility improvements

 Add SEO and Open Graph metadata

 Deploy the website online

📄 License

This project is available for personal and educational use. Customize the content, branding, menu, and contact information as needed for your café or portfolio.

☕ Raei's Coffee

Sip • Smile • Stay Awhile

Made with coffee & a little bit of magic. 💜
