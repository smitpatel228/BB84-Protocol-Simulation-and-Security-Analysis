# BB84 Quantum Key Distribution: Simulation & Analysis

This project implements a simulation of the BB84 Quantum Key Distribution (QKD) protocol using Qiskit. It explores secure key exchange, eavesdropping detection, and the effect of noise in quantum communication.

 🚀 Features

* End-to-end BB84 protocol simulation (Alice → Bob)
* Eavesdropping (Intercept-Resend attack by Eve)
* Noisy quantum channel using depolarizing noise
* Quantum Bit Error Rate (QBER) calculation
* Abort condition based on QBER threshold (~11%)

 🧠 Key Concepts

* Quantum superposition and measurement
* Basis mismatch and probabilistic outcomes
* No-cloning theorem and security of QKD

 📊 Results

* Without Eve → Low QBER (secure communication)
* With Eve → Increased QBER (detectable attack)
* With noise → Realistic error behavior

 🛠️ Tech Stack

* Python
* Qiskit (quantum simulation)
* NumPy, Pandas
* Matplotlib

 ▶️ How to Run

```bash
git clone https://github.com/YOUR_USERNAME/BB84-Quantum-Cryptography.git
cd BB84-Quantum-Cryptography
pip install -r requirements.txt
jupyter notebook BB84_Trial_5.ipynb
```

 📁 Project Structure

* `Notebook` -> BB84_Trial_5.ipynb` → Main simulation notebook
* `requirements.txt` → Dependencies
* `Images`    

 📌 Future Work

* Extend to E91 protocol
* Add privacy amplification and error correction

## 👤 Author

Smit Patel
