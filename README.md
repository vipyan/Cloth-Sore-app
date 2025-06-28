# Cloth-Sore-app

A simple responsive website to demonstrate the use of SCSS and modern front-end web design principles, themed as a clothes store.

![Logo](images/logo.png)

## Features

- **Responsive Layout:** Uses CSS Grid and Flexbox for adaptable layouts across devices.
- **SCSS Architecture:** Modular SCSS with variables, mixins, and component-based structure.
- **Modern UI Components:** Header, navigation menus, slideshow/banner, product cards, and footer.
- **Product Showcase:** Sections to display products with images, descriptions, and pricing.
- **Newsletter Signup:** Simple form to collect user information.
- **Social Media Integration:** Footer contains social media links (Facebook, YouTube, Twitter, LinkedIn, Instagram).
- **Accessible and Clean Typography:** Uses 'Josefin Sans' and 'Great Vibes' Google Fonts.

## Technologies Used

- **HTML5**
- **SCSS (and compiled CSS)**
- **Font Awesome** (for icons)
- **Google Fonts**
- **Vanilla JavaScript** (if any, not present in main codebase currently)

## File Structure

```
.
├── css/
│   └── main.css
├── scss/
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   └── _base.scss
│   ├── components/
│   │   ├── _button.scss
│   │   ├── _dropdown.scss
│   │   ├── _heading.scss
│   │   └── _logo.scss
│   ├── layout/
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _navigation.scss
│   │   ├── _products.scss
│   │   └── _slideshow.scss
│   └── main.scss
├── images/
│   ├── logo.png
│   └── product[1..N].png
└── index.html
```

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/vipyan/Cloth-Sore-app.git
   cd Cloth-Sore-app
   ```

2. **Open `index.html`**
   Open the `index.html` file in your web browser. All styles are precompiled to `css/main.css`.

3. **Development (SCSS)**
   - Edit or add SCSS files in the `/scss` directory.
   - Compile SCSS to CSS using your preferred method, e.g.:
     ```
     sass scss/main.scss css/main.css
     ```

## Screenshots

![Demo](images/product1.png)

*Add more screenshots as needed.*

## License

*No license specified. Please add a license if you intend others to use or contribute to this project.*

## Author

- [vipyan](https://github.com/vipyan)

---

> _This project is intended as a learning/demo project for SCSS and front-end layouts._
