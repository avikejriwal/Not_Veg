# Not_Veg

This is a model trained on VGG16's architecture in TensorFlow/Keras to identify images of food by dietary restriction (vegan, dairy, meat).

### Image Scraping
Imgur API: [imgurpython](https://github.com/Imgur/imgurpython)  
Pixabay API: [python_pixabay](https://github.com/faraco/python-pixabay)  
Google Images: https://gist.github.com/genekogan/ebd77196e4bf0705db51f86431099e57

### Files
`Transfer Learning.ipynb`: Retrain VGG on my food image data  
`predict_image.ipynb`: Load the model and run predictions for an image file  
`model.h5`: the final trained model
