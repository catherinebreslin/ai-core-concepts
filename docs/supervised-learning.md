# Supervised Learning


## What is supervised learning?

Supervised learning is one of the most widely used types of machine learning. Supervised models predict an output for a given input. Our job is to define what the input and output are, and train the model to do a good job at the prediction. 

![Supervised Learning](imgs/sup1.png){ align=center }

In supervised learning, models are trained on a dataset that's been labelled with the labels that you would like the model to predict. One example is of spam email detection, where we would like to predict whether an email is spam or not.

![Spam Email Detection](imgs/sup2.png){ align=center }

Supervised learning can either be **classification** or **regression**.

**Classification** is where the output is one of a fixed number of categories. This could be a binary classification task where there are exactly two possible outputs, like the example of spam email. There could be multiple categories, likerecognising the person in an image, like your phone might do. Even more, in some scenarios, an input might have multiple output labels, which is called _multi-label classification_, e.g. an image might have multiple people in it.  

**Regression** is where the output is a continuous number rather than a discrete class. Examples might be...

Other examples of supervised learning tasks include:

| Task | Input | Output |
| ---- | ----- | ------ |
| Automated transcription | Audio files | Written transcription |
| Machine translation | Text in the source language | Text in the target language |



## Training supervised models

Training a supervised learning algorithm involves:

1. decide on the task and collect data
2. label that data
3. train a model on a 'training' set of your data
4. evaluate the model on a separate test set, to see how well it does
5. investigate the errors to see where you can improve

This tends to be an iterative process, not a linear one, so you may need to loop through these steps several times to get a model that works. 

Popular supervised learning algorithms include logistic regression, decision trees, support vector machines, neural networks.




## Top Tips for getting started

1. Start with a small model and a simple baseline
2. Start with a small dataset, before increasing the amount of data
3. Ensure there's no leakage between your test and training data
4. Make use of open source libraries, models and data

## Inspiration

Find more examples of research that's using supervised learning on Accelerate's blog:

- link
- link
- link


## Contact

Don't see what you need? 

[CONTACT US :fontawesome-solid-paper-plane:](mailto:accelerate-mle@cst.cam.ac.uk){ .md-button }




