# Physics Tutoring Website

A professional, responsive website for advertising physics tutoring services. Features a modern design with sections for personal details, experience, testimonials, and a contact form.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Professional Layout**: Clean, modern design with smooth animations
- **Contact Form**: Interactive contact form with validation
- **Sections Included**:
  - Hero section with call-to-action
  - About section with personal details
  - Experience timeline
  - Testimonials from students
  - Contact form and information

## Setup

1. Clone or download this repository
2. Open `index.html` in a web browser
   - For local development, you can use a simple HTTP server:
     ```bash
     # Using Python 3
     python3 -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```
3. Navigate to `http://localhost:8000` in your browser

## Customization

### Personal Information

Edit `index.html` to update:

- **About Section** (lines ~50-75): Update your education, specializations, and bio
- **Experience Section** (lines ~85-110): Add your work history and achievements
- **Testimonials** (lines ~120-145): Replace with real testimonials from your students
- **Contact Information** (lines ~155-170): Update email, phone, location, and availability

### Styling

Edit `styles.css` to customize:

- **Colors**: Modify CSS variables in the `:root` section (lines ~8-15)
- **Fonts**: Change the `font-family` in the `body` selector
- **Layout**: Adjust spacing, sizes, and responsive breakpoints

### Contact Form

The contact form currently shows a success message when submitted. To actually send emails, you'll need to:

1. Set up a backend service (Node.js, Python Flask/Django, PHP, etc.)
2. Use an email service (SendGrid, Mailgun, Nodemailer, etc.)
3. Update the form submission handler in `script.js` (lines ~50-85)

Alternatively, you can use services like Formspree or Netlify Forms for a quick solution without backend code.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Feel free to use this template for your tutoring business!
