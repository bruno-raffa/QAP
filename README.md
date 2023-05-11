*Quadratic assignment problem (QAP)



The quadratic assignment problem (QAP) is one of the fundamental combinatorial optimization problems in the branch of optimization or operations research in mathematics, from the category of the facilities location problems first introduced by Koopmans and Beckmann.

The problem models the following real-life problem:

There are a set of n facilities and a set of n locations. For each pair of locations, a distance is specified and for each pair of facilities a weight or flow is specified (e.g., the amount of supplies transported between the two facilities). The problem is to assign all facilities to different locations with the goal of minimizing the sum of the distances multiplied by the corresponding flows.
Intuitively, the cost function encourages facilities with high flows between each other to be placed close together.

The problem is defined here is defined here: https://neos-guide.org/case-studies/sc/la/qap/

The approach used here involves using a Constrained Quadratic Model (CQM).  The solution is computed using the LeapHybridCQMSampler.

We will consider two cases the simplest one (n=4) and the most complex one (n=9). The results obtained in both of the cases with CQM are coincident with the optimal results obtained in the case study, confirming that Dwave annealer can be used for coping this problem.