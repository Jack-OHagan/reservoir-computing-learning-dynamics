# Reservoir Computing Learning Dynamics
A repository of experiments on the dynamics of trained and untrained attractors in a trained reservoir computer.

## Notebooks Overview

- **ReservoirComputer_np.ipynb**  
  RC object for lower-dimensional reservoirs that do not benefit from sparse indexing. Also includes an object through which the RC state space can be explored easily.

- **ReservoirComputer_sparse.ipynb**  
  RC object for high-dimensional reservoirs that benefit from the sparse indexing to cut computational costs. Also includes an object through which the RC state space can be explored easily.

- **simulation_generation_notebook.ipynb**  
  Framework for mass exploration of trained RC state spaces across different spectral radius values and random initialisations of reservoir topology and readin matrix.

- **Display_and_save_simulation_plots.ipynb**  
  Automates generation and storage of figures from large corpus of data generated with **simulation_generation_notebook.ipynb**.

- **Classification_of_attractors_across_bifurcation_analysis.ipynb**  
  Automates classification of exploration and the attractors simulated in the exploration, that were generated in **simulation_generation_notebook.ipynb**. Also includes methods for generating figures to help interpret trends in how classification of attractors and state spaces change with rho.

- **poormans_continuation_on_trimmed_attractors_for_bifurcation_diagram.ipynb**  
  Framework through which attractors of a RC confuguration may be identified and continued across parameter changes.

- **Bifurcation_diagram.ipynb**  
  Automates the generation of bifurcation diagrams from the data generated and stored in **poormans_continuation_on_trimmed_attractors_for_bifurcation_diagram.ipynb** to gain insight into the evolution of attractors as they are continued across parameter changes.

---

## Unrefined notebooks / Experiments still underway
**Note:**  
*The following notebooks are experimental and created for specific exploratory purposes without a grand design. They may be messier and were intended for one-time use:*

---

- **Check_if_flow_is_preserved.ipynb**  
  Analyzes the flow of confabulations and their relationship to Lorenz attractor flow.

- **Lorenz_birth_generation_notebook.ipynb**  
  Generation of simulations around the point where the Lorenz attractor is born.

- **Test_birth_death_Lorenz_Specific_M.ipynb**  
  Exploration of state space around parameters changes resulting in the dissapearance of the Lorenz attractor.

- **Poor_mans_continuation.ipynb**  
  A computationally infeasible continuation approach due to the presence of numerous duplicate attractors.

- **Test_book_for_RC_analysis.ipynb**  
  A notebook used to test ideas before committing them to cleaner notebooks above.
