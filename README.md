# Opmed.ai Coding Assignment
This repository is an assignment for the Sr. Algo position at Opmed.ai

All code was run on a Windows 10 machine, in a Jupyter notebook running Python 3.11.6

# Part 1
The solution to part 1 can be found in the Jupyter notebook: [predict_surgery_time.ipynb](https://github.com/Zenome84/opmed_ai/blob/main/predict_surgery_time.ipynb)

The solution does some exploratory analysis, finding the discriminatory features. This hypothesis is also tested by using a non-parametric model - Decision Tree - to fit
the data on the discriminatory features, and subsequently on all features. We see that the choice was was correct and offer possible non-parametric and parametric approach
to deal with overfitting. We employ a basic non-parametric approach and observe the results.

# Part 2
The solution to part 2 can be found in the Jupyter notebook: [schedule_surgeries.ipynb](https://github.com/Zenome84/opmed_ai/blob/main/schedule_surgeries.ipynb)

The solution notes that the number of permutations to explore is too large, and instead find ways to reduce the problem so that it can be solved with less complexity.
The notebook explores upper-bound and lower-bound approximations for the cost, explaining the reasons behind these and then proceeds to implement an approach to arrive
at a best, although not proveable, solution. The solution found is, however, very close to the lower-bound.
