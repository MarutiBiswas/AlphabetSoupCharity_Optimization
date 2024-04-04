Step 4 : Writing a Report on the Neural Network Model _ Alphabet Soup Charity Analysis Report:

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.
The report should contain the following:

Q1- Overview of the analysis: Explain the purpose of this analysis.

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using machine learning and neural networks, we use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
Q2- Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?

Our target is the "y" which is the "IS_SUCCESSFUL" column

What variable(s) are the features for your model?

Our features is the "X" which is everything but the "IS_SUCCESSFUL" column as: "APPLICATION_TYPE" , "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"

What variable(s) should be removed from the input data because they are neither targets nor features?

"EIN & "NAME" were removed from variables, since they are neither targets nor features.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

I had 3 tries trying to get to best & highest accuracy

1st try: 2 hidden layers & an outer layer, layer 1: 80 neurons, tanh activation, layer 2: 30 neurons, sigmoid activations, and Outer layer: 1 unit, sigmoid activation & adam optimizers for complier.

2nd try: 3 hidden layers & an outer layer, layer 1: 85 neurons, tanh activation, layer 2: 35 neurons, sigmoid activations, layer 3: 10 neurons, relu activations, and Outer layer: 1 unit, sigmoid & adam optimizers for complier.

3rd try: 3 hidden layers & an outer layer, layer 1: 75 neurons, tanh activation, layer 2: 25 neurons, sigmoid activations, layer 3: 20 neurons, sigmoid activations, and Outer layer: 1 unit, sigmoid & adam optimizers for complier.

Were you able to achieve the target model performance? The best I got accuracy 0.7246

What steps did you take in your attempts to increase model performance? after cleanining & removing none features neither targets, & splitting used the deep neural net & trying diffrent number of layers, activations, optimizers & epochs

Q3- Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation:

<img width="468" alt="image" src="https://github.com/MarutiBiswas/AlphabetSoupCharity_Optimization/assets/147889069/716b0013-4ea6-4752-8c77-04d7452af4a4">
<img width="468" alt="image" src="https://github.com/MarutiBiswas/AlphabetSoupCharity_Optimization/assets/147889069/9bee0bdc-0fdf-447c-a7ca-340d65c1698e">
<img width="448" alt="image" src="https://github.com/MarutiBiswas/AlphabetSoupCharity_Optimization/assets/147889069/edc4fd08-4e3c-491b-8b06-fdc09b1e2bff">
<img width="468" alt="image" src="https://github.com/MarutiBiswas/AlphabetSoupCharity_Optimization/assets/147889069/00b98bfb-0000-4568-99ed-d46d17ce84ec">
<img width="468" alt="image" src="https://github.com/MarutiBiswas/AlphabetSoupCharity_Optimization/assets/147889069/41d543e6-6dce-4475-9f61-66c1c2816692">
<img width="468" alt="image" src="https://github.com/MarutiBiswas/AlphabetSoupCharity_Optimization/assets/147889069/1bc4a7c7-b3fe-4f80-a439-055b1a9d3f08">
