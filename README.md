# deep-rl-bootcamp-lab04

#### Task 3.3 & 3.4: Accumulating Policy Gradient
<img alt="Task 3.3 & 3.4 Results" src="/images/3_3_Results_1.png" width="400"> 
<img alt="Task 3.3 & 3.4 Results" src="/images/3_3_Results_2.png" width="400"> 

#### Task 3.5: Time-Dependent Baseline
<img alt="Task 3.5 Results" src="/images/3_5_Results.png" width="400">
<img alt="Task 3.5 Results" src="/images/3_5_Results_2.png" width="400">

#### Task 3.6 Discrete Actions
<img alt="Task 3.6 Results" src="/images/3_6_Results.png" width="400">
<img alt="Task 3.6 Results" src="/images/3_6_Results_2.png" width="400">


#### Task 3.7: Hyperparameter Tuning

Differentiating in Batch Size, Discount and Learning Rate leads to vastly different results for Point-v0 and Cartpole-v0. Some Examples:

| Hyperparameters              | Average Return | Theta 2|
|-----------------------|----------------|--------|
|b=1000, d=0.95, a=0.01 | -34.12          | 0.74   |
|b=2048, d=0.97, a=0.01 | -34.25          | 0.73 |
|b=1000, d=0.95, a=0.05 | -23.55          | 3.44   |

The most influential factor for the average return is by far the learning rate and should be optimized if possible. Learning Rate of 0.05 seems to be the best solution for both problems.



#### Task 3.8: Natural Gradient

<img alt="Task 3.8 Results" src="/images/3_8_Results.png" width="400">


#### Task 4: Advanced Policy Gradient

At around 55 Moves, there is a mistake visible which did cost some steps to recover back to 200. After that it stayed at around 200 with a small mistake at around 70.

<img alt="Task 4 Results" src="/images/4_Results.png" width="750">


#### Task 5: Trust Region Policy Optimization (TRPO)

- First Test gets around 200 Average return at around 25 Iterations.
- Second Test gets around -200 Average return at the same time, but with a somewhat exponential increase towards the -200.
- Third Test steadily increases the Average Return over time and goes towards 200 at 100 Iterations and 600 at 150 Iterations.



#### Task 6: Advantage Actor Critic (A2C)
Here are some Screenshots of the results during training which lead to the result of the benchmarks being achieved.
<img alt="Task 6 Results" src="/images/6_Results.png" width="350">
<img alt="Task 6 Results" src="/images/6_Results_2.png" width="350">


