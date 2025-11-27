# Climatovate MVP - Sprint 1

A modern, responsive climate intelligence dashboard built with React and Tailwind CSS. No external authentication services required.

## Features

✨ **Authentication (FR3)**
- Simple localStorage-based authentication
- Unique user ID generation
- Persistent sessions across page refreshes
- No Firebase or external services needed

📊 **Dashboard (FR1)**
- Real-time weather conditions display (Temperature, Wind Speed, Soil Moisture)
- 7-day weather forecast
- Interactive geospatial map placeholder (lazy-loaded for performance)
- Responsive design (mobile & desktop)

🎨 **Design**
- Modern UI with Tailwind CSS
- Smooth animations and transitions
- Mobile-first responsive layout
- Professional gradient styling
- Inter font family

## Quick Start

### Option 1: Open Directly (Simplest)

Just double-click `index.html` to open in your browser. That's it!

### Option 2: Using Live Server (Recommended)

1. **VS Code Live Server:**
   - Install "Live Server" extension in VS Code
   - Right-click `index.html` → "Open with Live Server"

2. **Or use npx:**
   ```bash
   npx serve .
   ```

3. **Or use Python:**
   ```bash
   python -m http.server 8080
   ```

Then open `http://localhost:8080`

## How to Use

1. Open the app in your browser
2. Enter any email and password (no real validation)
3. Click "Sign In to Dashboard"
4. View your unique User ID displayed at the top
5. Explore the weather widgets and map
6. Click "Sign Out" to return to login

## Project Structure

```
.
├── index.html        # Complete app (CDN-based, open directly)
├── App.jsx           # Standalone React component (for bundlers)
└── README.md         # This file
```

## Technologies Used

- **React 18** - UI framework (via CDN)
- **Tailwind CSS** - Styling (via CDN)
- **Lucide React** - Icons (via CDN)
- **localStorage** - Session persistence
- **React.lazy & Suspense** - Code splitting

## Performance Optimizations

- Lazy loading of map component
- Single-file architecture
- CDN-based dependencies (no build step)
- Mobile-first responsive design

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Notes

- Sprint 1 MVP focusing on authentication and core dashboard
- Mock data used for weather information
- Map component is a placeholder for future integration
- No backend or database required

---

**Climatovate MVP Sprint 1** 🌍
