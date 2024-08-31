$ git clone https://github.com/yasuo72/chatbot.git
$ cd chatbot-deployment
$ python -m venv venv
$ . venv/bin/activate



$ (venv) pip install Flask torch torchvision nltk

$ (venv) python
>>> import nltk
>>> nltk.download('punkt')

$ (venv) python train.py


$ (venv) python chat.py


to run flask - python app.py
