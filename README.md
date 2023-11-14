## c-elegans

find a list of all the datasets and compile them

1. Multilayer connectome of Caenorhabditis elegans (Bentley 2016) (https://doi.org/10.1371/journal.pcbi.1005283)
2. C.elegans Cell List (WormAtlas) (http://www.wormatlas.org/)
3. C.elegans Cell List (WormBase) (http://doi.org/10.1093/nar/gkp952) (http://doi.org/10.1002/cfg.248)
4. herm_full_edgelist (Cook 2015) (http://abstracts.genetics-gsa.org/cgi-bin/celegans15s/wsrch15.pl?author=emmons&sort=ptimes&sbutton=Detail&absno=155110844&sid=668862)
5. modified celegans db dump
6. Celegans NeuronsTable (OpenWorm)

different packages to analyse and visualise the datasets
1. Problog (https://www.researchgate.net/publication/244995125_Data_acquisition_and_modeling_for_learning_and_reasoning_in_probabilistic_logic_environment)
2. Gen (http://probcomp.csail.mit.edu/software/gen/)

biological constraints:
1. wiring cost (energy efficency)
2. topology of network based on embryological origin
3. cost of new neurons vs saturation of network
4. extrasynaptic communication via NTs, neuropeptides and hormones

problems with reconstruction
1. static picture of a dynamic system so information is lost
2. multiple different worms are used to reconstruct one connectome
3. lack of external information of extrasynaptic input

ideas for visualising the connectome
1. abstract the data down the levels from L5-L1, to help compare differences in datasets (ProbLog)
2. as there is fixed unsegmented body shape, is it possible to revisualise the connectome with boundary of the worm as the centre, to find out overall length of neural network

general rules and open questions:
1. most bilaterally symmetric pairs of neurons arise from bilaterally symmetric cell lineages, but there are exceptions (symmetry as way to reduce energy cost?)
2. how does male specific neurons influence the wiring of non-male specific neurons in general circuitry? is there a significant energy cost to the rewiring
3. is it better to analyse the connectome separately for male vs hermaphrodite or combine them and merge sex-specific circuitry?

Behaviour:
1. locomotion:CePNEM expression dependent on velocity, head curvature, pumping rate
2. foraging
3. feeding
4. defecation
5. dauer larve formation
6. egg laying (sex-specific)
7. male mating (sex-specific)
8. sensory responses to touch, smell, taste, temperature
9. social behaviour
10. learning and memory