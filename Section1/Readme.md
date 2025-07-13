# Method 1 O(1) qubit complexity

We have added notebooks here for the solution we proposed. We have tested the solution against the a set of U. We have provided notebooks with local simulation as well as running on IBM and AWS. We also have noisy simulation notebook. In each notebook, we have also added tools for visualization and comparing the results.

Here the U we have selected they have q0 as the control qubit and we are using this as signal bit.
We can also have the control bit (C) and signal bit different (S) and for this we have added notebook in Section4. Our Auxilary qubit is the one that is helping us amplify the required state. When the C and S are different we would need to do mathematical analysis and create class of U. We tried to do that mathematical analysis and classical prepossing in Section4. More analysis is still required.

NOTE: For running on IBM, we would have to add the token key and the device CRN on which we want to run.


# Notebooks
[Method 1 Solution](Quantum_Evolution_with_Measurement_and_Reset_Method-1%20.ipynb)

[IBM Method 1](Quantum_Evolution_with_Measurement_and_Reset_[IBM]_Method_1.ipynb)

[AWS Method 1](QunatumEvolution_AWS.ipynb)

[Noisy Simulation Method 1](Quantum_Evolution_with_Measurement_and_Reset_[Noise]_Method_1.ipynb)

