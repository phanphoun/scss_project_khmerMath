# My SCSS Website

A modern website built with HTML5, SCSS, and JavaScript, featuring a modular SCSS architecture and responsive design.

## 🚀 Features

- **Modular SCSS Architecture**: Organized with 7-1 pattern for maintainable styles
- **Responsive Design**: Mobile-first approach with flexible grid system
- **Modern CSS**: Uses latest CSS features with autoprefixer for browser compatibility
- **Component-Based**: Reusable UI components (buttons, cards, forms, modals)
- **Multiple Pages**: Educational content pages for different grade levels
- **Interactive Tools**: Calculator, chatbot, and other utility tools

## 📁 Project Structure

```
my_website/
├── .vscode/                 # VS Code configuration
│   └── settings.json        # Live Sass Compiler settings
├── assets/                  # Static assets
│   ├── css/                 # Compiled CSS files
│   ├── fonts/               # Font files
│   ├── images/              # Image assets
│   └── js/                  # JavaScript files
├── pages/                   # HTML pages
│   ├── grade7.html          # Grade 7 content
│   ├── grade8.html          # Grade 8 content
│   ├── grade9.html          # Grade 9 content
│   ├── grade10.html         # Grade 10 content
│   ├── grade11.html         # Grade 11 content
│   ├── grade12.html         # Grade 12 content
│   ├── chatbot.html         # Chatbot tool
│   ├── cululator.html       # Calculator tool
│   └── tool.html            # Other tools
├── scss/                    # SCSS source files (7-1 pattern)
│   ├── abstracts/           # Variables, functions, mixins, placeholders
│   ├── bases/               # Reset, base styles, typography
│   ├── components/          # Buttons, cards, forms, modals
│   ├── layout/              # Header, footer, navigation, grid
│   ├── pages/               # Page-specific styles
│   ├── theme/               # Theme configuration
│   ├── vendors/             # Third-party styles
│   └── main.scss            # Main SCSS entry point
├── about.html               # About page
├── contact.html             # Contact page
├── index.html               # Homepage
└── README.md                # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **SCSS**: CSS preprocessor with modern features
- **JavaScript**: Interactive functionality
- **Live Sass Compiler**: VS Code extension for SCSS compilation
- **Autoprefixer**: Automatic CSS vendor prefixing

## 📦 Installation & Setup

### Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)
- [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) extension
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension (optional)

### Setup Instructions

1. **Clone or download the project**
   ```bash
   git clone <repository-url>
   cd my_website
   ```

2. **Install VS Code extensions**
   - Install "Live Sass Compiler" by Ritwick Dey
   - Install "Live Server" by Ritwick Dey (recommended)

3. **Configure Live Sass Compiler**
   - The project includes `.vscode/settings.json` with optimal configuration
   - SCSS files will compile to `assets/css/` directory
   - Source maps are generated for debugging

4. **Start development**
   - Open the project in VS Code
   - Click "Watch Sass" in the status bar to start compilation
   - Right-click `index.html` and select "Open with Live Server"

## 🎨 SCSS Architecture (7-1 Pattern)

The project follows the 7-1 SCSS architecture pattern:

### 1. Abstracts (`scss/abstracts/`)
- `_functions.scss`: Sass functions
- `_mixins.scss`: Reusable mixins
- `_variables.scss`: Global variables (colors, fonts, breakpoints)
- `_placeholders.scss`: Extensible placeholders

### 2. Base (`scss/bases/`)
- `_reset.scss`: CSS reset
- `_base.scss`: Base HTML element styles
- `_typography.scss`: Typography styles
- `_utilities.scss`: Utility classes

### 3. Components (`scss/components/`)
- `_buttons.scss`: Button styles and variations
- `_card.scss`: Card component styles
- `_form.scss`: Form element styles
- `_modal.scss`: Modal component styles

### 4. Layout (`scss/layout/`)
- `_grid.scss`: Grid system
- `_header.scss`: Header styles
- `_footer.scss`: Footer styles
- `_navigation.scss`: Navigation styles
- `_sidebar.scss`: Sidebar styles

### 5. Pages (`scss/pages/`)
- `_home.scss`: Homepage-specific styles
- `_about.scss`: About page styles
- `_contact.scss`: Contact page styles

### 6. Themes (`scss/theme/`)
- `_theme.scss`: Theme configurations

### 7. Vendors (`scss/vendors/`)
- `_normalize.scss`: Normalize.css

### Main Entry Point (`scss/main.scss`)
Imports all partials in the correct order for compilation.

## 🎯 Key Features

### Responsive Grid System
- Mobile-first approach
- Flexible column layouts
- Breakpoint-based responsive design

### Component Library
- Reusable UI components
- Consistent design system
- Easy to customize and extend

### Educational Content
- Grade-specific pages (7-12)
- Interactive tools and calculators
- Chatbot functionality

## 🚀 Development Workflow

1. **Modify SCSS files** in the `scss/` directory
2. **Live Sass Compiler** automatically compiles to CSS
3. **Live Server** refreshes the browser on changes
4. **Test** across different screen sizes

## 📱 Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [7-1 SCSS Pattern](https://sass-guidelin.es/#the-7-1-pattern) for architecture inspiration
- [Normalize.css](https://necolas.github.io/normalize.css/) for CSS reset
- [Live Sass Compiler](https://github.com/ritwickdey/vscode-live-sass-compiler) for SCSS compilation

## 📞 Contact

For questions or suggestions, please open an issue or contact the project maintainer.

---

**Built with ❤️ using modern web technologies**
