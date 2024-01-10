## Whole-animal connectomes of both _Caeonrhabditis elegans_ sexes
_Steven J. Cook, Travis A. Jarrell, Christopher A. Brittin, Yi Wang, Adam E. Bloniarz, Maksim A. Yakovlev, Ken C. Q. Nguyen, Leo T.-H. Tang, Emily A. Bayer, Janet S. Duerr, Hannes E. Bülow, Oliver Hobert, David H. Hall & Scott W. Emmons_

_Published: 3 July 2019_

# Abstract
- Present quantitative connectivity matrices that encompass all connections from sensory input to end-organ output across the entire animal.
- Serial EM reconstructions that are based on analysis of both new and previously published EM update results and include data on male head
- Nervous system differs between sexes at multiple levels:
  - Several sex-shared neurons that function in circuits for sexual behaviour are sexually dimorphic in structure and connectivity
  - Inputs from sex-specific circuitry to central circuitry reveal points at which sexual and non-sexual pathways converge
  - Sex-shared central pathways, a substantial no. of connections differ in strength between the sexes

**Whole animal connectomes**
- Small world, network motifs, modules and rich clubs
- Reconstruction of circuity for the male head, including the nerve ring and retrovesicular ganglion, from a new EM series and re-annotate previously generated prints of the hermaphrodite
- Graph of the hermaphrodite connectome has 460 nodes (302 neurons, 132 muscles and 26 non-muscle end organs)
  - Male graph has 579 nodes (385 neurons, 155 muscles and 39 non-muscle end organs)
- Two dimensional layouts of the connectivity graphs based on computational arrangement reveal the pathways of sensory information flow
- Small number (1-5) of synaptic steps between the sensory neurons and the end organs and feedforward nature of the networks
- Placement of the nodes to the neuroanatomy of the worm reflects economical wiring, a property commonly found for nervous systems, including in C.elegans

**Architecture of information flow**
- Polarity of the chemical synapses and the architecture of the physical connectivity networks to order the sex-shared neurons and end organ classes using an algorithm that detects hierarchy in a network
- Interneurons can be categorised roughly into one of three layers that reflect preponderance of their output onto the layer below and approx the number of synaptic steps to motor neurons
- Fourth interneuron category: consists of interneurons that interact across all layers, cannot be fitted into this layered structure
- 83 sensory neurons that are shared by both sexes may be grouped into six categories based on type of stimulus, connectivity and the nature of the evoked behavioural response
- Chemical connectivity between the three interneuron layers forms a feedforward loop:
  - Layer 3 substantially targets both layer 2 and layer 1
  - Layer 2 targets layer 1
  - Feedforward loop is a prevalent motif in the C.elegans connectome
- Node degree: amount of convergence and divergence at single nodes in a network (number of attached edges)
  - Diverging connectivity enables information from single sensory neurons to potentially reach from 70% to 98% of all the other cells in the network within two synaptic steps











## Significant updates and corrections to previous data (Whole-animal connectome)
DVB/PVT mixup.  The ventral cord processes of these neurons were crossed in MOW.  PVT extends to the head, DVB ends mid-body.  Previously reported: (WBG 16(1):24 (October 1, 1999)).

PVCL and PVCR.  In MOW these were switched at N2U ventral cord section 1656.

Sublateral motor neurons.  MOW contained no data for the sublateral cords anterior or posterior to the nerve ring, and no neuromuscular junctions for these neurons along the body. Synapses were first noted by immunofluorescence, then confirmed by sampling multiple animals (not reconstructed).

Lateral nerves were closely examined in multiple animals to assess synapses for the first time (not reconstructed except for short portions) (Ramirez-Suarez N.J., Belalcazar H.M., Salazar C.J., Beyaz B., Raja B., Nguyen K.C.Q., Celestrin K., Fredens J., Færgeman N.J., Hall D.H., and Bülow H.E. (2018) Axon-dependent patterning and maintenance of somatosensory dendritic arbors, Dev Cell. 2019 Jan 28;48(2):229-244.).

Motor neurons re-assigned as interneurons: RIM, RMF, RMG.  nmj's reported in MOW for the adult RMF could not be verified.

Interneurons reassigned as motor neurons: SAB, SIA, SIB.

Interneuron reasssigned as sensory neuron: DVA.

Amphid nerves were found to contain synapses among sensory dendrites and RIP, following first discovery in Pristionchus.

Synapses to hypodermis, both chemical and gap junctional, were occasionally reported in MOW but were not systematically scored until now.

Extensive gap junctional connectivity of hmc (head mesodermal cell) to muscle was previously noted (MRC notebooks) but never systematically assessed and reported.

PDB is considered to be an AS class motor neuron (AS12).  It shares all the characteristics of the other members of this class, except the route taken by its commissure differs by going first posteriorly before crossing the body and progressing anteriorly (the reason behind its unique name, J. White, personal communication).  In the male it has an extensive dendritic arbor involved in mating circuitry, as does AS11. 

Muscle arms of the bodywall muscles of the head (#1-8) were  traced to their NMJ inputs for the first time

## Male-specific neurons
There are two new classes of male-specific neurons: MCM (L and R) are interneurons in the head (Sammut et al. 2015, Nature 526, 385-390); PHD (L and R) are putative sensory neurons in the tail derived during the L4 larval stage by transdifferentiation of the phasmid socket cell PHso1 (Sulston et al., 1980; Molina-Garcia et al., https://www.biorxiv.org/content/early/2018/03/21/285320).

In Jarrell et al., the processes of PHD(L/R) were misidentified as branches of R8B.

In Jarrell et al., LUA and PHC were reversed.  Connectivity data given for LUA is in fact due to PHC, and vice versa.
AN3 of Jarrell et al. is AVF (verified by transgene expression of a synaptic marker (unpublished observations)).  AN3 was one of three interneuron processes of neurons with cell bodies in the head that could not be positiviely identified in the pre-anal ganglion.  The other two, AN1 and AN2, are tentatively assigned as AVH and AVJ, respectively.
