
# Features 

- Search and watch movies: users can search for movies by title and can watch them easily
- Genre-wise display: movies can be sorted by genre
- Movie Details: users can view detailed information about each movie
- Playlist or Fav Movies: users can Add their favorite movies for later viewing into Playlist
- Google Authentication: users can sign in using their Google account



# 🍿 Technology

FasalMovie Site is built using the following technologies:

- ReactJS
- TMDB API
- Firebase Google Authentication
- Framer Motion



# How to Run the Website on Your System

## Step 1: Download and Extract the Code


## Step 2: Obtain the TMDB Movies API Key and Firebase Configuration

Before starting the website, you will need to obtain the TMDB Movies API key and Firebase configuration. Follow these steps to obtain them and add them to your `.env` file.

### ▶️ Get TMDB API Key 

- Go to https://www.themoviedb.org/ and log in.
- Click on your user profile picture in the navigation bar, and select "Settings".
- In the settings, select "API" and generate an API key.

### ▶️ Firebase Setup 

Note that Firebase is only required for Google authentication. If you are not using Google authentication in your application, you can skip this step.

- Go to the Firebase Console and create a new app.
- After creating the app, build a web app by clicking "Add App" and following the instructions.

- Copy the configuration information  and paste it into the `.env` file:


- Next, to activate Google authentication in Firebase, go to **Build > Authentication** and enable Google authentication.
- To use Google authentication in localhost, add your localhost as an Authorized Domain at **Build > Authentication > Settings > Authorized Domains** and add localhost  to this section.


## Step 3: Run the Website

```bash
npm run dev
```

This will start the application.

Note: Ensure that you have carefully added the TMDB API key and Firebase authentication configuration to your .env file. If the .env file is not working, add all the API keys and configuration manually.

<hr/>

#  Demo 

- Check out our live demo at 

