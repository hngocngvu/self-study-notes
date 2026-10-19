## Definitions
- ML= study of algorithms learning from experience (observational data, environment interactions)

- approach to ML: define a flexible program determining behaviors by params

- fixed params -> program= model

- model family = distinct programs (I-O mappings) producing by manipulating params 

- learning algorithm= meta-program using the dataset to **choose params** 

## Key components 
![Training process](img/training_process.png)

1. Data
- features= input (special: target= output)
- can be varying-length
- mistaken -> poor predictive performance, un-/under-represented groups (bias)

2. Models
- model: computational machine ingesting data -> output= prediction
- statistical models: params estimated from data
- deep learning models: chained, successive data transformations- multiple layers

3. Objective functions
- measure model performance (good/bad) 
- usually the lower the better -> loss functions
- regression: common loss function= squared error
- classification: objective= minimize error rate
    + but difficult to optimize directly (different probs but same results, non-differentiable)
    
    -> optimize surrogate objective

- overfitting= well-performed on training set but fails to generalize to unseen data

4. Optimization algorithms
- search for the best params for minimizing loss function
- popular: gradient descent
