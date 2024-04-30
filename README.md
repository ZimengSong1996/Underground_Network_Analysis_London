# Underground_Network_Analysis_London

`Contact: ismine.song@gmail.com`

`Main content: Underground_Network_Analysis_London.ipynb`

This is a individual program from UCL, CASA. The program is designed to assess the understanding and application of the different urban modelling methodologies. This could be used as a basical tutorial for analysing transport network.

The program will guide you to critically investigate the resilience of the London’s underground as a network and the methodological limitations. We will do this in two ways. In the first part, we will only take into consideration the infrastructural network, where stations are connected through only one link, regardless of the number of lines connecting the stations. In the second part, we will consider the commuting flows, and discuss the impact of the analysis on the number of people moving from one part of the city to another. Then, we will recompute the flows using spatial interaction models according to different scenarios described below and discuss the vulnerability of the network under these new scenarios.


`Part 1: London’s underground resilience`

`I. Topological network`

In this part, we will evaluate the resilience of the London’s underground through the removal of stations that can potentially make the underground vulnerable. Through the procedure outlined below we will investigate which are the stations that are most critical for the functioning of the underground, and which methodology is more appropriate to finding these stations.

`I.1. Centrality measures`

`I.2. Impact measures`

`I.3. Node removal`



`II. Flows: weighted network`

In this section, we will include passengers into the underground, and assess whether different measures need to be used when flows are considered. The network to use in this section is the weighted network given in the github 'london_flows.csv', where the flows of passengers were assigned to the links between stations.

`II.1. Weighted Betweenness Centrality in Directed Networks`

`II.2. Weighted Directed Network Efficiency`

`II.3. Node removal (Weighted Directed Network)`



`Part 2: Spatial Interaction models`

For this section, we will use a “symbolic” population and the number of jobs for the stations in the underground. We will also use the number of people that commute from one station to another, through an OD matrix. All data is contained in 'london_flows.csv'.


`III. Models and calibration`

`III.1. Introduce Double-Constrained Model`

`III.2. Build Double-Constrained Model`



`IV. Scenarios`

`IV.1. Scenario A`

`IV.2. Scenario B`

`IV.3. Analysis of Flow Changes`





