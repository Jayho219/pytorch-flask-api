# PyTorch Flask API


## How to 

Install the dependencies:

    pip install -r requirements.txt


Run the Flask server:

    FLASK_ENV=development FLASK_APP=app.py flask run


From another tab, send the image file in a request:

    curl -X POST -F file=@cat_pic.jpeg http://localhost:5000/predict


