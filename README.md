# **Quantum Computing and The Deutsch’s Algorithm**

### Emerging Technologies

---

##### Ryan Harte (G00338424)

---

### **Introduction**

This repository contains two Jupyter Notebooks focused on quantum computing concepts and implementations using Qiskit, IBM's open-source quantum computing software development framework.

### **Jupyter Notebook Overview**

- **Project Notebook:** This notebook provides a detailed exploration of Deutsch's Algorithm, a foundational quantum computing algorithm. It includes an introduction to the problem solved by Deutsch's Algorithm, a comparison of quantum and classical approaches, implementation details using Qiskit, and simulation results.

- **Tasks Notebook:** This notebook contains various tasks dedicated to exploring fundamental tasks in quantum computing.

### **Installation Setup Guide**

The following is a step by step guide on how you can clone this repository down on to your own machine and get it running. Please ensure you have the following prerequisites installed before continuing.

### **Prerequisites**

Installation of `git` <br>
Installation of `Python 3` (versions 3+)
or
Installation of [Anaconda](https://www.anaconda.com/download/)<br>
Installation of `Visual Studio Code`, with extension `Jupyter` & `notebook`

<a id="step1"></a>

### **Step 1: Clone Repository:**

In order to clone the github repository, use the following command:<br>
git clone https://github.com/The-Mad-Ryanosaurus/Emerging-Technologies.git<br>
This link can be found in the code button at the top of this page under the HTTPS tab.

### **Step 2: Install Project Dependencies:**

In the same terminal window you used to clone the repository, do the following step by step:

1. cd Emerging-Technologies
2. `pip install notebook`
3. `pip install qiskit`
4. `pip install qiskit-aer`
5. `pip install matplotlib`
6. `pip install pylatexenc`
7. `pip install qiskit-ibmq-provider` then do `pip install qiskit-ibm-runtime`: This is so you can connect to IBM Quantum devices to create and visualize circuits and execute them both on simulations and real quantum devices. You can see an example of this in my project notebook.
8. `pip install qiskit[visualization]`

Remember to restart the Jupyter kernel if you encounter any import errors after installation.

Should the installs fail, run your command prompt as an administrator and try again from [Step 1](#step1). If you do not have administration permissions on your machine, try adding '--user' after each 'pip install'. Ex: pip install --user "_dependency_"

### **Step 3: Open Project in Visual Studio Code:**

Still in the same terminal window do the following:<br>
code .<br>
This will open VS code and you can now access and run both jupyter notebooks.
