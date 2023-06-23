# STMO project
**Michael Fatjanov and Ruben Allaert**

These notebooks explore the Slime Mold Algorithm (SMA), a technique derived from the unique problem-solving capabilities of Physarum polycephalum, an acellular slime mold. We first examine the biological characteristics of this organism, before transitioning into the mathematical principles that govern the algorithm. Next, we assess the performance of the SMA and contrast it with its altered versions to identify potential enhancements. Our study concludes with the application of this algorithm on practical problems, specifically the Traveling Salesman Problem (TSP).

We suggest the reader to read the notebooks in the following order:
1. `SMA.ipynb`: this notebook introduces the meta-heuristic slime mold algorithm to optimize continuous function and shows its inner working by applying to some objective functions.
2. `frituurDensity.ipynb`: we take a dataset (scraped frituren around Vlaanderen) and fit a kernel density function to it. We then apply the SMA to it to find the most frituur-dense place in Flanders.
3. `frituurTSP.ipynb`: the SMA used in the earlier notebooks is revised so that it is able to solve traveling salesman problems, specifically for frituren around Flanders. A Bayesian optimization experiment is also included.
