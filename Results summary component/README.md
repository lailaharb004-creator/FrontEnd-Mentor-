# Frontend Mentor - Results Summary Component Solution

This is my solution to the **Results Summary Component** challenge from Frontend Mentor. The project is a responsive results card that displays a user's score summary with different category results and a call-to-action button.

The main goal of this challenge was to recreate the provided design while practicing layout techniques, Flexbox, responsive design, and component styling.


## 🔗 Links

- **Live Site:** https://your-github-pages-link.com
- **Solution Repository:** https://github.com/your-username/results-summary-component

## 🚀 Built With

- Semantic HTML5
- CSS3
- Flexbox
- Responsive Design
- CSS Gradients
- Media Queries

## ✨ Features

- Responsive results summary card.
- Two-section layout:
  - Result section with score and performance message.
  - Summary section with category scores.
- Custom circular score indicator using CSS gradients.
- Different colors for each result category.
- Mobile-friendly layout with stacked sections.
- Styled button with rounded design.

## 📚 What I Learned

Through this project, I practiced:

- Creating complex layouts using Flexbox.
- Building reusable styles for repeated components.
- Using CSS gradients to create visual effects.
- Organizing content into semantic sections.
- Making desktop layouts adapt to mobile screens.

Example of creating the score circle:

```css
.circle {
    background: linear-gradient(
        360deg,
        rgb(60, 48, 238),
        rgb(75, 36, 204)
    );
}
```

This helped me understand how gradients can be used to recreate modern UI designs.

## 📱 Responsive Design

The component adapts to different screen sizes:

- **Desktop:** Two-column layout with the result and summary sections displayed side by side.
- **Mobile:** Sections stack vertically for better readability and usability.

## 🛠️ Future Improvements

- Add smooth hover and active states to the button.
- Use CSS variables for colors and repeated values.
- Improve typography using the recommended font from the design.
- Use more flexible sizing with `clamp()` for better responsiveness.
- Add dynamic data rendering using JavaScript.

## 🙏 Acknowledgments

Thanks to **Frontend Mentor** for providing realistic frontend challenges that help developers improve their frontend skills through practical UI implementations.