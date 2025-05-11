# Movie Recommender System
A Content-Based Recommender System built with Python, featuring a Streamlit frontend and deployed on Heroku. This project allows users to explore and discover movies based on their preferences using content similarity.

## Project Overview
This Movie Recommender System suggests movies based on similarity in genres, keywords, overview, cast, and crew. It utilizes natural language processing (NLP) techniques to calculate similarity scores and deliver content-based recommendations.
<ol>
  <li>✅ Streamlit Web App</li>
 <li>✅ Content-Based Filtering</li>
 <li>✅ Cosine Similarity with TF-IDF</li>
 <li>✅ Responsive UI</li>
 <li>✅ Deployed on Heroku</li>

</ol> 

## Features
<ol>
  <li>🔎 Search for a movie and get top 5 similar recommendations</li>
  <li>📚 Content-based filtering using metadata (cast, crew, overview, genres)</li>
   <li>🧠 TF-IDF Vectorization and Cosine Similarity</li>
  <li>⚡ Interactive UI using Streamlit</li>
  <li>☁️ One-click deployment with Heroku</li>
</ol> 

## Dataset
This project uses a simplified version of the TMDb 5000 Movie Dataset, including:

1.Title
2.Overview (Plot)
3.Genres
4.Keywords
5.Cast & Crew (optional for enhancement)

### Installation
1. Clone this repository to your local machine:  
   ```bash
   git clone https://github.com/Gpm_Musfik/Movie-Recommender-System.git
   ```
2. Create a virtual environment:  
   ```bash
 python -m venv venv
source venv/bin/activate 
   ```
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
4. Run the app locally:  
   ```bash
   streamlit run app.py

   ```

### Heroku Deployment
Make sure you have the following files for Heroku:

-Procfile
-requirements.txt
-setup.sh (if needed)
-app.py

Deploy using the Heroku CLI:
  ```bash 
-heroku login
-heroku create movie-recommender-streamlit
-git push heroku main
-heroku open

 ```

## Future Improvements
* Add user ratings and collaborative filtering
* Integrate with TMDb API for real-time data
* Improve recommendation logic with advanced NLP (BERT, spaCy)
* Add genre/category filters for finer control

## Contributing
Feel free to fork the project and submit a pull request. For major changes, please open an issue first. If you like this project, please ⭐ the repository to show your support and follow for more projects!

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  
  
