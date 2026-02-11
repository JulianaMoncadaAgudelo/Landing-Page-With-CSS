# Portfolio Landing Page

A modern, responsive portfolio landing page built with HTML and CSS. This project demonstrates front-end development skills including semantic HTML, custom CSS styling, responsive design principles, and CSS-only interactive components.

## Overview

This is a personal portfolio landing page designed to showcase professional information, skills, and provide contact options. The project emphasizes clean code, modern design patterns, and mobile-first responsive design without relying on JavaScript frameworks.

## Features

- **Responsive Design**: Fully responsive layout that adapts seamlessly to desktop, tablet, and mobile devices
- **Fixed Navigation Header**: Persistent navigation bar for easy access across the page
- **CSS-Only Mobile Menu**: Interactive hamburger menu implemented using pure CSS (checkbox hack technique)
- **Gradient Background**: Modern gradient design with custom color palette
- **Interactive Elements**: Smooth hover effects and transitions on buttons, images, and links
- **Social Media Integration**: Quick access icons for LinkedIn, GitHub, and email contact
- **Cross-browser Compatible**: Works across modern web browsers
- **Performance Optimized**: Lightweight design with minimal external dependencies

## Tech Stack

- **HTML5**: Semantic markup for structure and accessibility
- **CSS3**: Custom styling with advanced features including:
  - Flexbox and CSS Grid for layout
  - Media queries for responsive design
  - CSS transitions and transforms
  - Custom properties and gradients
- **External Libraries**:
  - [Boxicons](https://boxicons.com/) - Icon library
  - [Remix Icon](https://remixicon.com/) - Additional icon set
  - [Google Fonts](https://fonts.google.com/) - Roboto font family

## Installation and Setup

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- A local web server (optional, for best practices)

### Steps

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Landing-Page-With-CSS.git
```

2. Navigate to the project directory:
```bash
cd Landing-Page-With-CSS
```

3. Ensure your project structure looks like this:
```
Landing-Page-With-CSS/
├── index.html
├── style.css
├── assets/
│   └── img/
│       └── Juli.jpeg
└── README.md
```

4. Add your profile image to the `assets/img/` directory (or update the image path in `index.html`).

## How to Run the Project

### Method 1: Direct File Opening
Simply open the `index.html` file in your web browser by double-clicking it or right-clicking and selecting "Open with" your preferred browser.

### Method 2: Using a Local Server (Recommended)

Using a local server prevents potential CORS issues and simulates a real hosting environment.

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
```

**Using VS Code:**
Install the "Live Server" extension and right-click on `index.html` to select "Open with Live Server".

Then navigate to `http://localhost:8000` in your browser.

## Usage Example

This project serves as a template for creating a personal portfolio landing page. You can customize it by:

1. **Updating Personal Information**: Edit the text content in `index.html` to reflect your own name, title, and bio.

2. **Changing Colors**: Modify the color scheme in `style.css`:
```css
/* Background gradient */
background: linear-gradient(245.59deg, #31494e 0%, #385e70 25%, #131313 75%);

/* Button colors */
background-color: #4d4d4d;
```

3. **Adding Sections**: Extend the page with additional sections like projects, skills, or experience by adding new HTML sections and corresponding CSS.

4. **Linking Social Media**: Update the social media links in the icons section:
```html
<a href="your-linkedin-url"><i class="ri-linkedin-line"></i></a>
<a href="your-github-url"><i class="ri-github-line"></i></a>
```

## Project Structure

```
.
├── index.html          # Main HTML file with page structure
├── style.css           # Complete styling and responsive design
├── assets/             # Static assets directory
│   └── img/           # Image files
│       └── Juli.jpeg  # Profile photo
└── README.md          # Project documentation
```

### Key Code Components

- **Header**: Fixed navigation bar with responsive mobile menu
- **Hero Section**: Two-column layout featuring introduction text and profile image
- **Icons Section**: Social media links positioned on the left side
- **Scroll Indicator**: Bottom-right scroll-down button for user guidance

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Improvements

- Add About Me section with detailed background information
- Implement Portfolio section to showcase completed projects
- Create Contact form with form validation
- Add dark/light theme toggle feature
- Integrate JavaScript for enhanced animations and interactivity
- Implement smooth scroll behavior for navigation links
- Add SEO optimization with meta tags and structured data
- Include accessibility improvements (ARIA labels, keyboard navigation)
- Create additional pages (Projects, Blog, Contact)
- Add loading animations and page transitions
- Implement lazy loading for images
- Add analytics integration for visitor tracking

## License

This project is open source and available for educational and personal use.

## Contact

For questions or feedback, feel free to reach out through the social media links on the landing page.

---

**Note**: This project was created as part of a web design course at Digital House, demonstrating fundamental front-end development skills suitable for junior developer positions.
