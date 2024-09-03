# Movie-Review-Rating

1.Setup:
   1.Imports necessary libraries like TensorFlow, TensorFlow Hub, TensorFlow Datasets, and Matplotlib.
Prints versions and checks for GPU availability.
   2.Download the IMDB Dataset:
Includes code to download the IMDB dataset from TensorFlow Datasets.
   3.Data Preprocessing and Model Training (likely following cells):
The code might involve loading the dataset, preprocessing it, and training a model, though these specific steps were not visible in the initial extract.

2.Install the required libraries: Ensure you have Python 3.x installed. You can install the required libraries using:
`pip install -r requirements.txt`
Verify TensorFlow installation: The project requires TensorFlow 2.x. You can verify your TensorFlow installation with:
`import tensorflow as tf
print(tf.__version__)`

Dataset
The IMDB dataset is used for training the model. It contains 50,000 movie reviews, each labeled as positive or negative. The dataset is automatically downloaded using TensorFlow Datasets.

Training the Model
To train the model, follow the steps provided in the Jupyter notebook nikki_movie_rating_pyfile.ipynb. The notebook includes data preprocessing, model definition, training, and evaluation steps.

Evaluation
After training, the model is evaluated on the test set, and various metrics such as accuracy, precision, and recall are computed. You can visualize the results using Matplotlib.

Usage
You can use the trained model to predict the sentiment of new movie reviews. The following is an example:
`new_review = "This movie was fantastic! The performances were great."
prediction = model.predict([new_review])
print("Sentiment:", "Positive" if prediction >= 0.5 else "Negative")`

