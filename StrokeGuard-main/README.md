# NeuroVigil
The World Health Organisation (WHO) reports that stroke is the second greatest cause of mortality worldwide and a major contributor to disability.Strokes claim the lives of about 5.5 million people annually, and survivors frequently suffer from long-term impairments that lower their quality of life. However, stroke can be avoided, and prompt action can have a big impact. 

Therefore, based on several physiological characteristics, I have developed a stroke prediction model that employs five different machine learning algorithms to determine the likelihood that a person would experience a brain stroke.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The NeuroVigil project is designed predict the probability of a person suffering from stroke based on their physiological attributes.

The machine learning algorithms which were employed in this project are Support Vector Machine (SVM), Random Forest, KNN, Naive Bayes, Decision Tree.  

This project is built using the Flask framework, which allows for easy deployment and interaction with the physiological attributes through a web interface. The frontend is developed using HTML, CSS, and JavaScript to provide a user-friendly experience.

## Technologies Used

The NeuroVigil project incorporates the following technologies:

- Random Forest Classifier
- Flask
- HTML
- CSS
- JavaScript
- And more...

## Installation

To set up the NeuroVigil project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Roohishaik/NeuroVigil.git
   ```

2. Navigate to the project directory:

   ```bash
   cd stroke prediction
   ```

3. Install the required dependencies using pip:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the Flask server:

   ```bash
   python app.py
   ```

5. Access the application by visiting `http://127.0.0.1:5000/` in your web browser.

## Usage

The main code for the Jupyter notebook can be found at `Stroke-final.ipynb`

1. Open the NeuroVigil web application in your preferred web browser.

2. Fill the physiologial attibutes which are asked for prediction

3. Click the "Submit" button.

4. Wait for the machine learning algorithms to process the input and predict whether you have the probability of getting a stroke.

5. Whether you are likely or not to get a brain stroke is predicted.


## Contributing

Contributions to the NeuroVigil project are welcome and encouraged. To contribute, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make the necessary modifications in your branch.

4. Test your changes to ensure they work as intended.

5. Submit a pull request with a detailed explanation of your changes.

## This is how the page looks:
![NeuroVigil](https://github.com/Roohishaik/NeuroVigil/assets/94975857/92492c0c-ffb8-45d8-aa86-9078a97cc3f8)


