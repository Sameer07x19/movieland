# MovieLand

A simple movie searching app built using React and the OMDB API. MovieLand allows users to search for their favorite movies and displays information such as title, release year, and poster.

## Features
- **Search Functionality**: Type in the search bar to find movies from the OMDB database.
- **Dynamic Results**: Displays a list of movies that match the search query.
- **Clean UI**: A user-friendly interface for a seamless experience.

## Live Demo
Check out the live demo of the app here:
[MovieLand](https://sameerxmovieland.netlify.app)

## Technologies Used
- **React**: For building the user interface.
- **OMDB API**: To fetch movie data.
- **Netlify**: For hosting the application.
- **CSS**: For styling the app.

## Installation
To run the app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/movieland.git
   ```

2. Navigate to the project directory:
   ```bash
   cd movieland
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and go to:
   ```
   http://localhost:3000
   ```

## Deployment
This app is deployed on Netlify. To deploy your own version:

1. Create a production build:
   ```bash
   npm run build
   ```

2. Upload the `build` folder to Netlify.

3. Your app will be live and accessible through the Netlify-provided link.

## API Integration
The app uses the [OMDB API](http://www.omdbapi.com/) to fetch movie data. Ensure you have a valid API key to use the service. Get your own api key at their official website.

To set your API key, update the `API_URL` constant in `App.js`:
```javascript
const API_URL = "https://omdbapi.com?apikey=YOUR_API_KEY";
```

## Contribution
Feel free to fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

**Author:** Sameer Sayyed

