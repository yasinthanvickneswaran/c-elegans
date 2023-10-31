## c-elegans

find a list of all the datasets and compile them

1. Multilayer connectome of Caenorhabditis elegans (Bentley 2016) (https://doi.org/10.1371/journal.pcbi.1005283)
2. C.elegans Cell List (WormAtlas)
3. C.elegans Cell List (WormBase)
4. herm_full_edgelist
5. modified celegans db dump

different packages to analyse and visualise the datasets
1. Problog (https://www.researchgate.net/publication/244995125_Data_acquisition_and_modeling_for_learning_and_reasoning_in_probabilistic_logic_environment)

biological constraints:
1. wiring cost (energy efficency)
2. topology of network based on embryological origin
3. cost of new neurons vs saturation of network
4. extrasynaptic communication via NTs, neuropeptides and hormones

problems with reconstruction
1. static picture of a dynamic system so information is lost
2. multiple different worms are used to reconstruct one connectome
3. lack of external input of extrasynaptic input

ideas for visualising the connectome
1. abstract the data down the levels from L5-L1, to help compare differences in datasets (ProbLog)
2. as there is fixed unsegmented body shape, is it possible to revisualise the connectome with boundary of the worm as the centre, to find out overall length of neural network

general rules and open questions:
1. most bilaterally symmetric pairs of neurons arise from bilaterally symmetric cell lineages, but there are exceptions (symmetry as way to reduce energy cost)
2. how does male specific neurons influence the wiring of non-male specific neurons in general circuitry? is there a significant energy cost to the rewiring
3. is it better to analyse the connectome separately for male vs hermaphrodite or combine them and merge sex-specific circuitry?