Portfolio Website - Assignment 1 (HTML5 and CSS3)

Overview

This project is a personal porfolio website built using semantic HTML5 and CSS3.

 It is my web and script assignment to demonstrate:
 - Understanding of HTML page structure
 - Use of CSS for layout and responsive design
 - Application of gradients (linear and angled)
 - Implementation of a consistent color scheme
 - Responsiveness across different screen sizes

 This website includes the following pages:
 - Home – Introduction and hero section
 - About Me – Biography, photo, and introductory video
 - Projects – Portfolio items displayed in a grid layout
 - Contact – Contact form with validation attributes

Viewpoint Dimensions

This projects consists of three breakpoints with seperate stylesheets linked with <link> tags:
- Desktop/Laptop (full.css) - min-width: 960px
- Tablet (tablet.css) - min-width: 481px and max-width: 959px
- Phone (phone.css) - max-width: 480px
These dimensions were selected because they align with common industry standards, ensuring the site is accessible and functional across a variety of devices.

Color Scheme

I used a calm and professional blue-themed palette because it's accessible and easy-to-read, while also looking visually clean and modern.
Primary Colors:
- Navy - used for navigation links and accents
- Lightblue - used in gradients and header/footer backgrounds
- Lightcyan - used as a complementary gradient color
Neutrals:
- White - used for main content backgrounds
- Whitesmoke - used for project card backgrounds
- Black - used for body text for maximum readability


Features

- Responsive Navigation: Highlighted active links and hover states
- Hero Section: Introduction with hero image and welcome text
- About Section: Bio, profile photo, and 45–60s intro video
- Projects Section: 5 project cards, organized into a grid layout
- Contact Form: Includes validation (required, type="email", pattern for phone)
- Consistent Styling: Separate CSS files for each breakpoint, gradients applied, named colors only


Validation & Testing

- All HTML validated using the W3C Markup Validation Service.
- All CSS validated using the W3C CSS Validator.
- Site tested across three viewport ranges (desktop, tablet, phone).
- Navigation and links tested across all four pages.
- Form validation confirmed for required fields and email format.

Notes

The validator flagged the mailto: link as inaccessible, but this is expected behavior since link checkers cannot open email clients.
