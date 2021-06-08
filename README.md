# Travelling Salesman Problem using Genetic Algorithm

Implementation : https://upbeat-wozniak-7da441.netlify.app

Travelling Salesman Problem : 
1. The journey begins and ends from and to the initial city 			
2. There are several cities, all of which must be visited exactly once 	
3. Travel must not return to the initial city before all the destination cities visited									
4. The purpose of this problem is to reduce the distance visited by salesperson by arranging the order of cities to be visited 

For implementation purpose, we have considered Maharashtra map cities for the travelling salesman problem.

Approach :  In our implementation, 
1. Indices of each city are taken as genes.
2. Complete list of indices of cities are taken as chromosome.
3. Set of shuffled indices of cities of all chromosomes are taken as Population.
4. 1/(total distance to be covered to visit all cities in each chromosome) is taken as fitness score of that chromosome.
5. Population Size: 500
6. Mutation Rate: 0.01
7. Number of Iterations: 999

![image](https://user-images.githubusercontent.com/54303198/121219964-d728d780-c8a1-11eb-963a-6acee5134c57.png)
