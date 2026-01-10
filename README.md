# Portfolio Website

A clean and modern portfolio website built with vanilla HTML, CSS, and JavaScript. This responsive portfolio showcases your professional information, experience, projects, and contact details.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Smooth scrolling between sections with a hamburger menu for mobile
- **Professional Sections**:
  - Profile/Introduction section with social links
  - About section with experience and education
  - Experience section showcasing skills and technologies
  - Projects section to display your work
  - Contact section with email and social media links
- **Interactive Elements**: Hover effects, smooth transitions, and mobile-friendly hamburger menu

## Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: Modern styling with flexbox and responsive design
- **JavaScript**: Interactive functionality for mobile menu
- **Google Fonts**: Poppins font family

## Project Structure

```
Portfolio-Basic/
├── assets/
│   ├── arrow.png
│   ├── checkmark.png
│   ├── education.png
│   ├── email.png
│   ├── experience.png
│   ├── github.png
│   ├── linkedin.png
│   ├── profile-pic.png
│   ├── project-1.png
│   ├── project-2.png
│   ├── project-3.png
│   └── resume-example.pdf
├── index.html
├── style.css
├── media.css
├── script.js
└── README.md
```

## Getting Started

### Prerequisites

No dependencies or build tools required! Just a modern web browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process needed.

### Local Development

You can use any local server to run the project:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server
```

**Using VS Code:**
- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

Then navigate to `http://localhost:8000` (or the port shown) in your browser.

## Customization

### Personal Information

1. **Profile Section** (`index.html` lines 40-57):
   - Update name, title, and profile picture
   - Replace `profile-pic.png` in the `assets` folder
   - Update resume PDF path
   - Update social media links (LinkedIn, GitHub)

2. **About Section** (`index.html` lines 59-85):
   - Update experience years and description
   - Update education details
   - Replace `about-pic.png`
   - Modify the about text

3. **Experience Section** (`index.html` lines 87-213):
   - Update skills and proficiency levels
   - Add or remove skill categories
   - Modify technologies listed

4. **Projects Section** (`index.html` lines 215-250):
   - Replace project images in the `assets` folder
   - Update project titles
   - Add GitHub or live demo links

5. **Contact Section** (`index.html` lines 252-265):
   - Update email address
   - Update social media links

### Styling

- **Colors**: Modify CSS variables or color values in `style.css`
- **Fonts**: Change the Google Fonts import in `style.css` (line 2)
- **Layout**: Adjust spacing, sizing, and layout in `style.css` and `media.css`

### Images

Replace the placeholder images in the `assets` folder:
- `profile-pic.png`: Your profile picture
- `about-pic.png`: About section image
- `project-1.png`, `project-2.png`, `project-3.png`: Your project screenshots
- `resume-example.pdf`: Your resume/CV

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal and commercial use. Feel free to customize it for your own portfolio!

## Contributing

Feel free to fork this project and customize it for your needs. If you have suggestions for improvements, pull requests are welcome!

## Contact

For questions or support, please open an issue in the repository.

---

**Note**: Remember to update all placeholder content, links, and images with your own information before deploying!

