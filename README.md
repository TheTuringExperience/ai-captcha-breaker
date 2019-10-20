# captcha-breaker-ia

This project uses a convolutional neural network trainied on images of really_simple captchas to try to automate the process
of reading captchas like the one bellow:

![alt text](https://github.com/TheTuringExperience/captcha-breaker-ia/blob/master/test.png)

My assumption was that if the model could perform well on the really simple captcha letters it could do well on the ones like in the 
image above. This assumption was wrong. The model performance is suboptimal. I need to get new, better, training data. 
The rest of the pipeline works well. It extracts the letters of the image and preprocess it properly.
