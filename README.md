# GAME STATION

A modern gaming news and community website showcasing featured games, news articles, and gaming reviews.

## 📋 Project Overview

GAME STATION is a responsive web application designed for gaming enthusiasts. It provides:
- Featured games showcase with game information
- Latest gaming news and updates
- Gaming reviews and community highlights
- Responsive design for desktop and mobile devices

## 🎯 Features

- **Hero Section**: Eye-catching welcome section with search functionality
- **Featured Games Grid**: Display of popular games (Fortnite, GTA V, Valorant) with descriptions
- **News Section**: Latest gaming news with publication dates
- **Responsive Design**: Optimized for desktop (1920px+), tablets (768px-1024px), and mobile (under 480px)
- **Modern UI**: Glass-morphism effects with backdrop blur and semi-transparent cards
- **Gaming Imagery**: Dynamic background images that adapt to screen size

## 📁 File Structure

```
mini-project/
├── index.html          # Main HTML file with page structure
├── style.css           # Complete styling with responsive media queries
├── README.md           # Project documentation
└── images/
    ├── game-logo.png   # Site logo
    ├── Fortnite.png    # Fortnite game image
    ├── gta-v.webp      # GTA V game image
    ├── valo.webp       # Valorant game image
    ├── wallhaven-1q83qg.jpg  # Desktop background (landscape)
    └── Wall-hev-mob.jpg      # Mobile background (portrait)
```

## 🎨 Design Features

### Color Scheme
- Primary: Yellow (#ffcc00) - Highlights and call-to-action buttons
- Background: Dark with semi-transparent overlays for readability
- Text: White for contrast against dark backgrounds

### Responsive Breakpoints
- **Desktop**: Full layout with parallax background effect
- **Tablet (≤768px)**: Adjusted spacing and font sizes
- **Mobile (≤480px)**: Mobile-optimized background image and compact layout

### Background Images
- **Desktop**: Landscape wallpaper with fixed attachment for parallax scrolling
- **Mobile**: Portrait-optimized image that covers full screen
- Gradient overlay (rgba(0,0,0,0.6)) for text readability

## 🔧 Technical Details

### HTML Structure
- Semantic HTML5 structure
- Meta viewport tag for responsive design
- Navigation bar with site logo and menu links
- Main sections: Hero, Featured Games, News

### CSS Features
- CSS Grid for game cards layout
- Flexbox for navigation and alignment
- Glass-morphism effects (backdrop-filter: blur)
- Media queries for responsive design
- CSS variables for consistent styling
- Linear gradients for overlays

### Mobile Optimization
- Touch-friendly button sizes
- Proper viewport meta tag configuration
- Background attachment: fixed for consistent appearance
- Cover background sizing for full viewport coverage

## 📱 Responsive Behavior

| Device | Width | Features |
|--------|-------|----------|
| Desktop | 1920px+ | Full parallax background, larger fonts, full nav menu |
| Tablet | 768px-1024px | Adjusted spacing, mobile background image |
| Mobile | <480px | Portrait background, compact layout, stacked cards |

## 🚀 Usage

1. Open `index.html` in a web browser
2. Navigate using the menu links in the header
3. Click on game cards or news items to explore more
4. Use the search box to find specific games or news

## 🔗 Navigation Links

- **Home**: Main landing page
- **About Us**: Company/project information
- **Contact Us**: Get in touch
- **Support**: Help and support section

## 💡 Notes

- The website uses modern CSS features (backdrop-filter) - ensure browser compatibility
- Images are optimized for different screen sizes
- Background images adapt based on device orientation and viewport size
- All text is readable with the semi-transparent overlay gradient

## 🎮 Featured Games

1. **Fortnite**: Battle royale game - fight to be the last one standing
2. **GTA V**: Open-world action-adventure set in Los Santos
3. **Valorant**: Tactical shooter with unique character abilities

## 📝 Future Enhancements

- Add JavaScript for interactive features
- Implement backend for dynamic content
- Add user authentication system
- Create individual game/article pages
- Add comment and rating system
