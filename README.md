# 🖼️ Image Search Gallery

A modern, responsive image search application that allows users to search and browse high-quality images from Pixabay. Features infinite scroll pagination, lightbox preview, and beautiful UI notifications.

## 🌐 Live Demo

**[View Live Demo](https://helen-akateva.github.io/goit-js-hw-12/)**

## ✨ Features

- **Image Search**: Search for high-quality images using keywords
- **Infinite Scroll**: Load more images with a "Load More" button
- **Lightbox Gallery**: Click images to view them in full-screen mode with navigation
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **User Notifications**: Beautiful toast notifications for search results and errors
- **Smooth Scrolling**: Auto-scroll functionality when loading more images
- **Loading States**: Visual feedback while fetching images

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox/Grid
- **JavaScript (ES6+)** - Modern JavaScript features
- **Vite** - Fast build tool and dev server
- **Axios** - HTTP client for API requests
- **Pixabay API** - Image search service
- **SimpleLightbox** - Lightbox image gallery
- **iziToast** - Beautiful toast notifications

## 📋 Functionality

1. **Search Images**: Enter keywords in the search form to find images
2. **View Results**: Images are displayed in a responsive grid layout
3. **Load More**: Click the "Load More" button to fetch additional images
4. **Preview Images**: Click any image to open it in a lightbox with navigation controls
5. **Error Handling**: User-friendly messages for empty searches, no results, or API errors
6. **End of Results**: Notification when all available images have been loaded

## 🚀 Installation and Setup

### Prerequisites

- Node.js (LTS version recommended)
- npm or yarn

### Steps

1. Clone the repository:
```bash
git clone https://github.com/helen-akateva/goit-js-hw-12.git
cd goit-js-hw-12
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to:
```
http://localhost:5173
```

## 📦 Build for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` folder.

## 📁 Project Structure

```
goit-js-hw-12/
├── src/
│   ├── css/           # Stylesheets
│   ├── js/
│   │   ├── pixabay-api.js       # API handling
│   │   └── render-functions.js  # DOM manipulation
│   ├── img/           # Images and assets
│   ├── main.js        # Main application logic
│   └── index.html     # HTML entry point
├── package.json       # Dependencies and scripts
└── vite.config.js     # Vite configuration
```

## 👤 Author

**Olena Akatieva**

- LinkedIn: [linkedin.com/in/olena-akatieva](https://linkedin.com/in/olena-akatieva)
- GitHub: [@helen-akateva](https://github.com/helen-akateva)

## 📝 License

This project is licensed under the ISC License.

---

*Created as part of JavaScript learning curriculum*
