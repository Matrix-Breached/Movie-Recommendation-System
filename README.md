# Movie Recommendation System 🎥

This is a Streamlit-based web application that provides movie recommendations based on content similarity. The system leverages vectorization, cosine similarity, and precomputed data stored in pickle files.

---

## **Features**
- Recommends similar movies based on user input.
- Simple and interactive UI built with Streamlit.
- Backend powered by vectorization and cosine similarity for calculating movie similarity.

---

## **Requirements**
- Python 3.7+
- Required libraries:
  - `streamlit`
  - `pandas`
  - `scikit-learn`
  - `numpy`

Install dependencies using:  
```bash
pip install -r requirements.txt
```

---

## **Files Included**
1. **`main.ipynb`**: Notebook to preprocess data and generate `movies_list.pkl` and `similarity.pkl`.
2. **`app.py`**: The main Streamlit app file.
3. **`Movies_data.csv`**: Dataset containing movie information.
4. **`movies_list.pkl`**: Pickle file storing processed movie data (not included).
5. **`similarity.pkl`**: Pickle file storing cosine similarity matrix (not included).

---

## **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/darshan-dalvi/Movie-Recommendation-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Movie-Recommendation-System
   ```
3. Generate pickle files:
   - Open and run the `main.ipynb` file to process the dataset and generate `movies_list.pkl` and `similarity.pkl`.

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## **Dataset**
- **`Movies_data.csv`** contains movie information used to compute recommendations.

---

## **Usage**
1. Run the Streamlit app.
2. Enter the name of a movie in the input box.
3. Get a list of recommended movies based on similarity.

---

## **Future Enhancements**
- Improve recommendation logic by including additional features.
- Support for hybrid recommendations (content + collaborative filtering).
- Include more datasets to expand movie recommendations.

---

## **Contributing**
Feel free to fork this repository and contribute by submitting a pull request.

---

## **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

Enjoy exploring your next favorite movie! 🍿
