# Tutorial: Introduction to NLP with Python

The Tutorial will give you a basic introduction to Natural Language Processing. Diskussed topics are: pre-processing the text, different representations as vectorization of words, training a ML model on text data.

The code is written in python. It is preferrable to use python3.6, since the library dependencies have been verified with v3.6.
Other higher versions also should work fine.

It is highly recommended to use `virtualenv` for installing packages, as it won't disturb your existing package versions.
You could also try `conda`, if you are comfortable with it.

### Installation instructions:

1. Install [python](https://www.python.org/downloads/), if you don't have it yet.

2. Open powershell/cmd/conemu of your choice.

3. Check `virtualenv -v`. If the package is not installed, execute `pip install virtualenv`

4. Create a virtual environment. `virtualenv -p python env36` (Make sure python points to python3 not python2)

5. Activate the environment. `env36\Scripts\activate`

6. Clone this repository. `git clone https://github.com/chmodsss/nlp-tutorial`

7. Enter the folder. `cd nlp-tutorial`

8. Install the requirements. `pip install -r requirements.txt`

9. After installation, execute `jupyter notebook`

10. Now the notebooks are up and running in your browser at `localhost:8888`


#### NLTK packages
NLTK library needs some pre-built models to be to loaded to execute certain functions

Open a python interpreter and execute the following commands.

`> import nltk`

`> nltk.download('punkt')`

`> nltk.download('wordnet')`
