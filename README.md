# Cat vs. Dog Image Classifier

An interactive web app that classifies images of cats and dogs. Built with Python, TensorFlow/Keras, and a user-friendly Streamlit interface. This was completed as part of the Accelerate Career Accelerator Program.



## Live Application Screenshots

Here is the model correctly identifying a cat and a dog.

| Cat Prediction | Dog Prediction |

| :---: | :---: |

| ![Cat Prediction Screenshot](cat-prediction.png) | ![Dog Prediction Screenshot](dog-prediction.png) |



## Features

- **Image Classification**: Classifies uploaded images of cats and dogs using a deep learning model.

- **Multiple Input Options**: Supports both file uploads and direct camera input.

- **Live Retraining**: Allows users to upload a ZIP file of new images to retrain and improve the model on the fly.

- **Performance Visualization**: Displays training and validation metrics after a retraining session.



## Technologies Used

- **Model**: TensorFlow, Keras

- **Web Framework**: Streamlit

- **Core Libraries**: Python, NumPy, Pillow

- **Plotting**: Matplotlib



## Setup and Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**

    ```sh

    git clone [https://github.com/ANGEL46-5/cats_and_dogs_image_classifier.git](https://github.com/ANGEL46-5/cats_and_dogs_image_classifier.git)

    cd cats_and_dogs_image_classifier

    ```

2.  **Create and activate a virtual environment (recommended):**

    ```sh

    python -m venv venv

    # On Windows: venv\Scripts\activate

    # On macOS/Linux: source venv/bin/activate

    ```


3.  **Install the required libraries:**

    ```sh

    pip install -r requirements.txt

    ```



## How to Run

After installing the requirements, run the Streamlit application with the following command:

```sh

streamlit run app.py
