# UQ-Methods-for-Predicting-Properties-of-Fiber-Reinforced-Composites
In this repository, we explore the domain of conformal prediction to predict the properties of fiber reinforced composites. Our primary focus is on assessing the effectiveness of different methods in constructing prediction intervals at varying confidence levels. To achieve this, we utilize both the renowned CV+ method and the Conformalized Quantile Regression (CQR) technique. Subsequently, we proceed to compare the results obtained from these approaches.

Folder "Data" contains two different size microstructures that were simulated, one batch of microstructures was $50 \times 50 \mu \text{m}$
and one batch was $100 \times 100 \mu \text{m}$.
 All simulated microstructures for both sizes were artificially generated with equivalent features from an as-manufactured composite laminate. $502$ microstructures were simulated at the $50\mu \text{m}$ size and $960$ for the $100\mu \text{m}$ size, for a total of $1462$ simulations. 

utils_Func.py:  This Python file contains utility functions used in the notebook.

UQ_FiberReinforcedComposites-C.ipynb: Notebook for analyzing prediction intervals of CV+ and CQR methods to predict the properties of fiber reinforced composites.

