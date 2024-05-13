# Movie Recommendation App

This project is a movie recommendation app built using Streamlit. It utilizes cosine similarity to recommend movies similar to a user-input movie. The app loads a dataset containing movie information, including genres, keywords, tagline, cast, and director. It then calculates the similarity between movies based on their combined features and recommends movies with high similarity scores.

## Steps to Run the Application

1. **Clone the Repository**: Clone the repository containing the code for the application.

2. **Install Streamlit**: If you haven't already, install Streamlit by running `pip install streamlit`.

3. **Install Dependencies**: Navigate to the project directory and install the required dependencies by running `pip install -r requirements.txt`.

4. **Run the Application**: Use the command `streamlit run app.py` to start the Streamlit application.

5. **Interact with the Application**: Once the application is running, you can interact with it in your web browser. Enter the name of your favorite movie in the input field and click the "Recommend" button to see a list of recommended movies based on the similarity to your input movie.

6. **View the Recommendations**: The application will display a list of recommended movies. Each movie is ranked based on its similarity to your input movie, with the most similar movies appearing first.

7. **Try Different Movies**: You can enter different movie names and click the "Recommend" button again to see how the recommended movies change based on your input.

8. **Note**: Make sure to have the `movies.csv` file available in the same directory as `app.py`, as the application loads this file to recommend movies.
