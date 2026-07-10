# Frontend Mentor - Stats Preview Card Component Solution

This is my solution to the **Stats Preview Card Component** challenge on Frontend Mentor. The goal of this project was to build a responsive stats preview card that closely matches the provided design while practicing semantic HTML, Flexbox, responsive layouts, and image overlay effects.

## 🔗 Links

- **Live Site:** https://your-github-pages-link.com
- **Solution Repository:** https://github.com/your-username/your-repository

## 🚀 Built With

- Semantic HTML5
- CSS3
- Flexbox
- Responsive Design
- Media Queries
- CSS Pseudo-elements (`::after`) for the image overlay

## ✨ Features

- Responsive layout for desktop and mobile devices.
- Flexbox-based structure for clean alignment.
- Purple overlay effect applied using a CSS pseudo-element.
- Rounded corners matching the original design.
- Mobile layout with reordered content using `flex-direction: column-reverse`.
- Clean typography hierarchy for headings, descriptions, and statistics.

## 📚 What I Learned

While building this project, I practiced:

- Structuring content using semantic HTML elements such as `article`, `section`, `header`, and `footer`.
- Creating responsive layouts with Flexbox.
- Using media queries to adapt the design for smaller screens.
- Applying an image overlay using a positioned pseudo-element.
- Managing spacing, alignment, and typography for a polished UI.

Example of the overlay implementation:

```css
.right-side::after {
    content: "";
    position: absolute;
    inset: 0;
    background: #a056ce;
    opacity: 0.66;
}
```

## 📱 Responsive Design

The component adjusts its layout depending on the screen size:

- **Desktop:** Content and image are displayed side by side.
- **Mobile:** The image moves above the content, and the statistics stack vertically for better readability.

## 🛠️ Future Improvements

- Use CSS custom properties for colors and spacing.
- Improve accessibility by refining color contrast where appropriate.
- Add hover effects for a more interactive experience.
- Optimize typography using `clamp()` for smoother responsiveness.


## 🙏 Acknowledgments

Thanks to Frontend Mentor for providing realistic frontend challenges that help improve HTML and CSS skills through practical projects.