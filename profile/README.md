# CaptchaOCR

This is an open-source project to solve 1st gen Captcha.  

Images can be uploaded through a webpage which are then passed through  
a trained neural network. Results are then sent back to the user.  


## Roadmap

### Neural Network:
- Build/Tune/Train NN using PyTorch using Uses [Captcha Dataset](https://www.kaggle.com/datasets/parsasam/captcha-dataset).
- Setup Captcha generation for frontend samples: [PHP Captcha](https://github.com/Gregwar/Captcha)


### Backend:
- Built using Django Framework
- Will use REST standard
- Debug options
- Deploy through a Docker container

### Frontend:
- Build Single Page Application using React
- Upload/generate Captcha images, send securely to API
- Deploy through a Docker container 
