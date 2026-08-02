# Frontend Mentor - 3-Column Preview Card Component Solution

This is my solution to the **3-Column Preview Card Component** challenge from Frontend Mentor. The project focuses on building a responsive three-column card layout using HTML and modern CSS while matching the provided design.

## 🔗 Links

- **Live Site:** https://lailaharb004-creator.github.io/FrontEnd-Mentor-/3-column%20preview%20card%20component/
- **Solution Repository:** https://github.com/lailaharb004-creator/FrontEnd-Mentor-/tree/main/3-column%20preview%20card%20component

## 🚀 Built With

- HTML5
- CSS3
- Flexbox
- Responsive Design
- Media Queries
- Google Fonts

## ✨ Features

- Responsive three-column card layout.
- Flexbox used for layout and content alignment.
- Google Fonts (**Big Shoulders Display** and **Lexend Deca**) for typography.
- Distinct background colors for each card.
- Rounded "Learn More" buttons.
- Mobile-friendly layout with stacked cards on smaller screens.

## 📚 What I Learned

While building this project, I practiced:

- Creating responsive layouts with Flexbox.
- Structuring reusable card components using semantic HTML.
- Applying different typography with Google Fonts.
- Using media queries to switch from a horizontal layout to a vertical layout on mobile devices.
- Styling buttons, spacing, and color themes consistently across multiple cards.

Example:

```css
.container {
    display: flex;
    width: 50%;
}

@media (max-width: 767px) {
    .container {
        flex-direction: column;
        width: 70%;
    }
}
```

This project helped me better understand how Flexbox and media queries work together to create responsive layouts.

## 📱 Responsive Design

The layout adapts to different screen sizes:

- **Desktop:** Three cards are displayed side by side.
- **Mobile:** The cards stack vertically for improved readability and usability.

## 🛠️ Future Improvements

- Use CSS custom properties (variables) for colors and spacing.
- Improve accessibility by adding more descriptive `alt` text to images.
- Add hover and focus effects to the buttons.
- Refactor repeated styles into reusable utility classes.

## 🙏 Acknowledgments

Thanks to **Frontend Mentor** for providing practical frontend challenges that help developers improve their HTML and CSS skills through real-world projects.