# Change Coder

# Abstract
This is a work-in-progress repository for training a model that is capable of determining if a token in a piece of code is correct or if it needs to be changed. This will be achieved by training on git commits rather than the code itself. This provides a different arrow of time and prediction direction, thus having different strengths and weaknesses than the popular autoregressive methods. This could potentially lead to synergetic effects between the two models.

# Background
## How autoregressive models are trained
