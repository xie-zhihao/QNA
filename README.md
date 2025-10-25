# QNA
QuantumNeuro Architecture Analytics Lab

A research framework system dedicated to exploring the intersection of quantum many-body physics and neural architecture design.
QNA provides an accelerated data analytics and storage system to benchmark, analyze, and optimize modular neural network architectures for NQS(Neural quantum states) across diverse Hamiltonians.



## 🧩 **Input Unit: Quantum Hamiltonian Library**

### Supported Hamiltonians
- **Ising model** (1D, 2D, transverse field)
- **Heisenberg model** (XXX / XXZ / anisotropic)
- **6-Vertex & 8-Vertex models**
- **J₁–J₂ spin chain**
- **Curie–Weiss mean-field model**
- **Hubbard model** (fermionic)
- **Bose–Hubbard / t–J extension**
- **Custom user-defined Hamiltonians**

### Input Format
- Symbolic or matrix-based Hamiltonian representation  
- Optional features:
  - Symmetry constraints  
  - Lattice geometry  
  - Boundary conditions  

---

## 🧠 **Architecture Modules Unit: Neural Quantum Architectures**

### Core Components
- **Neural network configuration**
  - NN size / depth / width  
  - Activation functions: `ReLU`, `GeLU`, `tanh`, `softsign`, complex-valued activations…  
  - Interconnectivity: fully connected, convolutional, graph-based, attention  
  - Optimizer: `Adam`, `RMSProp`, `SGD`, **Quantum Natural Gradient**

### Modular Building Blocks
- **Input Encoding:** spin / fermion / graph encoding schemes  
- **Convolutional modules:** 1D / 2D CNN  
- **Pooling / Padding layers:** for local feature aggregation  
- **Attention / Transformer modules:** nonlocal correlation learning  
- **Variational layers:** complex amplitude representation  
- **Autoencoder / symmetry-enforcing submodules**  
- **Quantum circuit-inspired layers:** unitary parameterization  

### Architecture Analytics
- **Structural visualization:** network graph  
- **Complexity metrics:** parameter count, expressivity index  
- **Training diagnostics:** stability and convergence analysis  

---

## ⚛️ **Output Unit: Quantum Observables & Correlation Metrics**

### Observable Outputs
- Ground-state energy: **E₀**  
- Correlation functions: ⟨SᵢSⱼ⟩  
- Entanglement entropy: von Neumann / Rényi  
- Coherence and purity metrics  
- Magnetization / charge-density profiles  
- Fidelity vs. ED or DMRG benchmarks  
- Neural-state expressibility score  

---

## 📊 **Statistical Analytics**

- **Learning curve:** energy or loss vs. iteration  
- **Variance & autocorrelation time:** sampling stability  
- **Architecture performance comparison:** cross-Hamiltonian benchmarking  
- **Robustness:** under noise or parameter perturbation  
- **Energy convergence rate:**  
  - \( \frac{dE}{d\text{epoch}} \),  
  - Energy deviation \( E - E_{\text{ref}} \)  
- **Runtime metrics:**  
  - Total training time  
  - Per-epoch latency  
  - Sampling time per configuration  
- **Computation cost:**  
  - Parameter count \( N_\theta \)  
  - FLOPs per epoch  
  - Memory footprint  

---

### 🧮 **Composite Performance Analysis**
> Assign weights to the above metrics and compute a **weighted composite performance score** for holistic evaluation.
