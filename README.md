# ASL_Translator
This project uses the Sign Language MNIST data set downloaded from Kaggle https://www.kaggle.com/datasets/datamunge/sign-language-mnist

I am well aware of the irony of using ASL, when I'm based in the UK. This is due to the fact that ASL has a very large, very well known data set that is freely available. BSL on the other hand, does not. There is, the BBC-Oxford BSL dataset, which would be large enough to support machine learning, but this is not freely available. Access is seemingly only granted for research use. 

NB: camera.py WILL NOT RUN on Windows Subsystem for Linux - this is a... feature of WSL, rather than a bug within the code. The code has been tested on, and will run in PyCharm Community edition on Windows 10. If it complains that CV2 hass not been defined, do not install opencv-python-headless. This version of opencv again causes the code to error for reasons I do not understand. 
