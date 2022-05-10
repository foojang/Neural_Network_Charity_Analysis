**Overview of the analysis**

Beks has asked us to use our knowledge of neural networks to create a binary classifier that can predict is applicants will be successful if funded by Alphabet Soup. We will be reviewing 34,000 organizations that have received funding from Alphabet soup. 

**Results** 

The target for the model is “Is Successful” 

The variables considered is App Type, Affiliation, Classification, Use Case, Org, Income, Ask, 

The variables that are not targets is EIN and Name 

I selected three hidden layers to try and increase accuracy. Many machine learning problems can be solved with only two layers. For this model I wanted to try and increase to layers but keep the neurons low. I was trying to avoid overfitting I included 15 neuron in the first layer, 10 neurons in the second, and 8 in the third.

I was not able to increase the accuracy by either increasing the Epochs or increasing the layers to the desired 75% The first model had a accuracy of 54% when I increase the layers and epochs the accuracy only went to 58% with increased layers and 57% with increased epochs. 
