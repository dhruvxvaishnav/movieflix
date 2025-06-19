# 🎬 Movie Discovery App

A modern, responsive movie discovery application built with React.js that allows users to browse trending movies, search for specific titles, and explore movie details using the TMDB API.

![Movie App Demo](https://img.shields.io/badge/React-18.0+-blue?logo=react) 
![Vite](https://img.shields.io/badge/Vite-5.0+-646CFF?logo=vite) 
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.0+-38B2AC?logo=tailwind-css) 
![Appwrite](https://img.shields.io/badge/Appwrite-1.0+-F02E65?logo=appwrite)

## ✨ Features

🎯 **Core Features**
- Browse trending movies with real-time data
- Search movies by title with instant results
- Responsive design that works on all devices
- Modern, sleek UI with smooth animations
- Movie details with ratings and release information

🚀 **Technical Features**
- Fast loading with Vite build tool
- Component-based architecture for reusability
- Environment variable configuration
- API integration with error handling
- Clean, maintainable code structure

## 🛠️ Tech Stack

- **Frontend**: React.js 18+ with modern hooks
- **Styling**: TailwindCSS for utility-first styling
- **Build Tool**: Vite for fast development and optimized builds
- **Backend Services**: Appwrite for data management
- **API**: The Movie Database (TMDB) API for movie data
- **State Management**: React hooks (useState, useEffect)

## 🚀 Quick Start

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (version 16 or higher)
- [Git](https://git-scm.com/)
- npm (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/movie-discovery-app.git
   cd movie-discovery-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory and add:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key_here
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` to see the app in action!

## 🔧 Getting Your API Keys

### TMDB API Key
1. Go to [The Movie Database](https://www.themoviedb.org/)
2. Create an account and log in
3. Go to Settings → API
4. Request an API key (it's free!)
5. Copy your API Read Access Token

### Appwrite Setup
1. Sign up at [Appwrite Cloud](https://cloud.appwrite.io/)
2. Create a new project
3. Set up a database and collection
4. Copy your project ID, database ID, and collection ID

## 📁 Project Structure

```
movie-discovery-app/
├── src/
│   ├── components/
|   |   ├──Spinner.jsx
│   │   ├── MovieCard.jsx
│   │   └── Search.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── public/
├── .env
├── package.json
└── README.md
```

## 🎨 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 🌟 Key Components

- **App.jsx** - Main application component with movie fetching logic
- **MovieCard.jsx** - Reusable component for displaying movie information
- **Search.jsx** - Search functionality component

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Issues & Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/yourusername/movie-discovery-app/issues) page
2. Create a new issue with detailed information
3. Include steps to reproduce the problem

## 🚀 Future Enhancements

- [ ] Add movie favorites functionality
- [ ] Implement user authentication
- [ ] Add movie trailers and reviews
- [ ] Include movie recommendations
- [ ] Add dark/light theme toggle
- [ ] Implement infinite scroll for movie lists

---

⭐ **Star this repository if you found it helpful!**

Made by dhruvxvaishnav
