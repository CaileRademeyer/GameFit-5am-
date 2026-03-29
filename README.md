# GameFit 5am Club - Progressive Web App

A fitness and workout planning app designed for mobile devices.

## Features

- **Progressive Web App (PWA)**: Installable on phones and tablets
- **Offline Support**: Works without internet connection
- **Responsive Design**: Optimized for mobile screens
- **Workout Categories**: Strength, Cardio, Mobility, Rugby Drills, Fitness Circuits, Boxing, and Women's Fitness
- **User Authentication**: Login/signup system

## Installation

### For Users

1. Open the app in a modern browser (Chrome, Firefox, Safari, Edge)
2. Look for the "Install" or "Add to Home Screen" option
3. Follow the prompts to install the app

### For Developers

#### Prerequisites

- Modern web browser with PWA support
- HTTPS for production deployment

#### Local Development

1. Clone or download the files
2. Open `index.html` in a browser
3. The app will work locally, but PWA features require HTTPS

#### Deployment

Deploy to any static hosting service with HTTPS:

- **Netlify**: Drag and drop the files
- **Vercel**: Connect GitHub repo
- **GitHub Pages**: Enable Pages in repository settings
- **Firebase Hosting**: Use Firebase CLI

## File Structure

```
/
├── index.html          # Main app HTML
├── style.css           # App styling
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── icon-192.svg       # App icon (192x192)
└── icon-512.svg       # App icon (512x512)
```

## PWA Features

- **Installable**: Add to home screen on mobile devices
- **Offline First**: Cached resources work without internet
- **Fast Loading**: Optimized for mobile performance
- **Native Feel**: Standalone app experience

## Browser Support

- Chrome/Edge (best PWA support)
- Firefox (good PWA support)
- Safari (iOS PWA support)
- Samsung Internet

## Development Notes

- Touch targets are minimum 44px for accessibility
- Responsive design works on screens 320px and up
- Dark theme optimized for battery life
- Animations use CSS for smooth performance

## Future Enhancements

- Real user authentication with backend
- Workout progress tracking
- Push notifications for workout reminders
- Social features and leaderboards
- Integration with fitness wearables
