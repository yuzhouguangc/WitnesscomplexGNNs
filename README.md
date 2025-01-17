### Witness complex-based GNNs

#### 1. witness_complex_topo_summary.py: generate witness complex-based persistence diagram (PD) and persistence image (PI)
#### 2. test_gcn.py: test $\color{gray}{\text{vanilla GCN}}$ $\rightarrow$ $\color{red}{\text{various GNNs?}}$ performance under $\color{gray}{\text{meta attack}}$ $\rightarrow$ $\color{red}{\text{various attack strategies?}}$ with different pertubation rates
#### 3. test_witcompnn.py: test Witness complex-based GCN performance under meta attack with different pertubation rates

### Witness complex-based topological feature representation learning

#### 1. DeepSets $\sim$ PD

#### 2. Rational hat function $\sim$ PD

#### 3. Point transformations $\sim$ PD

#### 4. CNN $\sim$ PI

#### 5. Set2Set $\sim$ PI

#### 6. Transformer $\sim$ PI

### Design an attack strategy based on topological-based nodes' properties (e.g., higher persistence)
#### optimize $\epsilon$, how to select landmarks (remove the backbone nodes).

### Requirements:
- python >= 3.9
- pip3 install cython
- pip3 install ripser
- pip3 install numba, gensim
- pip3 install numpy,scipy, 
- torch
- torch_geometric
