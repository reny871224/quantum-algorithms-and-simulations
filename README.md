# quantum-algorithms-and-simulations
# 🧠 Awesome Quantum Algorithms & Simulations by Chih Yuan Chang

Welcome to my quantum computing project repository! This collection features a variety of Jupyter notebooks that demonstrate implementations of quantum algorithms, simulations of quantum time evolution, decoherence models, and studies on quantum system interactions. These projects are implemented using Qiskit and Python, and they showcase both theoretical foundations and practical simulations relevant to quantum algorithm and hardware research.

---

## Repository Structure

The repository is organized into several folders based on the topic:

### 📁 Algorithms
- **Grover's Search Algorithm**  
  `algorithms/grover_algroithm.ipynb`  
  Demonstrates the implementation of Grover’s algorithm for unstructured search, complete with circuit visualization.

- **Deutsch–Jozsa Algorithm (with and without noise)**  
  `algorithms/Deutsch-Jozsa_without_with noise.ipynb`  
  Compares the ideal and noisy execution of the Deutsch–Jozsa algorithm, highlighting the impact of noise on quantum circuits.

---

### ⏱ Quantum Time Evolution
- **Quantum Real Time Evolution**  
  `time_evolution/Quantum Real Time Evolution.ipynb`  
  Simulates the real-time unitary evolution of a quantum system under specific Hamiltonians.

- **Variational Quantum Time Evolution (VQTE)**  
  `time_evolution/Variational Quantum Time Evolution.ipynb`  
  Implements a variational approach to simulate time evolution, suitable for NISQ devices.

- **Trotter Decomposition**  
  `time_evolution/Trotter.ipynb`  
  Utilizes the Trotter–Suzuki method to decompose Hamiltonian evolution into a sequence of quantum gates.

---

### 🧬 Decoherence & Relaxation
- **Relaxation Simulations (T₁ decay)**  
  `decoherence/relaxation.ipynb` and `decoherence/relaxation_real.ipynb`  
  Model the amplitude damping process to study T₁ decay in quantum systems.

- **T₂ Dephasing Simulation**  
  `decoherence/T2.ipynb`  
  Illustrates phase damping effects and coherence loss, providing insights into T₂ dephasing mechanisms.

---

### ⚛️ Quantum System Interaction
- **Single Qubit System**  
  `interaction/Single System.ipynb`  
  Explores the dynamics of a single qubit system and its response to external perturbations.

- **Two Qubit Coupling**  
  `interaction/two qubit system.ipynb`  
  Simulates interactions and entanglement formation between two qubits.

---

## About Me

I am **Chih Yuan Chang (張智淵)**, a Master's graduate in Semiconductor Physics from National Tsing Hua University, Hsinchu, Taiwan. With a strong foundation in quantum mechanics, computational materials science, and hands-on experience in quantum algorithm implementations, I am passionate about advancing quantum computing research. My work includes both theoretical studies and practical simulations, bridging the gap between quantum algorithm development and quantum hardware challenges.

- **Email:** reny871224@gmail.com  
- **GitHub:** [github.com/yourusername](https://github.com/yourusername) *(replace with your actual username)*

---

## Future Directions

- **Quantum Error Correction:** Exploring implementations of stabilizer codes such as Surface code and Bacon-Shor code.
- **Hardware Integration:** Investigating the interplay between decoherence models and experimental qubit control.
- **Advanced Quantum Algorithms:** Developing more complex quantum algorithms and benchmarking their performance under realistic noise models.

---

**Feel free to explore, fork, and contribute to this repository.**  
If you have any questions or suggestions, please open an issue or contact me directly.

Happy Quantum Computing! 🚀
