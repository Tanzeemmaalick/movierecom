
# Movie Recommender System

![Movie Recommender System](movie_recommender.png)

The Movie Recommender System is a Python application that utilizes a recommendation algorithm to suggest movies based on user input. It is built using the Pandas library for data manipulation, Streamlit for creating a user interface, and the Pickle library for loading pre-trained models.

## Getting Started

1. Install the required libraries:

   ```
   pip install pandas streamlit requests
   ```

2. Clone the project repository:

   ```
   git clone https://github.com/your-username/movie-recommender.git
   cd movie-recommender
   ```

3. Run the Streamlit app:

   ```
   streamlit run movie_recommender.py
   ```

## How it Works

The Movie Recommender System uses a pre-trained model to calculate similarity between movies based on their features. The dataset used for this model contains movie titles, IDs, and other relevant information. The system fetches movie posters using The Movie Database (TMDb) API to display them along with the recommended movie titles.

## Features

- Select a movie from the provided dropdown menu.
- Click the "Recommend" button to get movie recommendations.
- The system will display five recommended movies with their posters.

## Data Sources

The project uses two datasets:

1. **movies_dict.pkl**: A pickled dictionary containing movie information, including movie titles, IDs, and other attributes.

2. **similarity.pkl**: A pickled similarity matrix that represents the similarity between movies based on their features.

## Requirements

- Python 3.x
- Pandas
- Streamlit
- Requests

## Contributions

Contributions to the project are welcome. If you have any suggestions or find any issues, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Contact

For any questions or feedback related to the Movie Recommender System, please contact:

- Name: [Tanzeem Mallick]
- Email: [tanzeemmallick26@gmail.com]
- 

Thank you for using the Movie Recommender System. We hope you enjoy discovering new movies with our recommendations!
```

Please ensure to replace `[Your Name]` and `[Your Email]` with your actual name and email address in the "Contact" section. Save this text as "README.md" in the root directory of your project. Also, consider adding a suitable image (e.g., `movie_recommender.png`) that represents your Movie Recommender System and add it to the repository.
