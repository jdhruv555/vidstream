# VidStream

A modern video streaming platform built with React.js and Material-UI. VidStream allows users to browse, search, and watch videos with a sleek and responsive interface.

## Features

- 🎥 Video playback with React Player
- 🔍 Real-time search functionality
- 📱 Responsive Material UI design
- 🎯 Category-based video filtering
- 👤 Channel pages
- 📺 Related videos suggestions
- 🎨 Modern dark theme interface

## Tech Stack

- React.js
- Material-UI
- React Router
- Axios
- YouTube Data API (via RapidAPI)

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/jdhruv555/vidstream.git
```

2. Install dependencies
```bash
cd vidstream
npm install
```

3. Create a `.env` file in the root directory and add your RapidAPI key:
```
REACT_APP_RAPID_API_KEY=your_api_key_here
```

4. Start the development server
```bash
npm start
```

5. Open [http://localhost:3000](http://localhost:3000) to view it in your browser

## Project Structure

```
vidstream/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── ChannelCard.jsx
│   │   ├── ChannelDetail.jsx
│   │   ├── Feed.jsx
│   │   ├── Navbar.jsx
│   │   ├── SearchBar.jsx
│   │   ├── SearchFeed.jsx
│   │   ├── Sidebar.jsx
│   │   ├── VideoCard.jsx
│   │   ├── VideoDetail.jsx
│   │   ├── Videos.jsx
│   │   └── index.js
│   ├── utils/
│   │   ├── constants.js
│   │   └── fetchFromAPI.js
│   ├── App.js
│   └── index.js
└── package.json
```

## License

Copyright 2024 VidStream by DHRUV. All rights reserved.
