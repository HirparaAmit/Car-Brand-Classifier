# Car-Brand-Classifier

I create this project just to learn about how we can use Flask API to deploy our deep learning model on web app. I used ResNet50 architecture from keras to classify brand name of cars and also I used ImageNet's weights so that I don't need to train complete model.

I just add 3 car brand classes (Audi, Lamborghini and Mercedes) and not use any big dataset. In fact I create this dataset by myself. I know that this dataset is very small for any deep learning model but as I already said that in this project I just focused on how to create flask API for the model.

If you want to run my code then you just need to download this repo and first run the `Car-Brand-Classifier.ipynb` file so that trained model will save in `.h5` file. Then you just need to run `app.py` file and it will give you the url where the web app will running.

Note : Don't focus on the design of web app. I already said that I want to learn just flask API from this project.
