# usePopcorn Movie App

**usePopcorn Movie App** is a movie discovery and management app built entirely with React. It utilizes the OMDb API to search for movies by title and provides a sleek, user-friendly interface for interacting with movie data.

## Features 

- **Search Functionality:** Users can search for movies by their name using the OMDb API, and a list of results will be displayed.
- **Loading and Error Handling:** While the search is being processed, a loading message appears. If the movie is not found, a message informs the user that the movie is unavailable.
- **Rating System:** Users can click on stars to rate movies. The rating is saved in local storage, allowing users to persist their ratings even after a page refresh.
- **Watched Movies List:** Once a user rates a movie, they can add it to their "Watched Movies" list for easy reference. Movies can also be removed from the list.
- **Local Storage Integration:** The user's movie ratings and watched list are saved in the browser’s local storage, ensuring the data persists between sessions.


![usePopcorn 1](https://github.com/user-attachments/assets/7749b401-bd72-4745-b0a3-6c9186c058ca)
![usePopcorn 2](https://github.com/user-attachments/assets/f9e00386-8027-4906-83d5-8d08323b70db)
![usePopcorn 3](https://github.com/user-attachments/assets/88d7a467-9fdb-4ab7-88b2-f0c3d8262bdb)



## Technologies used

- **React:** Component-based architecture for building a fast and scalable app.
- **OMDb API:** Used to fetch movie data.
- **Local Storage:** Used to store user ratings and watched movie list.


## Installation

To run the app locally, follow these steps:
1. Clone the repository:
   git clone https://github.com/yordan-gergov01/usePopcorn.git
2. Navigate to the project directory:
   cd usePopcorn
3. Install the dependencies:
   npm install
4. Start the app:
   npm start


## How to use:

1. Enter a movie name in the search bar.
2. View the results with detailed information about each movie.
3. Click the stars to rate the movie.
4. Add movies to your "Watched Movies" list once you’ve rated them.
5. Manage your watched list by removing movies if needed.


## Future Improvements

- Add user authentication for storing and syncing data across devices.
- Improve search accuracy and expand filtering options (e.g., by genre or year).
- Integrate a real-time database for persistent movie lists and ratings.
