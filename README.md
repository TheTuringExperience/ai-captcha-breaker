# AI Captcha Breaker

This project uses a convolutional neural network trainied on images of "really simple captchas" to try to automate the process
of reading captchas like the one bellow:

![alt text](https://github.com/TheTuringExperience/captcha-breaker-ia/blob/master/test.png)

My assumption was that if the model could perform well on the really simple captcha letters it could do well on the ones like in the 
image above. This assumption was wrong. The model performance is suboptimal. I need to get new training data made up of captchas that are just like the one above. The rest of the pipeline works well. It extracts each letters of the image and preprocess it properly before feeding it into the model.

### Run the notebooks in the following order
- training_data_generator.ipynb
- model_definer.ipynb
- captcha_breaker.ipynb
