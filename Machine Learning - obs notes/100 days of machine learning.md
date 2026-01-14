### Difference between Conventional and Instance based learning 

| Usual/Conventional machine learning                                                | Instance Based learning                                                                                   |
| ---------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| prepare the data for model training                                                | Prepare the data for model training                                                                       |
| Train model from training data to estimate model parameters i.e. discover patterns | Do not train model. Pattern discovery postponed until scoring query received                              |
| Store the model in suitable form                                                   | There is no model to store                                                                                |
| Generalize the rules in form of model, even before scoring instances is seen       | No generalization before scoring. Only generalize for each scoring instance individually as and when seen |
| Predict for unseen scoring instance using model                                    | Predict for unseen scoring instance using training data directly                                          |
| Can throw away input/training data after model training                            | Input/training data must be kept since each query part or full set of training observations               |
| Requires a known model form                                                        | May not have explicit model form                                                                          |
| Storing models generally requires less storage                                     | Storing training data generally requires more storage                                                     |

### When to use standardization 

| **Algorithm(s)**                   | **Reason of applying feature scaling**                                                                                                                             |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| K-means                            | Use the Euclidean distance measure                                                                                                                                 |
| K-nearest neighbours               | Measure the distance between pairs of samples and these distances are influenced by the measurement units                                                          |
| Principal Component Analysis (PCA) | Try to get the feature with maximum variance                                                                                                                       |
| Artificial Neural Network          | Apply gradient descent                                                                                                                                             |
| Gradient Descent                   | Theta calculation becomes faster after feature scaling and the learning rate in the update equation of stochastic Gradient Descent is the same for every parameter |

