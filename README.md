# Lucas_island

Lucas & Prescott - Equilibrium Search and Unemployment

Python code for solving this model.

In a nutshell, this model is about workers that move through separate markets (it is easier to think of these markets as islands) searching for jobs. At any time, a worker is in an island and decides whether to stay and take a job there or go to another island searching for a job.

For a more detailed explanation, the notebooks].

The process of arriving to an island  is stochastic. 

The notebook LucasPrescott74 works with stochastic arrival. The associated Python file is lucas_search.py. This file contains the lucas_search_ns.py file but adds the stochastic arrival part.

The code uses the Bellman operator to compute a value function. This code also computes a Markov transition matrix to model the dynamics of the workforce.

The Python file lucas_search_general.py provides a way of computing a general equilibrium when one of the assumptions is taken away (low number of islands). However, this code is not efficient and its usefulness is questionable.
