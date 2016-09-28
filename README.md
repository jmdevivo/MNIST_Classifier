This project attempts to utilize classify images of hand-drawn integers rangin from 1 to 9 using a Support Vector Machine.
The scikit-learn library (http://scikit-learn.org/stable/index.html) is used to create, fit, and us the SVM model.

To Run:

1) Install all Python Packages specified in requirements.txt (pip install -r requirements.txt)

2) Change directory to image_classifier/python-mnist/main/ (cd image_classifier/python-mnist/main/)

3a) To run with existing models serialized in pkl format run classify.py with no arguments (python classify.py)

3b) To train a new model, delete all pkl files in image_classifier/python-mnist/main/ and run classify.py with makemodel arg (python classify.py makemodel)


-John Devivo
