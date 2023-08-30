# Captcha Reader
This repository provides full information on utilizing machine learning algorithms to perform tasks such as extracting text from images or retrieving information from captcha images. The comprehensive instructions are outlined within the notebook

# Dataset
I downloaded a dataset from Kaggle to train the model for capturing captchas. I also added a dataset called "sample". About 90% of the dataset is used for teaching the model and the remaining part helps us test and see how well the model performs.

# CRNN Architecture
We're using a special setup called CRNN to pull out text from captcha images. It's like a combination of two types of brain cells: one for recognizing picture parts and another for understanding the order these parts go in. So, first, the model spots important things in the image using the first type of cell (CNN). Then, the second type (RNN) helps the model figure out the correct order of these things. This way, CRNN makes it easier to read text from tricky images.

<img src="https://miro.medium.com/v2/resize:fit:1400/1*rzAN2Iq534Nt8hfd_Q8Afw.png">

# Log Model Performance
To see how good the model was getting, I used a tool called "weights and biases" (wandb). This let me look closely at different settings that control how the model learns. I went through each setting, tried out new ones, and adjusted things to make the model work well in different cases. I also explained about "weights and biases" in the notebook to make sure it's clear. You can view here how log works: https://wandb.ai/ai-viper/CAPTCHA-CRACKER?workspace=user-bishowlamsal233


