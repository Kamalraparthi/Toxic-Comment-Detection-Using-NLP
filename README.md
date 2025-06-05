# _Toxic Comment Classification Using NLP:_

This project builds a multi-label classification model to detect various forms of toxic comments such as obscene, identity hate, insult, and more using NLP techniques and deep learning.


## Project Goal:

- To preprocess user comments, balance class labels, and train a deep learning model to classify multiple types of toxic behavior in text.
- To reduce the spread of toxic language in online forums and social media by enabling automated moderation through AI.



## Project Structure:

- Toxic Comment Classifier.ipynb (Main Jupyter notebook with full pipeline)
- contractions.py (Handles expansion of English contractions)
- nlp_utils.py (Contains reusable NLP preprocessing functions)
- train.csv (ignored-Dataset uploaded separately)
- .gitignore (File to ignore large datasets)
- README.md (Project documentation)


## Dataset:

- **Source**:[Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge)
- **Columns**:"toxic", "severe_toxic", "obscene", "threat", "insult", "identity_hate".
- **Size**:~65MB CSV file
- **Download**:[Google Drive Link](https://drive.google.com/file/d/1xqPGhLRDagrdHDyYJkA2soao_Zb4i4VN/view?usp=drive_link) 
"train.csv" is excluded from the repository due to GitHub's file size limitations. Please download and place it in your local folder.


## Features and Workflow:

**Text Cleaning**
- Removing punctuation, lowercasing, handling contractions.
**Custom NLP Utility Scripts**
- "contractions.py" and "nlp_utils.py".
**Data Balancing**
- Addressing class imbalance for better model performance.
**Model Architecture**
- LSTM / Bidirectional LSTM.
**Evaluation**
- F1 Score, classification report, visualization of label distribution.


## Tools & Technologies:

1. Python
2. Jupyter Notebook
3. Pandas, NumPy
4. NLTK, spaCy
5. TensorFlow / Keras
6. Scikit-learn
7. Matplotlib, Seaborn


## What I Learned:

- How to prepare text data for deep learning.
- Handling multi-label classification problems.
- Writing modular Python code for NLP.
- Visualizing and interpreting class imbalances.


## How to Run:

1. Clone the repository:
   git clone https://github.com/Kamalraparthi/Toxic-Comment-Detection-Using-NLP.git
   cd Toxic-Comment-Detection-Using-NLP

2. Download the dataset from the link above and place it as train.csv in the root directory.

3. Install dependencies: pip install -r requirements.txt

4. Open the notebook: jupyter notebook "Toxic Comment Classifier.ipynb"


## License:

This project is for educational purposes. Attribution to the [Jigsaw competition](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge) is appreciated.


## Acknowledgements:

- Kaggle & Google for hosting the dataset.
- TensorFlow, NLTK, and other open-source tools that made this project possible.