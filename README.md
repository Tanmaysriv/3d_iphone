# iPhone E-Commerce React App

This project is a modern e-commerce web application for showcasing and selling the iPhone 15 Pro. It features a visually rich UI, video carousels, 3D scenes, and smooth animations using React, GSAP, and Three.js.

## Features

- **Product Showcase:** Hero section with video and animated transitions.
- **3D Experience:** Uses Three.js and @react-three/drei for interactive 3D product views.
- **Video Carousel:** Highlight product features with video slides.
- **Responsive Design:** Optimized for desktop and mobile devices.
- **Modern Animations:** GSAP-powered smooth UI transitions.
- **Pricing in INR:** All prices are displayed in Indian Rupees (₹).

## Tech Stack

- **React** (Vite)
- **Three.js** & **@react-three/drei**
- **GSAP** for animations
- **Sentry** for error monitoring
- **Tailwind CSS** for styling

## Getting Started

### Prerequisites

- Node.js (v16 or above)
- npm

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/iphone-main.git
   cd iphone-main
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

## Project Structure

```
src/
  components/      # React components (Hero, VideoCarousel, Lights, etc.)
  utils/           # Utility functions and constants
  App.jsx          # Main app component
  main.jsx         # Entry point
  index.css        # Global styles
```

## Customization

- **Change Pricing:**  
  Update prices in components like `Hero.jsx` and any other relevant files. All prices are now in INR (₹).

- **Media Assets:**  
  Place your videos and images in the appropriate folders and update import paths as needed.

## Deployment

You can deploy this app to any static hosting provider (Vercel, Netlify, Firebase Hosting, etc.) after building:

```bash
npm run build
```

## License

This project is for educational/demo purposes.

---

**Made with ❤️ using React, GSAP, and
