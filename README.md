# MERN Stack Developer Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript for MERN stack developers. This portfolio showcases your skills, projects, and provides a professional way to connect with potential clients or employers.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Scroll Animations**: Elements animate as they come into view
- **Professional Sections**: Hero, About, Skills, Projects, and Contact sections

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Email**: Update the email address in the contact section
- **Phone**: Update the phone number
- **Location**: Update your city and country
- **Social Links**: Update the social media links with your profiles

### 2. About Section

Modify the about section content in `index.html`:
- Update the description paragraphs
- Adjust the statistics (years of experience, projects completed, etc.)

### 3. Skills Section

The skills are organized into three categories:
- **Frontend**: React.js, JavaScript, HTML5, CSS3
- **Backend**: Node.js, Express.js, MongoDB, REST APIs
- **Tools & Others**: Git, GitHub, AWS, Docker

You can add or remove skills by editing the skill items in the HTML.

### 4. Projects Section

Update the project cards with your actual projects:
- **Project Title**: Change the project names
- **Description**: Update project descriptions
- **Technologies**: Modify the technology tags
- **Links**: Add actual links to your live projects and GitHub repositories

### 5. Styling Customization

In `styles.css`, you can customize:
- **Colors**: Update the color scheme by changing CSS variables
- **Fonts**: Modify the font family (currently using Poppins)
- **Layout**: Adjust spacing, padding, and margins
- **Animations**: Modify animation durations and effects

### 6. Contact Form

The contact form includes:
- Form validation
- Success/error notifications
- Email format validation

To make it functional, you'll need to:
1. Set up a backend service (Node.js/Express)
2. Configure email sending (Nodemailer, SendGrid, etc.)
3. Update the form submission handler in `script.js`

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: ES6+ features and modern APIs
- **Font Awesome**: Icons
- **Google Fonts**: Poppins font family

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- **Optimized Images**: Use WebP format when possible
- **Minified CSS/JS**: For production deployment
- **Lazy Loading**: For images (can be implemented)
- **Smooth Animations**: Hardware-accelerated CSS transitions

## Deployment

### Option 1: GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch and deploy

### Option 2: Netlify
1. Drag and drop your folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on push

### Option 3: Vercel
1. Install Vercel CLI
2. Run `vercel` in your project directory
3. Follow the prompts

## SEO Optimization

To improve SEO, consider:
1. Adding meta tags for social sharing
2. Including structured data (JSON-LD)
3. Optimizing images with alt tags
4. Adding a sitemap
5. Setting up Google Analytics

## Accessibility

The portfolio includes:
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- Screen reader compatibility

## Future Enhancements

Potential improvements:
- **Dark Mode**: Add theme toggle
- **Blog Section**: Add a blog to showcase your thoughts
- **Resume Download**: Add downloadable resume
- **Testimonials**: Add client testimonials
- **Portfolio Gallery**: Add more project images
- **Blog Integration**: Connect to a headless CMS

## Support

If you need help customizing this portfolio:
1. Check the HTML comments for guidance
2. Review the CSS structure for styling changes
3. Examine the JavaScript for functionality modifications

## License

This project is open source and available under the MIT License.

---

**Happy Coding! 🚀**

Feel free to modify this portfolio to match your personal brand and showcase your unique skills and projects. 