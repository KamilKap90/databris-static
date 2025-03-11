# Databris

Databris is a modern, responsive web application that provides a clean and intuitive interface for data visualization and analytics. Built with Bootstrap 5 and optimized for performance across all devices, it offers a seamless user experience while maintaining high accessibility standards.

## Features

- Responsive layout using Bootstrap 5 components and grid system
- Modern JavaScript with ES6+ syntax for enhanced interactivity
- Cross-browser compatibility with progressive enhancement
- Optimized performance with lazy loading and efficient asset management
- Accessibility compliance following WCAG guidelines
- Interactive data visualization components
- Smooth scrolling and navigation with ScrollSpy implementation

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, or Edge latest versions)
- Node.js and npm (optional, for development)
- Local server environment or PHP server for backend integration

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/databris.git
   ```
2. Navigate to the project directory:
   ```
   cd databris
   ```
3. Open `index.html` in your browser or set up with your local server.

## Project Structure

```
databris/
├── assets/
│ ├── css/
│ │ ├── bootstrap.min.css
│ │ └── custom.css
│ ├── js/
│ │ ├── bootstrap.bundle.min.js
│ │ └── custom.js
│ ├── vendor/
│ │ └── bootstrap/
│ └── img/
├── index.html
└── [other HTML files]
```

## Usage

Databris provides several interactive components for data visualization:

1. **Interactive Dashboards**: Navigate through different data views using the tabbed interface
2. **Responsive Charts**: Data visualizations automatically adjust to screen size
3. **Data Filtering**: Use the dropdown controls to filter and sort displayed information
4. **Scrollable Data Tables**: Browse through large datasets with optimized scrolling performance

## Customization

### CSS

Custom styles extend Bootstrap through dedicated classes in `custom.css`. To modify:

1. Add new CSS classes rather than overriding Bootstrap defaults
2. Use Bootstrap's utilities where possible (`my-3`, `d-flex`, etc.)
3. Follow the established naming conventions
4. Use CSS variables for consistent theming

### JavaScript

The JavaScript is structured in modular components:

1. Core functionality in `custom.js`
2. Event handlers use delegation patterns for better performance
3. DOM manipulation is optimized for performance
4. Bootstrap components are initialized with custom configurations

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- iOS Safari (latest)
- Android Chrome (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'add: some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Bootstrap 5.0.1](https://getbootstrap.com/)
- [GLightbox](https://biati-digital.github.io/glightbox/)
- FontAwesome for icons
- All contributors who have helped shape this project

---

README.md created by [Edin Durak](https://github.com/edindurak)
