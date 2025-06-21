# Spotify-Clone
A complete and working clone of Spotify, constructed using React, Node.js, Express.js, and MongoDB. The goal of this project is to mimic Spotify's essential features, which include the ability to play music, explore albums, and control playback. It has features for uploading, viewing, and deleting songs in addition to creating, browsing, and deleting albums.

# Features
Album Management: Create, list, and delete albums.\
Song Management: Upload, list, and delete songs.\
Play Music: Users can play, pause, and skip tracks.\
Responsive Design: Mobile-friendly design for better accessibility.
Technologies Used
Frontend: React, Tailwind CSS\
Backend: Node.js, Express.js\
Database: MongoDB\
Cloud Storage: Cloudinary for image and song storage\
Tools: Git, Vite, VSCode\
State Management: Context API\
Other Libraries: Axios, React Router, React Toastify
# Installation

Clone the repository:

git clone https://github.com/lavanya0506/Spotify-clone.git<br/>
cd Spotify-Clone-MERN-Website\
Set up environment variables: Create a .env file in the root directory and add the following:

MONGO_URI=your_mongodb_uri \
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name\
CLOUDINARY_API_KEY=your_cloudinary_api_key\
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

cd spotify-backend\
npm install\
npm start


Run the backend :\
cd spotify-admin\
npm install\
npm run dev

Run the frontend:\
cd spotify-frontend\
npm install\
npm run dev

#Usage
Open your browser and navigate to http://localhost:3000.<br/>
Create new albums and songs on the Spotify Admin page.<br/>
Browse albums and songs, create playlists, and enjoy music.<br/>
