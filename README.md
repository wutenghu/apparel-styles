# Apparel Classification App

Predict multiple attributes for a given apparel. This app was developed during Insight AI Fellowship in March'2017.  The app was developed using Python and uses PyTorch deep learning framework and Tordado web server.

[Slides](http://sampathweb.com/apparel-styles/)

## Setup Environment on Local Machine

### Env-dependencies

````
python=3.5.2
torch=0.3.1
numpy=1.14.5
````

### Train model & run inference service

```
git clone https://github.com/sampathweb/apparel-styles
# cd apparel-styles

# Build the Model
python ml_src/build_models.py

# Run the App
python run_server.py
````

### Test App

Open Browser:  [http://localhost:port](http://localhost:port)


## Dataset:

H. Chen, A. Gallagher, B. Girod, "Describing Clothing by Semantic Attributes", European Conference on Computer Vision (ECCV), 2012.

