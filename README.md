This repository contains the official code for the paper: "Grothendieck Graph Neural Networks Framework: An Algebraic Platform for Crafting Topology-Aware GNNs"

Abstract: Due to the structural limitations of Graph Neural Networks (GNNs), in particular with respect to conventional neighborhoods, alternative aggregation strategies have recently been investigated. This paper investigates graph structure in message passing, aimed to incorporate topological characteristics. While the simplicity of neighborhoods remains alluring, we propose a novel perspective by introducing the concept of 'cover' as a generalization of neighborhoods.
We design the Grothendieck Graph Neural Networks (GGNN) framework, offering an algebraic platform for creating and refining diverse covers for graphs. This framework translates covers into matrix forms, such as the adjacency matrix, expanding the scope of designing GNN models based on desired message-passing strategies. Leveraging algebraic tools, GGNN facilitates the creation of models that outperform traditional approaches.
Based on the GGNN framework, we propose Sieve Neural Networks (SNN), a new GNN model that leverages the notion of sieves from category theory. SNN demonstrates outstanding performance in experiments, particularly on benchmarks designed to test the expressivity of GNNs, and exemplifies the versatility of GGNN in generating novel architectures.

For the BREC dataset, start by running the code BREC_dataset. If the accuracy is below 100%, try running BREC_dataset_more_strong_embedding. The need for this adjustment depends on the versions of the installed libraries.