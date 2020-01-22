# ML-python-sklearn-svm-cpu-service

Quickstart project for executing a Iris classifier using the SciKit-Learn framework on a CPU.

Running pip install requirements.txt and then python `app.py` will start the app on localhost where the user can send GET requests to perform inference.

eg .../iris/{index} where index is in the range [0:150]

NOTE: this quickstart has an onnx model included. This is a placeholder model trained on Iris data and is not intended to be used by the user in production. Their own models will overwrite this, once trained.

