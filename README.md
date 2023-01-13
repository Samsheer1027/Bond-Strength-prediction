# Bond-Strength-prediction





## Tech Stacks
- sci-kit-learn
- Gunicorn
- flask
- Heroku


## Model Training
I have added a detailed notes on the training and inference model in this [repository](https://github.com/Samsheer1027/Heart-disease-prediction).
>Here you can find complete zip file.

## Instructions

#### To run locally,

Clone this repository with ```git clone```.

pen a terminal inside the project directory.

Install dependencies using ```pip install -r requirements.txt```

Run ```python app.py``` to open the app on ```localhost:8000```.




### To Deploy in Heruko

1. Make sure you have all the requirements in ```requirements.py```.

2. Open a terminal on the project directory and create a heroku application using ```heroku create covid19-xray-detector```.

3. Since I use OpenCV Contrib Library, it requires ```libsm6 libxender1``` and it can be installed only though ```apt-get```. So we import buildpack in ```heroku, use heroku buildpacks:add --index 1 heroku-community/apt```.

4. Now you are all set to go, deploy with a single command ```git push heroku master```.
