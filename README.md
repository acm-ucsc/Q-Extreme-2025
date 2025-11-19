# Q-Extreme Hackathon: Participant Guide

**Sri Lanka's First-Ever Quantum Computing Hackathon**
*Organized by the UCSC ACM Student Chapter*

## 📖 Introduction

Welcome to **Q-Extreme**! Over the next five days, you will push the boundaries of your quantum knowledge, moving from foundational protocols to advanced quantum chemistry simulations. This guide outlines the competition format, scoring criteria, and submission guidelines.

---

## 📅 Timeline

*All times are in IST (Indian Standard Time).*

* **Competition Start:** Wednesday, November 19th @ 12:00 PM
* **Long-Format Challenges (Tasks 1 & 2):** Released at Start. Open until competition closes.
* **Speed Challenge (Task 3):** Sunday, November 23rd @ 12:00 PM
* **Competition Close:** Sunday, November 23rd @ 11:59 PM

---

## ⚖️ Rules & Conduct

* **Participation:** This is an individual event.
* **Collaboration:** Collaboration between competing individuals is strictly prohibited.
* **Plagiarism:** Plagiarism of code or report content will result in immediate disqualification.
* **Resources:** Use of Qiskit documentation and open-source resources is encouraged, but the implementation must be your own.

---

## 🏆 Challenge Categories & Scoring

The hackathon consists of three main tasks totaling **100 Points**.

### Task 1: Quantum Chemistry & Optimization (40 Points)

* **Format:** Jupyter Notebook (`The_Chemist.ipynb`)
* **Objective:** Compute the Ground State Energy of Molecules using Sampling-based Quantum Diagonalization (SQD). You will explore methods to construct subspaces to solve the $N_{2}$ molecule problem, comparing the SQD and Sample-based Krylov Quantum Diagonalization (SKQD) methods.

**Scoring Breakdown:**
* **Exercise 1 (6 Marks):** Defining Active Space & Molecular Properties.
* **Exercise 2 (6 Marks):** Qubit Hamiltonian Mapping.
* **Exercise 3 (6 Marks):** Hardware-Efficient Ansatz (RealAmplitudes).
* **Exercise 4 (6 Marks):** Chemistry-Inspired UCJ Ansatz implementation.
* **Exercise 5 (6 Marks):** Constructing SKQD Circuits.
* **Exercise 6 (10 Marks):** Running the full SKQD Workflow.
    * Part A (5 Marks): Circuit execution and Job ID collection.
    * Part B (5 Marks): Results retrieval and post-processing.

> **Note:** Download the notebook via the link provided in the challenge release and open it in Google Colab (recommended) or your local environment.

### Task 2: Quantum Cryptography & Research (40 Points)

* **Format:** Jupyter Notebook (`The_Cryptographer.ipynb`) & Report
* **Objective:** Implement the BB84 Quantum Key Distribution protocol. Beyond coding, this task requires a comprehensive report analyzing noise, eavesdropping, and robustness solutions.

**Scoring Breakdown:**
* **Protocol Implementation (10 Marks):** Correct implementation of Alice's preparation, Bob's measurement, key sifting, and error checking.
* **Noise Characterization (5 Marks):** Implementing noise models (depolarizing/amplitude damping) and analyzing error rate thresholds.
* **Eavesdropping Scenario (5 Marks):** Implementing an intercept-resend attack and analyzing detection probabilities.
* **Research & Robustness Report (20 Marks):**
    * Identifying real-world challenges (e.g., photon loss, dark counts).
    * Implementing solutions (e.g., Privacy Amplification, Decoy States).
    * Quality, novelty, and depth of the written report (written inside the notebook).

### Task 3: The Speed Round (20 Points)

* **Format:** Timed Challenge (Released Sunday @ 12:00 PM)
* **Structure:** A 4-hour window to complete two specific objectives. Points decay based on the time taken to submit.

**Objectives:**
1.  **Bernstein-Vazirani Oracle (10 Marks):** Implement the oracle for a hidden string.
    * *Metric:* Accuracy + Least Time.
2.  **GHZ State Construction (10 Marks):** Create a Greenberger-Horne-Zeilinger (GHZ) state.
    * *Metric:* Least Gate Count + Least Time.

---

## 📮 Submission Guidelines

### 1. File Naming
Please rename your notebooks as follows:
* **Task 1:** `<YourName>_Task1.ipynb`
* **Task 2:** `<YourName>_Task2.ipynb`

### 2. Execution
Ensure all cells in your notebooks are run and outputs are visible before saving.

### 3. Report Format
For Task 2, your report should be written in a separate file and attached as a PDF. Critical explanations should be written directly inside the Markdown cells of the notebook.

### 4. Submission Links
Links will be provided via email/WhatsApp upon the start of the event.

---

**Good luck and may your qubits remain coherent!**

Happy Hacking,
*Qiskit Fall Fest Team*
*UCSC ACM Student Chapter*
