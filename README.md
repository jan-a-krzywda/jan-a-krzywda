# Jan A. Krzywda

<div align="center">

### Theoretical Physicist & Systems Engineer
*Bridging AI and quantum computing through a systems perspective.*

[![Personal Website](https://img.shields.io/badge/Personal%20Website-jan--a--krzywda.com-blue?style=for-the-badge&logo=safari)](https://jan-a-krzywda.com)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Citations%3A%20500%2B-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=HAbQfbIAAAAJ&hl=en&oi=ao)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/yourchannel)

</div>

---

## 🎯 Mission Statement

I approach quantum computing from a systems engineering perspective, studying the entire pipeline from hardware physics to high-level algorithms. As a researcher at Applied Quantum Algorithms, Leiden University, my primary focus is connecting artificial intelligence with quantum physics.

My goal is to close the feedback loop across the quantum computing stack. To achieve this, I build digital twins of quantum hardware, deploy reinforcement learning agents to improve device control, and stress-test system designs. Ultimately, I work to develop active learning algorithms that adapt to physical devices and utilize quantum algorithms to coherently process physical data.

---

## 🗂️ Research Subjects & Open Source

### 1. Hardware Architectures, Simulators & Databases
Democratizing semiconductor spin qubits by developing foundational architectures and open-source tools to utilize the massive scaling potential of these devices.
* **Conveyor Belt Shuttling:** A foundational theoretical proposal for continuous coherent electron shuttling that has become a hardware standard, culminating in a recent experimental demonstration. [cite_start]Foundation paper: [*Physical Review B* 101, 035303 (2020)](https://doi.org/10.1103/PhysRevB.101.035303) [cite: 118, 119][cite_start], Recent experimental demonstration: [*arXiv:2602.09179* (2026)](https://arxiv.org/abs/2602.09179)[cite: 107, 108].
* **[QDarts](https://github.com/qplai/QDarts):** A quantum dot array transition simulator.
* **[Readspyn](https://github.com/jan-a-krzywda/ReadSpyn):** Simulation frameworks for multi-qubit arrays and noise spectroscopy.
* **[SQalar](https://github.com/jan-a-krzywda/SQalar):** Tools for scalable quantum architectures.
* **[SpinBase](https://github.com/jan-a-krzywda/SpinBase):** A catalogue of quantum algorithms and papers specifically for spin qubits.

### 2. Real-Time Tracking & Quantum Error Correction
Bridging low-level hardware fluctuations with high-level logic. This focuses on estimating the state of noisy systems on the fly to keep qubits stable over many cycles.
* **[Real-Time Bayesian Tracking](https://github.com/jan-a-krzywda/Quantum-Bayesian-Tracking):** Algorithms for estimating and tracking qubit drift on microsecond timescales.
* **[Quantum Error Correction (QEC)](https://github.com/jan-a-krzywda/qec-gym):** Ongoing projects applying sequential decision-making to the decoding problem.

### 3. Active Quantum Control & Reinforcement Learning
Applying active inference, world models, and representation learning to quantum control. By building efficient representations, autonomous agents can plan and execute control policies directly on the hardware.
* **[World-Models of Quantum Devices](https://github.com/jan-a-krzywda/quantum-active-control):** Using latent spaces to compress the complexity of quantum systems for autonomous control.
* **[Quantum-gym](https://github.com/jan-a-krzywda/quantum-gym):** Environments for training reinforcement learning agents on quantum hardware tasks.

### 4. Quantum Learning Machines
[cite_start]Leveraging coherent processing to learn directly from quantum data[cite: 202]. [cite_start]This research treats physical hardware limitations as a feature to find practical machine learning advantages on near-term devices[cite: 234].
* **[QML Advantage](https://github.com/jan-a-krzywda/demonstraing-quantum-advantage):** Evidence of machine learning advantage using noisy qubits.
* **Physical-AI with Quantum Computers:** Integrating physical AI architectures with quantum computation *(TBA)*.
* **Quantum Games:** Citizen science platforms that harvest human intuition to train control models.
    * **[QEC Game (Erratiq)](https://erratiq.xyz/)**

### 5. Physics-Inspired Classical Machine Learning
Using the mathematical machinery of statistical physics to understand and improve classical deep learning architectures.
* **Neural Network Pruning:** Discovering universal scaling laws and phase transitions in pruning capacity *(TBA)*.
* **Physics-Informed Architectures:** Applying statistical mechanics frameworks directly to AI design *(TBA)*.

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

*Below are my 5 most recent works. For the complete list, please see [PUBLICATIONS.md](./PUBLICATIONS.md).*

1. **Statistical Structure of Charge Disorder in Si/SiGe Quantum Dots**
   *Samadi, S., & Krzywda, J. A.* (2025). [arXiv:2510.13578](https://arxiv.org/abs/2510.13578)

2. **Real-time adaptive tracking of fluctuating relaxation rates in superconducting qubits**
   *Berritta, F., Benestad, J., Krzywda, J. A., et al.* (2025). [arXiv:2506.09576](https://arxiv.org/abs/2506.09576)

3. **Efficient Qubit Calibration by Binary-Search Hamiltonian Tracking**
   *Berritta, F., ..., Krzywda, J. A., et al.* (2025). *PRX Quantum*. [DOI](https://doi.org/10.1103/PRXQuantum.6.030335)

4. **QDarts: A quantum dot array transition simulator**
   *Krzywda, J., Liu, W., van Nieuwenburg, E., & Krause, O.* (2025). *SciPost Physics Codebases*. [DOI](https://doi.org/10.21468/SciPostPhysCodeb.43)

5. **Decoherence of electron spin qubit during transfer between two semiconductor quantum dots**
   *Krzywda, J. A., & Cywiński, Ł.* (2025). *Physical Review B*. [DOI](https://doi.org/10.1103/PhysRevB.111.115305)

<div align="center">

**[📄 View Complete Publication List](./PUBLICATIONS.md)**

</div>

---

## 🕹️ After Hours Projects

When I'm not building quantum systems, I explore complexity in other forms:
* **[arXiv Digest](https://jan-a-krzywda.com/arxivaria):** Curating and summarizing selected arXiv papers in spin-qubits, quantum control, quantum machine learning, and physics-inspired AI.
* **[Outreach](https://www.youtube.com/@jakmatura-fizyka207):** Running *JakMatura - Fizyka*, an educational physics channel for high school students.
* **Motorsport Analytics:** Analyzing motorsport data to uncover hidden patterns and insights, with a focus on Formula 1 *(TBA)*.
* **Music:** Playing the piano and listening to Chopin.
* **[Being a Dad](https://www.instagram.com/quantum_papa/):** Living the adventure of parenthood.
* **[Handmade Clothes](https://atelier-daily-elegance.store/):** Supporting my wife's passion and our handmade clothing brand, Atelier Daily Elegance

---

<div align="center">

**Building the Quantum Future, One System at a Time**

[Website](https://jan-a-krzywda.com) • [LinkedIn](https://linkedin.com/in/yourprofile) • [Research Organization](https://github.com/jaq-lab)

</div>

