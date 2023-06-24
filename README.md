# RealTime RSP Classifier with TFJS
=================================

This repository contains code for a real-time Rock-Paper-Scissors (RPS) classifier using TensorFlow.js. The classifier uses a webcam to capture video input and TensorFlow.js to perform inference and make predictions.

Getting Started
---------------

To get started, follow these steps:

1. Clone the repository using the following command: 
    `git clone https://github.com/astrophile481/RealTime-RSP-classifier-with-TFJS.git`
2. Open the HTML file in a web browser.


Usage
-----

The web page consists of a video element that displays the webcam feed, along with buttons for different hand gestures (Rock, Paper, Scissors, Spock, and Lizard). The buttons are used to collect training data for each gesture.

Once you have collected enough training data, click the "Train Network" button to train the classifier. After training, you can click the "Start Predicting" button to make real-time predictions based on the webcam input.

To stop predicting, click the "Stop Predicting" button. If you are satisfied with your model, you can download it model.json by clicking the "Download Model" button.

Dependencies
------------

The following dependencies are used in this project:

- TensorFlow.js: `https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest`
- TensorFlow.js Visualization Library: `https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-vis`

Contributing
------------

Contributions to this project are welcome. Feel free to open issues or submit pull requests with improvements or bug fixes.

License
-------

This project is licensed under the [MIT License](LICENSE).

Acknowledgments
---------------

- The code in this repository is based on example and tutorials from the TensorFlow.js documentation.
