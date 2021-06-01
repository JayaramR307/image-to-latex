# image-to-latex

## Flask Application

A flask application to convert math equation images to LaTeX markup.
## Installation

Requires Python 3.7+ & dependencies to run.

Install the requirements.

Download/Clone this repository
```python
cd image-to-latex 
pip install -r requirements.txt
```

## Using the application

Run the flask app
```python
cd image-to-latex 
python app.py
```

Go to localhost : 
```
http://127.0.0.1:5000/ 
```
Home screen will display: Veda Smart Math Solver

Append the base64 string of the image to url to get the LaTeX

```
http://127.0.0.1:5000/[base64 image string]
```

## Acknowledgment
 - [lukas-blecher/LaTeX-OCR](https://github.com/lukas-blecher/LaTeX-OCR)
 - [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
 
