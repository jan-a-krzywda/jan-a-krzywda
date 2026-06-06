# Jan A. Krzywda

<div align="center">

### Theoretical Physicist & Systems Engineer
*Bridging AI and quantum computing through a systems perspective.*

[![Personal Website](https://img.shields.io/badge/Personal%20Website-jan--a--krzywda.com-blue?style=for-the-badge&logo=safari)](https://jan-a-krzywda.com)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Citations%3A%20500%2B-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=HAbQfbIAAAAJ&hl=en&oi=ao)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jan-a-krzywda-489a59315/)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/@jakmatura-fizyka207)
[![AQA](https://img.shields.io/badge/AQA-Leiden_University-001158?style=for-the-badge)](https://aqa.liacs.nl/)

</div>

---

## 🎯 Mission Statement

I approach quantum computing from a systems engineering perspective, studying the entire pipeline from hardware physics to high-level algorithms. As a researcher at Applied Quantum Algorithms, Leiden University, my primary focus is connecting artificial intelligence with quantum physics.

My goal is to close the feedback loop across the quantum computing stack. To achieve this, I build digital twins of quantum hardware, deploy reinforcement learning agents to improve device control, and stress-test system designs. Ultimately, I work to develop active learning algorithms that adapt to physical devices and utilize quantum algorithms to coherently process physical data.

---

## 🗂️ Research Subjects & Open Source
My research spans through the quantum computing stack, starting from the physics of semiconductor spin qubits, to real-time tracking and quantum error correction, to active control with reinforcement learning, and finally to quantum machine learning. I also explore physics-inspired approaches to classical machine learning.

### 1. Hardware Architectures, Simulators & Databases
Democratizing semiconductor spin qubits by developing foundational architectures and open-source tools to utilize the massive scaling potential of these devices.
* **[Charge Noise Simulation and Spectroscopy](https://github.com/jan-a-krzywda/charge-noise-spin-qubits):** Effective models of charge noise in quantum dot arrays and developing tools for noise spectroscopy.
* **[Conveyor Belt Shuttling](https://github.com/jaq-lab/mobile-qubit-protection):** Latest experimental demonstration of protecting qubits during shuttling. In the past contributed to the development of a conveyor belt architecture.
* **[QDarts](https://github.com/qplai/QDarts):** A quantum dot array transition simulator.
* **[Readspyn](https://github.com/jan-a-krzywda/ReadSpyn):** Simulation frameworks for multi-qubit arrays and noise spectroscopy.
* **SQalar** (WIP): Tools for scalable quantum architectures.
* **SpinBase** (WIP): A catalogue of quantum algorithms and papers specifically for spin qubits.

### 2. Real-Time Tracking & Quantum Error Correction
Bridging low-level hardware fluctuations with high-level logic. This focuses on estimating the state of noisy systems on the fly to keep qubits stable over many cycles.
* **[Real-Time Bayesian Tracking](https://github.com/jan-a-krzywda/quantum-bayesian-tracking)** (WIP): Algorithms for estimating and tracking qubit drift on microsecond timescales.
* **[Quantum Error Correction (QEC)](https://github.com/jan-a-krzywda/qec-gym):** Ongoing projects applying sequential decision-making to the decoding problem.

### 3. Active Quantum Control & Reinforcement Learning
Applying active inference, world models, and representation learning to quantum control. By building efficient representations, autonomous agents can plan and execute control policies directly on the hardware.
* **[Controllability Analysis](https://github.com/jan-a-krzywda/qdot-disorder-structure):** Using principal component analysis to analyze the controllability of quantum dot arrays under realistic disorder.
* **[World-Models of Quantum Devices](https://github.com/jan-a-krzywda/quantum-active-control)** (WIP): Using latent spaces to compress the complexity of quantum systems for autonomous control.
* **[Quantum-gym](https://github.com/jan-a-krzywda/quantum-gym)** (WIP): Environments for training reinforcement learning agents on quantum hardware tasks.

### 4. Quantum Learning Machines
Leveraging coherent processing to learn directly from quantum data. This research treats physical hardware limitations as a feature to find practical machine learning advantages on near-term devices.
* **[QML Advantage](https://github.com/jaq-lab/noisy-learning-advantage):** Evidence of machine learning advantage using noisy qubits.
* **Physical-AI with Quantum Computers** (WIP): Integrating physical AI architectures with quantum computation.
* **Quantum Games:** Citizen science platforms that harvest human intuition to train control models.
    * **[QEC Game (Erratiq)](https://erratiq.xyz/)**

### 5. Physics-Inspired Classical Machine Learning
Using the mathematical machinery of statistical physics to understand and improve classical deep learning architectures.
* **Neural Network Pruning** (TBA): Discovering universal scaling laws and phase transitions in pruning capacity.
* **Physics-Informed Architectures** (TBA): Applying statistical mechanics frameworks directly to AI design.

---

## 🛠️ Tech Stack & Tools

<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-000000?style=flat&logo=JAX&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat&logo=TensorFlow&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-%236929C4.svg?style=flat&logo=Qiskit&logoColor=white)
![QuTiP](https://img.shields.io/badge/QuTiP-%231E90FF.svg?style=flat&logo=QuTiP&logoColor=white)
![pytket-qiskit](https://img.shields.io/badge/pytket--qiskit-005288?style=flat)

</div>

---

## 📚 Latest Publications

*Below are my 5 most recent works. For the complete list, please see 📄 [PUBLICATIONS.md](publications.md).*
1. O. Danaci, Y. J. Patel, R. Molteni, E. van Nieuwenburg, V. Dunjko & J. A. Krzywda. **Evidence of Quantum Machine Learning Advantage with Tens of Noisy Qubits.** (2026). [[arXiv:2605.21346]](https://arxiv.org/abs/2605.21346)
2. J. A. Krzywda\*, Y. Matsumoto\*, M. De Smet\*, L. Tryputen, S. L. de Snoo, S. V. Amitonov, E. van Nieuwenburg, G. Scappucci, & L. M. K. Vandersypen. **Coherence Protection for Mobile Spin Qubits in Silicon.** (2026). *(\*equal contribution, experimental paper, in review for Phys. Rev. X).* [[arXiv:2602.09179]](https://arxiv.org/abs/2602.09179)
3. F. Berritta, J. Benestad, J. A. Krzywda, O. Krause, M. A. Marciniak, S. Krøjer, et al. **Real-time adaptive tracking of fluctuating relaxation rates in superconducting qubits.** *Phys. Rev. X* 16, 011025 (2026). [[Link]](https://journals.aps.org/prx/abstract/10.1103/gk1b-stl3)
4. F. Berritta, J. A. Krzywda, T. Dvir, P. Buttles, S. Eilhart, J. Danon, & F. Kuemmeth. **Operating a bistable qubit.** (2026). *(In review for Phys Rev. App).* [[arXiv:2605.03187]](https://arxiv.org/abs/2605.03187)
5. S. Samadi, Ł. Cywiński & J. A. Krzywda. **Statistical Structure of Charge Disorder in Si/SiGe Quantum Dots.** (2025). *(Accepted in Phys. Rev. App).* [[arXiv:2510.13578]](https://arxiv.org/abs/2510.13578)


---

## 🕹️ After Hours Projects

When I'm not building quantum systems, I explore complexity in other forms:
* **[arXiv Digest](https://jan-a-krzywda.com/arxivaria):** Curating and summarizing selected arXiv papers in spin-qubits, quantum control, quantum machine learning, and physics-inspired AI.
* **[Outreach](https://www.youtube.com/@jakmatura-fizyka207):** Running *JakMatura - Fizyka*, an educational physics channel for high school students.
* **Motorsport Analytics:** Analyzing motorsport data to uncover hidden patterns and insights, with a focus on Formula 1 *(TBA)*.
* **Music:** Playing the piano and listening to Chopin.
* **[Being a Dad](https://www.instagram.com/quantum_papa/):** Living the adventure of parenthood.
* **[Handmade Passion](https://atelier-daily-elegance.store/):** Supporting my wife's passion and our handmade clothing brand, Atelier Daily Elegance.

---

<div align="center">

**Building the Quantum Future, One System at a Time**

[Website](https://jan-a-krzywda.com) • [LinkedIn](https://www.linkedin.com/in/jan-a-krzywda-489a59315/) • [Research Organization](https://github.com/jaq-lab)

</div>