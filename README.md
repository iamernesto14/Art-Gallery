# Modern Art Gallery Website

A responsive website for a modern art gallery that showcases artwork collections and provides location information.

## Overview

This project is a multi-page website for an art gallery that includes:
- A responsive home page displaying the gallery's featured artwork
- A location page with address information
- Mobile-first design approach with responsive layouts for tablet and desktop
- Interactive elements with hover states

## Technologies Used

- HTML5
- CSS3
- Responsive Design Techniques
- CSS Grid and Flexbox
- CSS Custom Properties (Variables)
- Mobile-first workflow

## Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop viewports
- **Interactive Elements**: Button hover effects and interactive components
- **Grid Layout**: Advanced CSS grid implementation for gallery section
- **High-Resolution Images**: Optimized images with `<picture>` element for different screen sizes
- **Accessible Design**: ARIA attributes and semantic HTML

## Project Structure

```
Modern-Art-Gallery/
├── index.html           # Home page
├── location.html        # Location page
├── css/
│   └── styles.css       # Main stylesheet
└── images/              # Image assets for the project
    ├── desktop/         # Desktop-sized images
    ├── tablet/          # Tablet-sized images
    └── mobile/          # Mobile-sized images
```

## Git Workflow Used

The development of this project followed a structured git workflow:

1. **Repository Setup**:
   ```
   git init
   ```

2. **Initial Commit**:
   ```
   git add .
   git commit -m "Project Setup"
   ```

3. **Feature Branch Creation**:
   ```
   git branch development
   git branch feature/Home-page
   git checkout feature/Location
   git checkout feature/button
   git checkout feature/readme
   ```

4. **Feature Development**:
   ```
   git add index.html css/styles.css
   git commit -m "create a thome page"
   ```

5. **Feature Integration**:
   ```
   git checkout development
   git merge feature/Homepage
   ```

6. **Checking Status**:
   ```
   git status
   ```

7. **Remote Repository Management**:
   ```
   git push origin main
   ```

## Responsive Design

The website implements a mobile-first approach with three main breakpoints:
- Mobile: Default styles
- Tablet: 768px and above
- Desktop: 1024px and above
- Large Desktop: 1200px and above

CSS Grid and Flexbox were used for complex layouts, particularly in the gallery grid section and for the responsive header.

## Accessibility Features

- Semantic HTML structure
- ARIA labels for interactive elements
- Sufficient color contrast

## CSS Features

- Custom CSS variables for consistent theming
- CSS Grid for complex layouts
- Flexbox for component alignment
- Media queries for responsive design

## Setup and Local Development

1. Clone the repository:
   ```
   git clone [repository-url]
   ```

2. Navigate to the project folder:
   ```
   cd Art-Gallery
   ```

3. Open `index.html` in your browser to view the website locally.

4. For development purposes, it's recommended to use a local server:
   ```
   npx serve
   ```

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

Developed by [Ernest Anokye] 