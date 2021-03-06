Massive MIMO and Small Cells
==================

This is a code package is related to the follow scientific paper:

Emil Björnson, Marios Kountouris, Mérouane Debbah, “[Massive MIMO and Small Cells: Improving Energy Efficiency by Optimal Soft-Cell Coordination](http://arxiv.org/pdf/1304.0553),” Proceedings International Conference on Telecommunications (ICT), Casablanca, Morocco, May 2013

The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the paper. *We encourage you to also perform reproducible research!*


##Abstract of Article

To improve the cellular energy efficiency, without sacrificing quality-of-service (QoS) at the users, the network
topology must be densified to enable higher spatial reuse. We analyze a combination of two densification approaches, namely “massive” multiple-input multiple-output (MIMO) base stations and small-cell access points. If the latter are operator-deployed, a spatial soft-cell approach can be taken where the multiple transmitters serve the users by joint non-coherent multiflow beamforming. We minimize the total power consumption (both dynamic emitted power and static hardware power) while satisfying QoS constraints. This problem is proved to have a hidden convexity that enables efficient solution algorithms. Interestingly, the optimal solution promotes exclusive assignment of users to transmitters. Furthermore, we provide promising simulation results showing how the total power consumption can be greatly improved by combining massive MIMO and small cells; this is possible with both optimal and low-complexity beamforming.


##Content of Code Package

The paper contains 2 simulation figures, Figure 3 and Figure 4. These are generated by the Matlab scripts simulationFigure3.m and simulationFigure4.m. The package contains 3 additional Matlab functions, function_QoSproblem_multiflowRZF.m, function_QoSproblem_relaxation.m, and function_QoSproblem_singleBS.m, which are called by the other scripts.

The convex optimization problems are implemented using the modeling language [CVX](http://cvxr.com/cvx/).

See each file for further documentation. 


##Acknowledgements

E. Björnson is funded by the International Postdoc Grant 2012-228 from The Swedish Research Council. This research has been supported by the ERC Starting Grant 305123 MORE (Advanced Mathematical Tools for Complex Network Engineering).


##License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
