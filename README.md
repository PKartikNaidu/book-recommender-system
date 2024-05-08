<h1>Book Recommender System</h1>
<br>
<p>
  This project is a book recommender system built using machine learning techniques for backend processing and HTML/CSS for the frontend interface. The system suggests books based on user searches and recommends additional books by the same authors or with similar themes. Each recommended book comes with a short description retrieved from the provided database.
</p>

<h3>Features</h3>

•⁠  ⁠Search Functionality: Users can search for books by title, author, or keyword.<br>
•⁠  ⁠Recommendation Engine: Recommends books based on user preferences and similarities in author or theme.<br>
•⁠  ⁠Book Details: Provides detailed information about each book, including a short description.<br>
•⁠  ⁠Responsive UI: Frontend interface designed using HTML and CSS, ensuring a user-friendly experience across devices.<br>

<h3>Dataset</h3>

The book data used in this project is sourced from Kaggle. The dataset includes a wide range of books with associated metadata such as title, author, genre, and description.<br>

<h3>Technologies Used</h3>

•⁠  ⁠Machine Learning: Python libraries like scikit-learn for building the recommendation engine.<br>
•⁠  ⁠Backend: Flask framework for serving the machine learning model and handling requests.<br>
•⁠  ⁠Frontend: HTML for structure and CSS for styling the user interface.<br>
•⁠  ⁠Data Storage: PostgreSQL database for storing and querying book data.<br>

<h3>How It Works</h3>

1.⁠ ⁠Search: Users can enter a book title, author, or keyword in the search bar.<br>
2.⁠ ⁠Processing: The backend system processes the user query and retrieves relevant books from the dataset.<br>
3.⁠ ⁠Recommendation: Based on the searched book or user history, the system recommends similar books using machine learning algorithms.<br>
4.⁠ ⁠Display: Recommended books are displayed on the frontend along with their descriptions and additional details<br>

<h3>Setup Instructions</h3>

1.⁠ ⁠Clone the Repository:<br>
   ⁠bash<br>
   git clone https://github.com/PKartikNaidu/book-recommender-system.git<br>
    ⁠

2.⁠ ⁠Install Dependencie:<br>
   ⁠bash<br>
   pip install -r requirements.txt<br>
    ⁠

3.⁠ ⁠Run the Application:<br>
   ⁠bash<br>
   python app.py<br>
    ⁠

4.⁠ ⁠Access the Application:<br>
   Open a web browser and go to ⁠ http://localhost:5000 ⁠ to use the book recommender system.<br>


<h3>Acknowledgement</h3>

Special Thanks to CampusX(Nitish Singh Sir) for inspiration and guidance.<br>


