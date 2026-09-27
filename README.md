# Feane Restaurant & Grill

A responsive restaurant website built with HTML, CSS/SCSS, JavaScript, Bootstrap, and jQuery.

The project presents a modern restaurant interface with menu browsing, promotional offers, restaurant information, customer testimonials, and a table booking page.

## Features

* Responsive restaurant landing page
* Promotional food offers
* Filterable food menu by category
* Dedicated Menu and About pages
* Table booking interface
* Google Maps integration
* Responsive navigation
* Customer testimonial carousel
* Responsive layout for different screen sizes

## Tech Stack

* HTML5
* CSS3 / SCSS
* JavaScript
* Bootstrap
* jQuery
* Isotope.js
* Owl Carousel
* Nice Select
* Font Awesome
* Google Maps API

## Project Structure

```text
feane-restaurant-and-grill/
├── index.html
├── menu.html
├── about.html
├── book.html
├── css/
│   ├── bootstrap.css
│   ├── font-awesome.min.css
│   ├── responsive.css
│   ├── style.css
│   └── style.scss
├── js/
│   ├── bootstrap.js
│   ├── custom.js
│   └── jquery-3.4.1.min.js
├── images/
├── fonts/
└── .gitignore
```

## Running Locally

Clone the repository:

```bash
git clone https://github.com/adegram/feane-restaurant-and-grill.git
cd feane-restaurant-and-grill
```

Because this is a static website, no package installation or build process is required.

Open `index.html` in a browser, or serve the project with a local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Pages

| Page         | Description                                              |
| ------------ | -------------------------------------------------------- |
| `index.html` | Homepage, offers, featured menu, and restaurant sections |
| `menu.html`  | Full food menu with category filtering                   |
| `about.html` | Restaurant information                                   |
| `book.html`  | Table booking form and map                               |

## Notes

The project currently uses external CDN resources for libraries such as Owl Carousel, Isotope, Nice Select, and Google Fonts.

The booking form and online ordering interface are currently frontend components and do not include a backend reservation or payment system.

## Future Improvements

* Add a backend for table reservations
* Add online ordering functionality
* Add form validation and submission handling
* Add database integration
* Containerize the application with Docker
* Add CI/CD with GitHub Actions or Jenkins
* Add automated security and code-quality checks

## License

This project is intended for learning and portfolio purposes.
Original template credits are retained in the project files.
