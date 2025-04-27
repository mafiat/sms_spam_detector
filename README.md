# SMS Spam Classification App

This project is an SMS Spam Classification application that uses machine learning to classify text messages as either "spam" or "not spam". The application is built using Python, Scikit-learn, and Gradio for the user interface.

## Features

- **Machine Learning Model**: The app uses a pipeline with TF-IDF vectorization and a Linear Support Vector Classifier (LinearSVC) for classification.
- **Interactive Interface**: A Gradio-based interface allows users to input text messages and receive predictions in real-time.
- **Dataset**: The app is trained on the "SMSSpamCollection" dataset, which contains labeled SMS messages.

## How It Works

1. **Data Preprocessing**: The dataset is loaded and split into training and testing sets.
2. **Model Training**: A pipeline is created with TF-IDF vectorization and LinearSVC, and the model is trained on the training data.
3. **Prediction**: The trained model predicts whether a given text message is "spam" or "not spam".
4. **User Interface**: Users can input text messages into the Gradio interface to get predictions.

## Files

- **SMSSpamCollection.csv**: The dataset used for training and testing.
- **Jupyter Notebook**: Contains the code for data preprocessing, model training, and Gradio interface setup.
- **README.md**: This file, providing an overview of the project.

## How to Run

1. Clone the repository and navigate to the project directory.
2. Install the required dependencies:
    ```bash
    pip install pandas scikit-learn gradio
    ```
3. Open the Jupyter Notebook and run all cells to train the model and launch the Gradio app.
4. Use the Gradio interface to test the app by entering text messages.

## Example Messages to Test

1. "You are a lucky winner of $5000!"
2. "You won 2 free tickets to the Super Bowl."
3. "Thanks for registering. Text 4343 to receive free updates on medicare."

## Dependencies

- Python 3.x
- Pandas
- Scikit-learn
- Gradio

## Acknowledgments

- The "SMSSpamCollection" dataset used in this project is publicly available and widely used for spam classification tasks.
- Gradio for providing an easy-to-use interface for machine learning applications.

## License

This project is licensed under the MIT License.