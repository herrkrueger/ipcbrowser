# Requirements

- Python3 (and PIP3)
- docker
- home brew (package manager for local run with postgresql)

# Installation from pip (local run):

$ git clone https://gitlab.mtc.berlin/jet/patent-classification-browser.git

$ pip3 install -r requirements.txt

$ python3 app.py


# Installation from docker :
$ git clone https://gitlab.mtc.berlin/jet/patent-classification-browser.git

$ docker build -t patclass-image .

$ docker run -d --name patclass -p 5000:5000 patclass-image

The app can be reached in your browser at `http://0.0.0.0:5000`.


