# Expressibility-and-Scott-entanglement-measure-for-Parameterized-Quantum-Circuits

This repository has most of the codes I applied during my master's. I present some numerical calculations of expressibility, Scott entanglement measure 1 and 2 and t-designs estimation for different parameterized quantum circuits. The calculations were performed using scipy, numpy python libraries for special functions and Pennylane (Xanadu) library for the quantum circuits part.

It has 3 main folders and it is organized as a function of the calculations performed: Expressibility quantifier, average entanglement and t-design estimation. Each of the folders has a special file that should be read before the others, where the calculations performed are introduced. They are identified with a "double star" (**) next to their name. The capital letters names are the main folders, "->" indicates a subpath inside the folder and the other names are the files. Some file names inside the folders are omitted to simplify the presentation.

I advise you to start with the expressibility folder, move to the entanglement and after that to t-design estimation. Details on the definitions and usage of the quantifiers are presented in Guilherme Ilário Correr, "Exploring the role of qubit connectivity in expressibility and entanglement of parameterized quantum circuits architectures" - Universidade de São Paulo - Brazil (2024).

The structure is as follows:

## EXPRESSIBILITY

### ->Definitions_and_simplecodes_expressibility

   **Expressibility_0_Onequbit_example.ipynb (presents the method and a simple 1 qubit example)

   Expressibility_1_onelayer_topologyofcircuits_.ipynb (introduces the circuits we are studying for only one layer)

   Expressibility_2_ansatz1_multiplelayers_topologyofcircuits.ipynb (generalizes the circuits with Ansatz 1 structure for multiple layers)

   Expressibility_3_ansatz2_multiplelayers_topologyofcircuits.ipynb (circuits with Ansatz 2 structure for multiple layers)

### ->Final_codes_datageneration_expressibility (has the codes that generate the expressibility data outputs)

## AVERAGE_ENTANGLEMENT

### ->Definitions_and_simplecodes_entanglement

   **Entanglementcapability_ansatz1_multiplelayers_topologyofcircuits.ipynb (presents the quantifier and performs the calculations for circuit Ansatz 1)

   Entanglementcapability_ansatz2_multiplelayers_topologyofcircuits.ipynb (calculations for circuit Ansatz 2)

### ->Final_codes_datageneration_entanglement_MW_S1quantifier (has the codes that generate the average entanglement data outputs for quantifier Scott 1)

### ->Final_codes_datageneration_entanglement_S2quantifier (has the codes that generate the average entanglement data outputs for quantifier Scott 2)


## T-DESIGN_ESTIMATION

### ->Single_test (presents the calculations of the t-design closeness quantifier for a single test)
   
   **Ansatz1_2design_test.ipynb

### ->Averaged_case_with_stdeviation (presents the calculations of the t-design closeness quantifier performed many times and then averaged. The standard deviation is also an output.)
