# EnyFlow Landing Page

A modern and responsive landing page for the EnyFlow app - an application that helps users understand their energy balance and move with confidence.

## 📋 Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)

## ✨ Features

The EnyFlow landing page includes the following features:

- **Modern and responsive design**: Fully responsive layout that looks perfect on desktop, tablet, and mobile devices
- **Visually appealing UI**: 
  - Gradient background with decorative circles
  - Phone mockup with app screenshot
  - Smooth hover animations on buttons
- **App download buttons**: Direct links to App Store and Google Play Store
- **High-quality typography**: Use of the Nunito font for a modern and readable appearance
- **Accessibility**: ARIA labels added for better accessibility
- **Cross-browser compatibility**: Works on all modern browsers
- **Optimized layout**: Grid system for perfect alignment on different screen sizes

## 📁 Project Structure

```
Landing page/
│
├── index.html          # Main HTML file with the landing page structure
├── styles.css          # Styling and CSS for the entire page
├── logo.png            # EnyFlow logo image
├── mockup.png          # Screenshot/mockup of the app for display
└── README.md           # This file
```

### File Description

- **`index.html`**: Contains the complete HTML structure of the landing page, including:
  - Meta tags for SEO and viewport settings
  - External fonts (Google Fonts - Nunito)
  - GSAP library for future animations
  - Logo section
  - Main content with text and mockup
  - Download buttons for App Store and Google Play
  
- **`styles.css`**: Contains all styling, including:
  - CSS variables for color scheme (navy blue, dark, golden, cream)
  - Layout styles for container, content wrapper and grid
  - Responsive breakpoints for tablet and mobile
  - Animations and hover effects
  - Decorative background elements

- **`logo.png`**: The EnyFlow logo displayed at the top of the page

- **`mockup.png`**: A screenshot or mockup of the EnyFlow app displayed in a phone frame

## 🚀 Installation Instructions

This landing page is a static HTML/CSS application and requires no special installation or build steps.

### Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, but recommended for the best experience)

### Installation Steps

1. **Download or clone the project**
   ```bash
   # If you're using git:
   git clone <repository-url>
   cd "Landing page"
   ```

2. **Verify file structure**
   Make sure all files are present:
   - `index.html`
   - `styles.css`
   - `logo.png`
   - `mockup.png`

3. **Optional: Install a local web server**
   
   For the best experience (especially for testing external resources), you can use a local web server:

   **With Python 3:**
   ```bash
   python -m http.server 8000
   ```

   **With Python 2:**
   ```bash
   python -m SimpleHTTPServer 8000
   ```

   **With Node.js (http-server):**
   ```bash
   npx http-server -p 8000
   ```

   **With PHP:**
   ```bash
   php -S localhost:8000
   ```

## 💻 Usage

### Running the Application

There are two ways to view the landing page:

#### Method 1: Direct file opening (simplest method)

1. Navigate to the project folder
2. Double-click on `index.html`
3. The page opens directly in your default web browser

**Note:** Some features (such as external fonts and GSAP) may work better with a local server.

#### Method 2: With local web server (recommended)

1. Open a terminal/command prompt
2. Navigate to the project directory:
   ```bash
   cd "C:\Users\gijsb\OneDrive\Bureaublad\Landing page"
   ```
3. Start a local web server (see installation instructions above)
4. Open your web browser and navigate to:
   ```
   http://localhost:8000
   ```
   (Replace `8000` with the port you chose)

