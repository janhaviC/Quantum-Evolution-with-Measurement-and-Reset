# Quantum-Evolution-with-Measurement-and-Reset

The iterative evolution of quantum systems under the influence of measurement and subsequent reset operations presents a fascinating challenge in quantum control. Traditionally, such processes necessitate sequential measurement and re-preparation, hindering their direct implementation on coherent quantum hardware. We propose two solutions that effectively synthesize the conditional evolution of a two-qubit system undergoing repeated measurement-reset cycles, without performing actual intermediate measurements. One solution has O(1) qubits complexity and the other has O(n) qubit complexity.

We analyzed and found that O(1) showed > 10X better performance. We have based most of our analysis on O(1) solution. This is not depended upon n. The way our solution works is by using on auxillary bit and applying operations on that based on the mathematical analysis done on the type of U. We clearly demonstrated in Section1, Section2 that we are able to use the solution for a set of U.

Our solution is based on Grover and when we entangle the auxilary with `control bit` and apply X based on yi value on auxilary, we are able to amplify probability of the desired state.

We have divide the files in four sections. The writeup can be found [here]([Final]Quantum%20Evolution%20wit%20Measuremen%20and%20Reset_%20Wells%20Fargo.pdf)

## Section1: Basic Implementation

Here we have added notebook where we have provided solution to a set of U. There we have also provided IBM and AWS execution files. [Click here for section1](section1)

## Section2: Multi Qubit Support

Here we have added notebook, that shows how our implementation be extended to multi qubit. [Click here for section2](section2)

## Section3: Experimental analysis

Here we tried to create a more generic solution. We tried to do classical analysis and based on that changing operation on auxilary and selecting control bit. [Click here for section3](section3)

### Section5: O(n) Method approach

This method is expensive that is why we did not perform much analysis on this. But we have added this notebook too. [Click here for section4](section4)
