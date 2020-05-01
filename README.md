## Resources for Think 2020 Qiskit Master Class:

### [Learn about IBM Quantum’s Scalable Quantum Hardware and Software, and Build Your First Quantum Game!](https://events.tools.ibm.com/widget/ibm/think20/catalog?search=2914) 

### Presenters: [Anamita Guha](https://twitter.com/anamitag) and [James Weaver](https://twitter.com/javafxpert)

- #### Anamita Guha's presentation slides

- #### [James Weaver's presentations slides](https://slides.com/javafxpert/qiskitblocks)

### [IBM Quantum Experience](https://quantum-computing.ibm.com/) (where you'll create a quantum game)



## Quantum Game Challenge (Build a quantum 8-ball)

1. In the IBM Quantum Experience Circuit Composer, create a three-wire circuit whose measurements are randomly distributed among 000 - 111.
   - Observe the results when running your circuit on a backend quantum system or simulator
   - View the **Statevector** and **Measurement Probabilities** from the **Visualizations** tab (bar graph image) on the left side of the page.
2. Create the circuit using Python and Qiskit in an IBM Quantum Experience Jupyter notebook.
3. Make the program print out a message unique to each measured state (e.g. state 000 message might be "The quantum 8-ball says it's most likely"). For reference, here are the [possible answers from the original Magic 8-Ball](https://en.wikipedia.org/wiki/Magic_8-Ball#Possible_answers).
4. If you have time:
   - Rather than using a simulator, use the `from_instruction()` and `sample_counts()` methods of the `qiskit.quantum_info.Statevector` class. Your circuit should not have measure operations. 
   - Expand the circuit to four or five wires.
   - Add various single and multi-qubit gates to the circuit (in the Circuit Composer first if you'd like) and observe their effects on the measurement probabilities and results.



