# 🎵 Music Genre Prediction Model using Decision Tree

This project builds a machine learning model to predict a person's favorite **music genre** based on their **age** and **gender**. It uses a **Decision Tree Classifier** to make predictions, and includes saving and loading the trained model for future use.

---

## 📂 Project Structure

music-genre-prediction-model/
│
├── music genre predection project.ipynb # Main Jupyter notebook
├── music.csv # Dataset
├── model.joblib # Saved model (after training)
└── README.md # Project description


---

## 📊 Dataset Description

The dataset `music.csv` includes:

| Feature | Description        |
|---------|--------------------|
| `age`   | Age of the person  |
| `gender` | Gender (male/female) |
| `genre` | Target variable (e.g., rock, jazz, pop) |

---

## 🔍 Goal

To classify the music genre a user prefers based on demographic features using a supervised machine learning model (Decision Tree Classifier).

---

## 🔁 Workflow

1. **Load the dataset**
2. **Preprocess the features** (`age`, `gender`)
3. **Train** a Decision Tree Classifier
4. **Save** the trained model using `joblib`
5. **Load** the saved model
6. **Predict** the genre for new input data

---

## 🧠 Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas & NumPy
- scikit-learn (DecisionTreeClassifier)
- joblib (for saving/loading model)

---

## 🚀 How to Run

1. Clone this repo or download the files.
2. Open `music genre predection project.ipynb` in Jupyter.
3. Run the notebook cells step-by-step.
4. To test predictions on new data, use the model loading section at the end of the notebook.

---

## ✅ Example Output

python
# Predicting for a 21-year-old male
model.predict([[21, 1]])
# Output: ['HipHop']


🗂️ Future Improvements
Expand dataset with more features (e.g., location, time of listening)

Try other classifiers (Random Forest, KNN, etc.)

Add a simple UI for user input

📬 Contact
If you have any questions or suggestions, feel free to reach out!
📧 Email: mosbah47messaoud@gmail.com
🔗 LinkedIn: linkedin.com/in/mosbah-messaoud-338a10301
💻 GitHub: @mosbahmessaoud

Messaoud Mosbah


