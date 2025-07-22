# MovieLand 🎬

A modern React application for searching and discovering movies using the OMDB API. Built with a sleek dark theme and responsive design.

![MovieLand Screenshot](https://github.com/MunDo12138/Movie_Database/assets/66548936/8b44fc43-07c5-4ce2-933f-868f0a8f425c)

## Features

- **Movie Search**: Search for movies by title using the OMDB API
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Dark theme with gradient text and neumorphic design elements
- **Movie Cards**: Display movie posters, titles, release years, and types
- **Keyboard Support**: Press Enter to search
- **Fallback Images**: Placeholder images for movies without posters

## Tech Stack

- **React 18** - Modern React with hooks
- **OMDB API** - Movie database for fetching movie information
- **CSS3** - Custom styling with gradients and animations
- **Environment Variables** - Secure API key management

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn
- OMDB API key (get one free at [omdbapi.com](http://www.omdbapi.com/))

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd react_js_full_course
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your OMDB API key:
```
REACT_APP_OMDB_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm start
```

The app will open at [http://localhost:3000](http://localhost:3000)

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## Project Structure

```
src/
├── App.js          # Main application component
├── App.css         # Global styles and theme
├── MovieCard.jsx   # Individual movie card component
├── index.js        # React DOM entry point
└── search.svg      # Search icon
```

## API Integration

The app uses the OMDB API to fetch movie data. The API key is stored securely in environment variables and accessed via `process.env.REACT_APP_OMDB_API_KEY`.

## Styling

The application features:
- Custom CSS with CSS variables for consistent theming
- Google Fonts (Roboto Slab and Raleway)
- Neumorphic design elements with box shadows
- Responsive breakpoints for mobile devices
- Hover effects and smooth transitions

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).
