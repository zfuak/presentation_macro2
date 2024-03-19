# Introduction
The paper we are going to present is output dynamics in real business cycle models.

The main question: Are RBC models consistent with output dynamics stylized facts?

Short answer: yes and no. to some degree, it replicates the reality but most of the time it fails to do so.

We evaluate the model based on 2 metrics: 
1. ACF & Spectrum decomposition
2. Impulse response functions (Permanent and temporary)

# Model results and shock identification
Just for completeness reason, I am presenting the baseline RBC model here. The only difference from the very first toy model we studied in class is 1. the $g_t$ term which is exogenous and follows a AR(1) process. 2. The capital depreciation rate $\delta$

Also for completeness reason, we can easily derive the two optimality condtions. We don't have any closed form solution for the model, so we have to solve it numerically/by approximation.

In another paper, they apply another algorithm to solve the model to get a closed form solution. Interpretation of the results. Two parts: shock dynamic and propagation mechanism.

What we are going to focus on is exactly the two parts. First, we try to build a connection with the previous paper just presented. How to identify shocks (the matrix $S$). Therefore constructing the impulse response functions. Second, we examine the propagation mechanism. Graphical illustration.  

Because the CE model is a case of balanced growth model (why?), the assumptions of BQ decomposition hold. (why?). How does balance growth model relate to those assumptions?

# Par parenthese
To draw a line between what we learn in class and this paper, it's better to look at the third example where. 
So far, we have seen that we can use SR restriction to identify the S matrix. Look at the zero.
Moreover, similarity can be seen from the shock dynamics. Thus, BQ assumptions also hold. We can use LR restriction. 

# Question
why do we call $\varepsilon_g$ a transitory shock? It is not clear to me. Demand shock is transitory while supply shock is permanent? 


