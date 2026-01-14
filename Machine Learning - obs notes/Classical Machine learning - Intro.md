Abstract defn - "Learning patterns from data in order to draw inferences"

Function approximation and optimization

A machine has to sequentially learn from data given as inputs. Let g(x) be such a true function. for which it exactly can map to input.

and f($\bar{x}$) will a subset of g(x) x_bar because infinite resource of input data is not possible and $\theta$ that are a set of parameters such that as we characterize $\theta$ we can match f($\bar{x}, \theta$) to the true g(x).

so machine learning is to pick the appropriate model f($\bar{x}$) and to find $\theta$ for the same.

Machine learning ingredients
- data
- model
- cost:
  - cost function actually gives a score on how good your model is on prediction of the given data
  - cost function will compare it with the true value: C(f($\bar{x}, \theta$), correct) where correct is the true value, f($\bar{x}, \theta$) is $\hat{y}$ and true value is $y$, so C($\hat{y},y$).
  - one such cost fucntion is Mean Square Error (MSE) := $(\hat{y},y)^2$ 



$B_Z$
