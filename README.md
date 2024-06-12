# Explanation

In recent years, computational models have seen an increase in use across multiple disciplines, one of which being biology. This prompts the question, what makes such models useful in their ability to answer biological questions?  
ABMs (agent-based models) are one type of computational model that have proven helpful in many biological studies. These models involve simulating populations of autonomously interacting agents, usually representing individuals or organisms. 
Here, the ABM created by McNally et al. (2012), where agents represented by artificial neural networks were used to explore the co-evolution of cooperation and intelligence is investigated. 
The genetic algorithm used to evolve the networks over generations was replaced by the popular ‘Neuroevolution of Augmenting Topologies’ algorithm (or NEAT for short) in order to test the generalisability of the model’s results. 
This implementation successfully replicates McNally's model using NEAT. Multiple runs of network evolution can be carried out over 10,000 generations (by default). 
To evolve the networks, payoffs from both iterated Prisoner's Dilemma (IPD) and iterated Snowdrift (ISD) games were used as fitness evaluation mechanisms. 
These runs can vary in parameter choices such as fitness penalties, crossover rates and population size. Intelligence, cooperation, various identified strategies, and the selection for intelligence are recorded over generations for the networks. 
The gradients of the selection for intelligence and identified pure strategy frequencies are also analysed. From my own runs disparities in the results found here and the original model suggest that it does not generalise well when NEAT is used. Furthermore, 
on average, higher intelligence and cooperation levels were observed in ISD simulations, which is consistent with past research. Lastly, parameter choice
was observed to cause various shifts in results within both ISD and IPD simulations. All of my findings reinforce the importance of the choices made in computational model implementations, so that results obtained can have biological relevance.

# Original Model
McNally L, Brown SP, Jackson AL. Cooperation and the evolution of intelligence. Proc Biol Sci. 2012 Aug 7;279(1740):3027-34. doi: 10.1098/rspb.2012.0206. Epub 2012 Apr 11. PMID: 22496188; PMCID: PMC3385471.
https://pubmed.ncbi.nlm.nih.gov/22496188/
