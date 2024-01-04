# Machine Learning Projects

This repository contains various machine learning projects that showcase different aspects of machine learning, from data preprocessing to model evaluation. Each project is designed to provide insights into different machine learning techniques and applications.

Feel free to explore, modify, and use the code for your own projects. If you have any questions or suggestions, don't hesitate to reach out!

## Project 1: Music Genre Prediction

### Overview

This project predicts music genres using a Decision Tree Classifier based on features such as age and gender. The dataset (`music.csv`) is a sample dataset used to train and evaluate the model.

### Usage

1. Ensure Python is installed.
2. Install required libraries: `pip install pandas scikit-learn`.
3. Clone the repository or download `music.csv`.

```bash
git clone https://github.com/yourusername/music-genre-prediction.git
cd music-genre-prediction
python music_genre_prediction.py
```

### Code Explanation

- Uses `pandas` to read the dataset and prepare data.
- Splits the dataset into features (`X`) and target variable (`Y`).
- Divides the dataset into training and testing sets using `train_test_split`.
- Utilizes a Decision Tree Classifier for building the predictive model.
- Prints accuracy score and compares actual genres (`Y_test`) with predicted genres.

### Requirements

- Python
- pandas
- scikit-learn


## Project 2: Alternative Music Genre Prediction

### Overview

An alternative version of the Music Genre Prediction project, using a Decision Tree Classifier to predict music genres based on provided features.

### Usage

1. Ensure Python is installed.
2. Install required libraries: `pip install pandas scikit-learn`.
3. Clone the repository or download `music.csv`.

```bash
git clone https://github.com/yourusername/music-genre-prediction.git
cd music-genre-prediction
python music_genre_prediction_alternative.py
```

### Code Explanation

- Uses `pandas` to read the dataset and prepare data.
- Splits the dataset into features (`X`) and target variable (`Y`).
- Divides the dataset into training and testing sets using `train_test_split`.
- Utilizes a Decision Tree Classifier for building the predictive model.
- Calculates and prints the accuracy score.

### Requirements

- Python
- pandas
- scikit-learn


## Project 3: Music Genre Decision Tree Model

### Overview

This script trains a Decision Tree Classifier to predict music genres based on provided features such as age and gender. The dataset (`music.csv`) is used to train the model.

### Usage

1. Ensure Python is installed.
2. Install required libraries: `pip install pandas scikit-learn joblib`.
3. Clone the repository or download `music.csv`.

```bash
git clone https://github.com/yourusername/music-genre-prediction.git
cd music-genre-prediction
python music_genre_decision_tree.py
```

### Code Explanation

- Uses `pandas` to read the dataset and prepare data.
- Splits the dataset into features (`X`) and target variable (`Y`).
- Instantiates and trains a Decision Tree Classifier using the entire dataset.
- Includes commented-out code for saving and loading the model using `joblib`.
- Exports the Decision Tree as a `.dot` file using `export_graphviz` from `scikit-learn`'s `tree` module.

### Requirements

- Python
- pandas
- scikit-learn
- joblib
- Graphviz (for visualizing the Decision Tree)

### Visualizing the Decision Tree

To visualize the Decision Tree, you can use Graphviz. If you haven't installed it, you can download it from the official website: [Graphviz Download](https://graphviz.gitlab.io/download/).

After installation, you can use the following command to convert the generated `.dot` file to a visual format (e.g., PNG):

```bash
dot -Tpng ms_recommender.dot -o ms_recommender.png
```

### Author

- John Muhura
- Contact: [mail](mailto:jowamumjwesh@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/john-muhura-165b83294/)
- [GitHub](https://github.com/mj-weshh)

---
