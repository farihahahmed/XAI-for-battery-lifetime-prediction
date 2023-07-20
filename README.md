# Novel explainable AI for predicting battery lifetime: comparable accuracy to state- of-the-art black-box models

Authors: Farihah Ahmed, Mauricio Hernandez

- WHY? Battery lifetime prediction is a critical problem for electric vehicle (EV) users’ range maximization and battery manufacturers’ faster research and development (R&D). While a growing subfield of accurate AI has been applied to predict the nonlinear degradation mechanisms of batteries, there is a lack of explainable AI (XAI) in the field, inhibiting the deployment of these models due to missing trust and confidence from end- users in the models’ black-box decision-making.

- GOAL: Build an XAI model using the ‘explainable’ concept of Euclidean Distance that would overcome the accuracy-explainability tradeoff. Create an improved, deployable battery lifetime prediction model that's both accurate AND explainable to battery R&D manufacurers/researchers and EV users
  

- APPROACH: 3 different XAI models. 4 different data splits. 4 tasks: 1 regression, 3 classification. Hyperparameter tuning.

- RESULTS: lowest classification error is 4% (better than current state-of-the-art models) and lowest regression Mean Percent Error is 11.8% (comparable to state-of-the-art models).

- IMPLICATIONS:
  (1) overcome accuracy-explainability tradeoff in XAI field with novel XAI models built from scratch
  (2) reveal greater insights about how battery lifetime is determined--helping battery manufacturers accelerate the R&D process
  (3) increase trust battery manufacturers and EV consumers using this model--overcoming a massive barrier to the wider deployment of Lithium-ion batteries
  (4) call for greater deployment of XAI in all fields (we demonstrate that it is indeed possible to have both explainable and accurate AI, in order to increase societal trust in AI.
