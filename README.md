# GANILLA
GANILLA is a type of GAN (Generative Adversarial Network) that solves the image-to-image translation problem, in the domain of children’s book illustrations. In practice, when you provide a photograph to a trained GANILLA model, it will output an illustration of the input image, based on the style of a specific illustrator.
This repository is the implementation of the GANILLA paper, coded by Liron Soffer, Dafna Mordechai and Lior Dagan Leib. 

![alt text](https://miro.medium.com/max/2400/1*PH67577GfyEBWZRNEGVZWA.jpeg)

For the training process, we used the same landscape images GANILLA used as our source domain. For the destination domain, we choose the works of Hayao Miyazaki, which we scraped from the web. In the picture above you can see the GANILLA model in action. The top images are the original photographs, and the bottom ones are the model’s output illustrated image


Want to learn more about GANILLA? This blog-post is for you:
https://towardsdatascience.com/ganilla-fantasy-enhanced-d4918681820c

