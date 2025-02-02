# Extinquish: Parallelized QAOA to optimize resource-bound firefighting
Co-authors: Akanksha Chablani ([GH](https://github.com/AkuVolts)),  Aarav Mande ([LI](https://www.linkedin.com/in/aarav-mande-2848b311b/), GH), Corey Ferrier ([LI](https://www.linkedin.com/in/corey-ferrier-131794107/), [GH](https://github.com/coreyfer)), Shannen Espinosa ([LI](https://www.linkedin.com/in/shannenespinosa/), [GH](https://github.com/shannenespinosa))

[iQuHACK 2025 IonQ Challenge](https://github.com/iQuHACK/2025-IonQ), 2 February 2025

Three challenges:
1. Split each graph into two sets of nodes in a way that maximizes the number of edges spanning across the two sets.
2. Added twist: divide the graph in a way that ensures the two sets of nodes are evenly balanced.
3. Added constraint: the subgraphs within each of the two sets must be connected.

Application:
- With the recent tragic events in Los Angeles California, our group decided to utilize our solution in a manner that could potentially target the wildfire disaster over on the west coast. The Max-Cut solution of two groups with the maximum amount of edges between them represents two groups of nodes where we can then apply the few resources to as many nodes in one group such that when the fires are fought at that node, resources would quickly move via edge to the node in the other group.
