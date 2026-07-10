# Mount-Inn-Responsive-Hotel-Website

## 👉 [Live Website](https://the-mount-inn.netlify.app/)

A responsive hotel website template built to practice CSS layout fundamentals and mobile-responsive design patterns without a framework.

## What this demonstrates

- **Responsive Navigation**: Implemented a hamburger menu pattern using vanilla JavaScript to handle mobile state toggling.
- **Layout Techniques**: Utilized CSS Grid for the photo gallery and Flexbox for navigation, footer, and service card components.
- **Design System**: Implemented maintainable theming using CSS custom properties for color palettes and font stacks.
- **UX Enhancements**: Integrated smooth scroll behavior for in-page navigation and responsive media queries ranging from 1335px to 405px.
- **Semantic Structure**: Built with semantic HTML5 and external icons via Font Awesome 6.1.1.

## Build/design decisions

| Decision | Reasoning |
| :--- | :--- |
| **Desktop-first CSS** | Structured initially for large screens with breakpoint overrides for tablet and mobile responsiveness. |
| **Vanilla JS** | Used for navigation toggling to practice DOM manipulation without framework overhead. |
| **CSS Custom Properties** | Centralized theming (colors, typography) to ensure consistency across components. |

## What I'd do differently now

The current desktop-first approach using `max-width` breakpoints made managing responsive overrides across multiple sections complex. I would now implement a mobile-first approach using `min-width` breakpoints, which is more scalable and results in leaner CSS for smaller screens.

## Technologies Used

- **HTML5**
- **CSS3** (Flexbox, Grid, CSS Custom Properties, smooth scroll)
- **JavaScript** (Vanilla)
- **Fonts**: Google Fonts — Open Sans & Quicksand
- **Icons**: Font Awesome 6.1.1

## Project structure

```
mount-inn-responsive-hotel-website/
├── index.html      # single-page site: rooms/services, photo gallery, footer
├── css/
│   └── style.css   # layout, CSS custom-property theming, responsive media queries
└── js/
    └── script.js   # mobile hamburger-nav toggle
```

## Getting Started

1. **Clone the Repository**: Clone the repository to your local machine using the following command:
   ```bash
   git clone git@github.com:mahmud035/mount-inn-responsive-hotel-website.git
   ```
2. **Open the Project**: Navigate to the project directory and open the files in your preferred code editor.

3. **Run the Project**: Open the `index.html` file in your browser to view the website.

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.
