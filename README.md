# Waist-Circumference-Prediction

Waist Circumference Prediction based on Waist Side and Front Lengths

The dataset file contained processed and cleaned entries for the two dependent and one independent variable.

![image](https://user-images.githubusercontent.com/52124348/125114314-46912180-e103-11eb-9f8b-3d78b6fc07b9.png)

In this task, I developed a linear regression model for predicting waist circumference from the given set of values of waist side and front length. 

From the initial display of graphs of waist circumference wrt to the two independent variables, it was evident that a linear relationship would be best
suited as the classifier.

![image](https://user-images.githubusercontent.com/52124348/125114350-50b32000-e103-11eb-8edf-b80e08cf75e7.png)

Train-test split of 80:20 and train-val-test split of 60:20:20 produced similar results.

I could have also used neural networks and the problem can be made further complex for enhanced results. But, a 0.97 regression score on 
train, val, and test sets suggests that the results are very encouraging. Plus, a complex model would only lead to less generic results when it comes
to predicting unseen data. 

The .ipynb file shows the workflow for the program. The end weights were:

Optimized Model Coefficients
Bias: -9.22794373315321
Weights: [1.54472927 1.70542442]

At the end, I have displayed the 3D plot of the features and labels. We can see all actual points lie in close proximity to the plane that defines the solution
of the waist circumference problem.

![image](https://user-images.githubusercontent.com/52124348/125114558-8d7f1700-e103-11eb-8460-9f80cf04274f.png)

Here is the final output of predictions wrt actual values.

![image](https://user-images.githubusercontent.com/52124348/125114608-9d96f680-e103-11eb-95f2-2567af0defdf.png)






