# Neumorphism Profile Card UI

A simple profile card built with **HTML and CSS**, featuring a neumorphism-inspired design, a circular profile image, social media icons, action buttons, and profile engagement statistics.

##  Features

- Neumorphism-inspired profile card styling
- Circular profile image
- Name and professional tagline
- Social media icons for Facebook, Instagram, Twitter, and YouTube
- `Message` and `About Me` buttons
- Engagement statistics for shares, comments, and likes
- Hover effects on icons and statistics
- Font Awesome icons loaded from a CDN

## Built With

- HTML5
- CSS3
- [Font Awesome 5](https://fontawesome.com/)

## Project Structure

```text
Neumorphism-UI-Card/
├── index.html
├── style.css
└── Img.jpg
```

- `index.html` — contains the profile card markup.
- `style.css` — contains the layout, colors, shadows, and hover effects.
- `Img.jpg` — profile image displayed in the card.

## Run Locally

1. Download or clone this repository.
2. Keep `index.html`, `style.css`, and `Img.jpg` in the same folder.
3. Open `index.html` in your browser.

You can also open the folder in Visual Studio Code and use the **Live Server** extension to preview the page while editing.

## Customize the Card

- **Profile name and tagline:** Edit the text in `index.html`.
- **Profile picture:** Replace `Img.jpg` with your image, keeping the same filename, or update the image path in `index.html`.
- **Colors, dimensions, and shadows:** Edit the `.profile`, `.upper-part`, `.icon`, and related rules in `style.css`.
- **Social icons:** Change the Font Awesome icon classes in `index.html`.

## Notes

- Font Awesome icons require an internet connection because the stylesheet is loaded from a CDN.
- The social media icons and buttons are currently visual UI elements; they do not have functional links or actions connected.
- Update the sample profile details and engagement counts to your own content before publishing.

## License

This project is available for learning and personal experimentation. Add a license file if you intend to specify reuse and distribution terms.
