# This is a repo for Banana (Fresh/Stale) classification


This application uses MaskRCNN library from https://github.com/matterport/Mask_RCNN

Create a virtual environment with banana_test_env.yml to run the scripts

custom_banana.py file is for training and evaluation of the model. 80 images are used for training and 20 images are used for validation. Training and Validation data is not provided in this Github repo. You can create your own database or can ask me @ p.karmakar87@gmail.com
Please download  mask_rcnn_coco.h5 to facilitate the transfer learning

custom_banana1.py file is used for inference/testing   

custom_banana_streamlit.py file is required to build the web app.
