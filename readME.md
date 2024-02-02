# Infinite Scroll with Unsplash API

## Overview

This project demonstrates an infinite scroll implementation using the Unsplash API to load and display random photos. The user can scroll through the page, and as they approach the bottom, additional images are fetched and appended to the display.

## Technologies Used

- HTML
- CSS
- JavaScript

## Dependencies

- [Unsplash API](https://unsplash.com/developers) - To fetch random photos.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/infinite-scroll-unsplash.git
   ```

2. Open `index.html` in your web browser.

## Usage

1. The page initially loads with a title, loader, and an empty image container.
2. As you scroll down, additional images are fetched from the Unsplash API and displayed in the image container.
3. The loader indicates when images are being loaded.

## Styling

The project uses a minimalistic design with a loader and responsive styling. It is optimized for both large screens and small smartphones.

## Customization

- You can customize the appearance by modifying the `style.css` file.
- To change the number of initially loaded and subsequently fetched images, adjust the `count` variable in the `script.js` file.

```javascript
let count = 5; // initial count of images
```

## API Key

To fetch images from the Unsplash API, you need to obtain an API key. Replace the placeholder in the `script.js` file with your actual API key.

```javascript
const apiKey = 'your-api-key';
```

## Credits

- [Unsplash](https://unsplash.com/) - For providing a vast collection of high-quality images.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Acknowledgments

Special thanks to Unsplash for providing the API, and to the developers of Bebas Neue font.

---

Feel free to contribute, report issues, or suggest improvements!