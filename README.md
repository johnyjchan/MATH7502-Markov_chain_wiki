# Markov chain

[**From SUO, YaoJin; PAN, Xiaoming; CHEN, Yaojie**]

*Semester 2, 2019, The University of Queensland*

> Briefly, a Markov chain is a stochastic model describing a sequence of possible events in which the probability of each event depends only on the state attained in the previous event.

![markov_chain](https://pic4.zhimg.com/80/v2-2372589ce0e3ed1a1211f108693c3cc7_hd.jpg)

* [Origin](#origin)
* [Introduction](#intro)
* [Definition](#definition)
* [Markov modelling](#markov)
* [Stationary distribution & optimazed modelling](#optimazedmodelling)
* [Application](#application)
    - [Pagerank](#pagerank)
    - [Gambling](#gambling)
    
<div id="origin"/>

### Origin

Markov named after the Russian mathematician Andrey Markov. His was best known for his work on stochastic processes. A primary subject of his research later became known as Markov chains and Markov processes.

<div id="intro"/>

### Introduction

At each step of Markov chain, the system can change from one state to another or keep the current state according to the probability distribution. (We have transition matrix to describe the probability.) The change of state is called transition, and the probability related to different state changes is called transition probability. Random walk or Brownian motion is an example of Markov chain. The state of each step in random walk is the point in the graph. Each step can move to any adjacent point. The probability of moving to each point is the same here, no matter what the previous walk path is. (The memorylessness of stochastic process.)

<div id="definition"/>

### Definition

A discrete-time Markov chain is a sequence of random variables $X_{1}, X_{2}, X_{3}, ... $with the Markov property, namely that the probability of moving to the next state depends only on the present state and not on the previous states:

$$
P\left(X_{n+1} = x | X_{1} = x_{1}, X_{2} = x_{2}, ...,X_{n} = x_{n}\right) = P\left(X_{n+1} = x | X_{n} = x_{n}\right)
$$<br>
If both conditional probabilities are well defined, that is, if $P\left(X_{n+1} = x | X_{1} = x_{1}, X_{2} = x_{2}, ...,X_{n} = x_{n}\right)>0$ Then, The possible values of $X_{i}$ form a countable set S called the state space of the chain.

<div id="markov"/>

### Markov modelling
Naive method: iterally multiply the transfer matrice and convergence to stationary vector.


<div id="optimazedmodelling"/>

### Stationary distribution & optimazed modelling

<div id="application"/>

### Application

<div id="pagerank"/>

###### Pagerank

<div id="application"/>

### Application

<div id="pagerank"/>

###### Pagerank


PageRank was born in 1998 in the hands of Google's founders Larry Page and Sergey Brin. At the end of the last century when commercial search engines were just starting out, the search engine were not so convenient. The semantic analysis of the search terms, the web crawl, and the ranking stragtegy together determine the efficiency of information retrieval. Among them, the ranking algorithm is the most important.  Markov chain is one of the best measurement that time.

![page_rank](https://pic4.zhimg.com/80/v2-2372589ce0e3ed1a1211f108693c3cc7_hd.jpg)
Assuming that there are four websites in the internal as the figure shown.
![page_rank1](https://pic3.zhimg.com/80/v2-6e50164f39ee6e6e5e76b26aa3e31efa_hd.jpg)
![page_rank2](https://pic3.zhimg.com/80/v2-714bae6e50e142556b8972658c78677a_hd.jpg)

<div id="gambling"/>


###### Gambling
