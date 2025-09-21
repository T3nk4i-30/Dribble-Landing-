# Dribbble Clone

A modern, responsive clone of the Dribbble platform built with HTML amd CSS. This project showcases a clean design portfolio website with smooth animations and interactive elements.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and minimalist design inspired by Dribbble
- **Smooth Animations**: CSS animations for image carousel and hover effects
- **Interactive Elements**: Hover effects on portfolio items and buttons
- **Professional Navigation**: Clean navigation bar with login/signup functionality
- **Portfolio Gallery**: Grid-based design showcase with hover overlays

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Advanced styling with Flexbox, animations, and responsive design
- **Google Fonts**: Poppins and PT Serif for typography
- **Remix Icons**: Icon library for UI elements
- **External Images**: High-quality images from Unsplash and Dribbble CDN

## 📁 Project Structure

```
Dribble_clone/
├── index.htm          # Main HTML file
├── style.css          # CSS styles and animations
├── index.js           # JavaScript functionality
└── README.md          # Project documentation
```

## 🎨 Design Features

### Page 1 - Hero Section
- **Navigation Bar**: Clean navigation with logo and menu items
- **Hero Content**: Compelling headline with call-to-action button
- **Animated Image Carousel**: Horizontal scrolling animation with portfolio previews

### Page 2 - Portfolio Gallery
- **Grid Layout**: Responsive grid of design showcases
- **Hover Effects**: Interactive overlays with like buttons and category tags
- **Smooth Transitions**: CSS transitions for enhanced user experience

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. Clone or download the repository:
```bash
git clone [repository-url]
cd Dribble_clone
```

2. Open the project in your browser:
   - Simply open `index.htm` in your web browser
   - Or use a local server for development

### Local Development Server (Optional)

If you want to run a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎯 Key Components

### Navigation
- **Find Talent**: Navigation menu for talent discovery
- **Inspiration**: Design inspiration section
- **Learn Design**: Educational resources
- **Jobs**: Job listings
- **Go Pro**: Premium features
- **Authentication**: Login and Sign Up buttons

### Hero Section
- Eye-catching headline about creative talent
- Call-to-action button for hiring
- Animated portfolio preview carousel

### Portfolio Gallery
- Responsive grid layout
- High-quality design showcases
- Interactive hover effects with like functionality
- Category tags for each design

## 🎨 Styling Details

### Color Scheme
- **Primary Background**: #F8F7F4 (Light beige)
- **Accent Color**: #d4f12b (Bright yellow-green)
- **Text**: Black and white contrast
- **Hover Effects**: Subtle shadows and scaling

### Typography
- **Headings**: PT Serif (elegant serif font)
- **Body Text**: Poppins (modern sans-serif)
- **Responsive Font Sizing**: Uses viewport units (vw, vh)

### Animations
- **Image Carousel**: Continuous horizontal scroll
- **Hover Effects**: Scale and shadow transformations
- **Button Transitions**: Smooth color and border changes

## 🔧 Customization

### Adding New Portfolio Items
1. Add new `.box` div elements in the `#page2` section
2. Include an image and `.box-bottom` overlay
3. Update the CSS grid as needed

### Modifying Colors
- Update CSS custom properties or direct color values in `style.css`
- Main colors are defined in the `body`, `#content h3`, and button styles

### Changing Fonts
- Modify the Google Fonts import in `style.css`
- Update the `font-family` declarations throughout the CSS

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📱 Responsive Breakpoints

The design is fully responsive with:
- Mobile-first approach
- Flexible grid layouts
- Scalable typography
- Touch-friendly interactions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Dribbble**: For design inspiration
- **Unsplash**: For high-quality stock images
- **Google Fonts**: For beautiful typography
- **Remix Icons**: For the icon library

## 📞 Contact

If you have any questions or suggestions, feel free to reach out!

---

**Note**: This is a practice project for learning web development and CSS animations. It's not affiliated with Dribbble and is for educational purposes only.
