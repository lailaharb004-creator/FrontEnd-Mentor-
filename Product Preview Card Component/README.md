# Frontend Mentor - Product Preview Card Component Solution

This is my solution to the **Product Preview Card Component** challenge from Frontend Mentor. The project focuses on creating a product card layout that displays a product image, description, pricing information, and an add-to-cart button while maintaining a responsive design across different screen sizes.

## 🔗 Links

- **Live Site:** https://your-github-pages-link.com
- **Solution Repository:** https://github.com/your-username/product-preview-card

## 🚀 Built With

- Semantic HTML5
- CSS3
- Flexbox
- Responsive Design
- Media Queries
- CSS Object-fit

## ✨ Features

- Responsive product card layout.
- Desktop design with image and content displayed side by side.
- Mobile design with vertically stacked sections.
- Product image with rounded corners.
- Styled pricing section with current and previous prices.
- Add-to-cart button with icon and custom styling.
- Clean typography hierarchy for product information.

## 📚 What I Learned

While building this project, I practiced:

- Creating card-based UI components.
- Using Flexbox to control layout and alignment.
- Handling responsive images with `object-fit`.
- Managing spacing and typography to match a design reference.
- Creating reusable styles for buttons and content sections.

Example:

```css
.image img {
    object-fit: cover;
    object-position: center center;
}
```

This helped me understand how to control image behavior when the container size changes.

## 📱 Responsive Design

The layout adapts depending on the device:

- **Desktop:** Product image and information are displayed horizontally.
- **Mobile:** The image moves above the content and the card changes into a vertical layout.

## 🛠️ Future Improvements

- Add hover and active states for the cart button.
- Use CSS variables for colors and spacing.
- Add better accessibility with more descriptive image `alt` text.
- Use the recommended custom font from the design.
- Add JavaScript functionality to make the cart button interactive.

## 🙏 Acknowledgments

Thanks to **Frontend Mentor** for providing realistic frontend challenges that help developers improve their HTML and CSS skills through practical projects.