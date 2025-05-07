# David Llamas - Developer Portfolio

This repository contains the personal portfolio site of **David Llamas**, a software engineer and full-stack web developer. The template is a lightweight, fully responsive design built using HTML, Sass, JavaScript, and Bootstrap, with Font Awesome support.

It follows a modular layout with clear sections for showcasing experience, education, projects, and contact information. This template is ideal for developers looking to create a professional and visually appealing personal site.

To view the live version, host the site locally or deploy via GitHub Pages or a preferred hosting service.

---

## Features

- Fully responsive mobile-friendly design
- Sass-powered with easily customizable variables
- Built with Bootstrap grid
- Font Awesome integration for icons
- Modular structure for easy content replacement

---

## Sections Included

- **Header Navigation**: Links to all major sections
- **Lead Section**: Highlights name, role, university, and includes resume download
- **About Me**: Personal summary of background, education, and professional values
- **Experience**: Timeline showcasing professional roles
- **Education**: Academic history with degrees earned
- **Projects**: Descriptions and images for key projects
- **Skills**: Tech stack and proficiencies
- **Contact**: Form to send messages directly
- **Footer**: Social media links and copyright

---

## Instructions

### Editing the Template

1. Clone or download the repo
2. Customize content in `index.html`
3. Update colors and spacing in `sass/styles.scss`
4. Use `npm install` to get dependencies if using Gulp for compilation
5. Run `gulp watch` or `npm run watch` to compile Sass and JS

### Using Without Gulp

If you don’t want to customize the Sass or JS:
- You can simply edit the `index.html`
- Make sure the `css`, `js`, `images`, and `libs` folders are preserved

---

## Sample Project Entry

```html
<div class="project">
  <div class="project-image">
    <img src="images/warehouse.png" />
  </div>
  <div class="project-info">
    <h3>Warehouse Inventory Tracker</h3>
    <ul>
      <li>Built a full-stack inventory management app for warehouse tracking and logistics optimization.</li>
      <li>Used phpMyAdmin for data storage with MySQL to track items, quantities, and restocking status.</li>
      <li>Developed backend with Express.js and Node.js, following a Models, Views, Controllers (MVC) structure.</li>
      <li>Built a dynamic frontend using React.js for real-time inventory updates and user interaction.</li>
      <li><strong>Tech Stack:</strong> MySQL, Express.js, Node.js, React.js, phpMyAdmin</li>
    </ul>
    <a href="#">View Project</a>
  </div>
</div>
```

---

## Contact Setup

This site uses [Formspree](https://formspree.io/) for the contact form. Update the email in the form's `action` attribute to:

```html
<form method="POST" action="https://formspree.io/f/mlevnjvp">
```

To have messages sent to your inbox, configure the Formspree account with your address.

---

## License

© 2025 David Llamas
