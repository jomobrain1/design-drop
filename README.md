# DesignDrop

DesignDrop is a simple browser-based poster maker for creating branded image designs directly on a canvas. Upload a main image, add a logo, style the overlay, format the text, add quote marks, and export the final poster as a PNG.

Live app: https://designd.netlify.app/

## Features

- Upload a main poster image.
- Add a logo on top of the poster.
- Choose logo placement in the top-left or top-right corner.
- Resize the logo.
- Add a customizable overlay background.
- Move the overlay to the top, center, or bottom of the image.
- Adjust overlay color, opacity, and height.
- Add poster text with custom color, font size, and font family.
- Align overlay text to the top, center, or bottom of the overlay area.
- Enable quote-style text with selectable quote styles and quote color.
- Download the finished poster as a PNG.
- Mobile-friendly layout with the poster preview shown before the controls.

## Example Output

DesignDrop can be used to create quote posters, announcement graphics, social media posts, event posters, and branded image cards.

![Example poster created with DesignDrop](./example.png)

## How To Use

1. Open the live app at https://designd.netlify.app/.
2. Upload a main image.
3. Upload a logo image if needed.
4. Choose the logo corner and logo size.
5. Customize the overlay background color, opacity, height, and position.
6. Enter your poster text.
7. Choose text color, font size, font family, and text alignment.
8. Enable quote text if you want decorative quote marks.
9. Choose the quote style and quote color.
10. Click **Download Image** to save the poster as a PNG.

## Local Development

This project is a single-page HTML app, so no build step is required.

Open `index.html` directly in your browser, or serve the folder with any static server.

Example:

```bash
npx serve .
```

## Project Structure

```text
designdrop/
├── index.html
└── README.md
```

## Deployment

The app is deployed on Netlify:

https://designd.netlify.app/

Because the app is static, it can also be deployed to Netlify, Vercel, GitHub Pages, Cloudflare Pages, or any static hosting service.

## Tech Stack

- HTML
- CSS
- JavaScript
- Canvas API

## License

Use this project freely for personal or commercial poster creation.
