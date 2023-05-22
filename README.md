# TSP_with_RL

**Motivation :** With the increase in popularity of e-commerce, it is becoming of utmost importance for the logistics industry to optimize their deliveries inorder to minimize the cost. This is an application of TSP. TSP also works as a benchmark for the other complex problems like the Vehicle Routing Problem (VRP), the Marine Routing Problem (MRP) and the Warehouse Placement Problem. Thus, on a business front solving TSP optimally can make a difference to the organization. 

**Challenges :** The problem is categorized as a NP-Hard problem (nondeterministic polynomial time - hard). The worst case scenario for the problem is of the order O(n!) where n is the number of cities to be traversed, thus it becomes very difficult to do the brute force approach for even 20 cities as 20! is in the order of $10^{18}$. Thus we need to develop algorithms which would solve the TSP optimally and in reasonable time. It was evident that the simplest approach of trying every possible combination is not possible and thus ever since the problem has been formulated there have been numerous algorithms that intend to solve the TSP, but all of them involve math heuristics. 

**Innovation :** This project aims at taking the data-driven approach which will figure out what should be the optimal path to solve the problem. The input to the data will be a position of the cities and the output will be the optimal path to be traversed. This can be done by implementing a Reinforcement Learning which is a subset of Machine Learning. The further sections describe what reinforcement learning is and how is it implemented to solve the TSP. 

![image](https://github.com/JavalVyas2000/TSP_with_RL/assets/73403218/48c596cb-e219-4558-9a39-5001cedf665b)

![image](https://github.com/JavalVyas2000/TSP_with_RL/assets/73403218/92dc80e1-80bc-4101-87ad-ecf63d02b341)

![image](https://github.com/JavalVyas2000/TSP_with_RL/assets/73403218/9cd951ff-91fc-43f0-b7d5-878d4b251565)
