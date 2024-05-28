# Waste Segregation Using Deep Learning Models
This project is a web application that performs waste segregation using deep learning models. It utilizes the VGG16, ResNet50, and Xception models for image classification to identify different types of waste. A comparative analysis was conducted to determine the model with the best accuracy, which is then used for the final implementation in the web application. The application allows users to upload images of waste, processes them through the selected model, and classifies the waste into categories.

## Features
- Conduct comparative analysis of VGG16, ResNet50, and Xception models to determine the best-performing model.
- Use the model with the highest accuracy for waste classification in the web application.
- Upload images of waste for classification.
- Display the classification results along with confidence scores.

## Installation

### Clone the repository:
```sh
git clone https://github.com/your-username/waste-segregation.git
```

## Usage

1.Start the Flask server:
   ```sh
   python index.py
   ```
2.Open your browser and navigate to:
```sh
http://localhost:5000
```

## File Structure

- `Dataset/`
  - `cardboard`: Images of cardboards.
  - `glass`: Images of glasses.
  - `metal`: Images of metals.
  - `paper`: Images of papers.
  - `plastic`: Images of plastics.
- `Resources/`
  - `Model/`
    - Contains the .csv files of all the model history which will be used for making Prediction's.
- `templates/`
  - `index.html`: Main page where users upload the image to get the prediction.
  - `main.html`: Cover webpage which leads to `index.html`.
  - `main.css`: CSS file for styling the `index.html` and `main.html` pages.

## Dependencies

- TensorFlow: Library for deep learning.
- Flask: Web framework for Python.
- NumPy: Library for numerical computations.

## How to Use

1. When the application starts, you will be prompted to upload an image. Browse through your desktop and select an image of waste.
2. Press the "Submit" button to upload the image to the backend for processing.
3. Once the results are visible, if you want to check the probabilities of each class, press the "View Details" button to toggle the probabilities.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Author

- A S Abhishek - [GitHub](https://github.com/abhishek12345678900987654)

---
