# Spotify Artist Search App

This is a React-based web application that allows users to search for their favorite artists on Spotify and view their albums. The app uses the **Spotify Web API** for fetching artist data and album information.

## Live Demo
https://rethenike.github.io/Spotify-search-app/

## Features
- Search for artists using the Spotify API
- Display a list of albums for the searched artist
- Click on an album to open it on Spotify
- Responsive design using **React-Bootstrap**

## Technologies Used
- React.js
- React-Bootstrap
- Spotify Web API
- Fetch API
- CSS for styling

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Set Up Environment Variables
Create a `.env` file in the root directory and add the following:
```
VITE_CLIENT_ID=your_spotify_client_id
VITE_CLIENT_SECRET=your_spotify_client_secret
```
Replace `your_spotify_client_id` and `your_spotify_client_secret` with your **Spotify Developer API credentials**.

### 4. Run the Development Server
```sh
npm run dev
```
The application will be available at:
```
http://localhost:5173/
```

## Deployment on GitHub Pages
To deploy the app on GitHub Pages:
1. **Build the project:**
   ```sh
   npm run build
   ```
2. **Install `gh-pages` package (if not installed):**
   ```sh
   npm install gh-pages --save-dev
   ```
3. **Add the following in `package.json`:**
   ```json
   "homepage": "https://your-username.github.io/your-repo-name/",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
4. **Deploy the app:**
   ```sh
   npm run deploy
   ```
Your site will be live at:
```
https://your-username.github.io/your-repo-name/
```

## Usage
1. Enter the name of an artist in the search bar.
2. Press **Enter** or click the **Search** button.
3. View the list of albums displayed.
4. Click on an album to open it in Spotify.

## Contact
For any issues or questions, feel free to reach out!
philipp.h.tsang@gmail.com


