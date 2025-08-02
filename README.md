# Inked Mind - Poetry Community Platform

A modern web platform for poetry enthusiasts to share, read, and engage with poetry.

## Project Structure

```
Inked-Mind/
├── src/                    # Source files
│   ├── index.html         # Main homepage
│   ├── pages/             # All HTML pages
│   │   ├── login.html
│   │   ├── signup.html
│   │   ├── dashboard.html
│   │   ├── poems.html
│   │   ├── poem.html
│   │   ├── contests.html
│   │   ├── contest-submission.html
│   │   ├── pricing.html
│   │   └── payment.html
│   └── assets/            # Static assets
│       ├── css/           # Stylesheets
│       │   ├── style.css
│       │   ├── header.css
│       │   ├── footer.css
│       │   ├── dashboard.css
│       │   └── slider.css
│       ├── js/            # JavaScript files
│       │   ├── main.js
│       │   ├── slider.js
│       │   └── dashboard.js
│       └── images/        # Image assets
│           ├── Poetry.jpg
│           └── NatureContest.jpg
└── README.md             # This file
```

## Features

- **Poetry Sharing**: Users can share and read poetry
- **Contests**: Regular poetry contests with themes
- **Community**: Interactive community features
- **Dashboard**: User dashboard for managing content
- **Responsive Design**: Mobile-friendly interface

## Getting Started

This is a **simple static website** that runs directly in any web browser - no installation required!

### Option 1: Open directly in browser
1. Navigate to the `src` folder
2. Double-click `index.html` to open in your browser

### Option 2: Use a local server (recommended for development)
If you have Python installed:
```bash
cd src
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser

### Option 3: Use VS Code Live Server extension
1. Install the "Live Server" extension in VS Code
2. Right-click on `src/index.html`
3. Select "Open with Live Server"

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling (Grid, Flexbox, Custom Properties)
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icons

## File Organization

- **`src/index.html`** - Main homepage
- **`src/pages/`** - All other HTML pages
- **`src/assets/css/`** - All stylesheets
- **`src/assets/js/`** - All JavaScript files
- **`src/assets/images/`** - All images

## Contributing

1. Fork the repository
2. Make your changes
3. Test by opening the HTML files in a browser
4. Submit a pull request

## License

This project is open source and available under the [ISC License](LICENSE).
