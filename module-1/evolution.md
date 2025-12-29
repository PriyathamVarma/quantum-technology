## Evolution of Quantum Computing

### Classical Computing Perspective

- **Fundamental information carrier:** Bit  
- **Possible states:**  
  - `0`  
  - `1`  

A classical bit can exist in **only one definite state at a time**.

---

### Quantum Computing Perspective

- **Fundamental information carrier:** Qubit  
- **Possible states:**  
  - `|0⟩`  
  - `|1⟩`  
  - Any linear combination of both states simultaneously  

This property is known as **superposition**.

- **Superposition:**  
  A qubit exists in multiple states at once until it is measured.

- **Wavefunction:**  
  The quantum state of a system is described by a **wavefunction**, which contains all probabilistic information about the qubit.

---

## Fundamentals of Quantum Computing

### Mathematical Representation

- **Ket Notation (Dirac Notation):**  
  - Written as `|⟩`  
  - Example:  
    - `|0⟩`, `|1⟩`, `|ψ⟩`

- **State Vector:**  
  - A qubit is represented as a **state vector** in a complex vector space (Hilbert space).
  - General form:  
    \[
    |ψ⟩ = α|0⟩ + β|1⟩
    \]  
    where \( α \) and \( β \) are complex probability amplitudes.

---

### Multi-Qubit Systems

- **Qubit Arrays:**  
  - Multiple qubits form a **quantum register**.
  - The combined system is represented using **tensor products**.
  - Enables **entanglement**, where qubits share correlated states.

---

### Error Correction

- **Quantum Error Correction:**  
  - Quantum states are highly sensitive to noise and environmental interaction.
  - Errors arise due to **decoherence** and imperfect gate operations.
  - Error correction techniques use **redundant qubits** and **syndrome measurements** without directly measuring the quantum state.

---

### Reference Resource

- **Introductory Video:**  
  - https://www.youtube.com/watch?v=RQWpF2Gb-gU

---
