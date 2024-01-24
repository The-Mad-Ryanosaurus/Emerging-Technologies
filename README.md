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

Should you just wish to view the notebooks without installing any software please select the links below:<br>

- **Project Notebook:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Mad-Ryanosaurus/Emerging-Technologies/main?labpath=project.ipynb)<br>
- **Tasks Notebook:** [tasks.ipynb](https://hub.ovh2.mybinder.org/user/the-mad-ryanosa-ng-technologies-p78v34vt/doc/workspaces/auto-h/tree/tasks.ipynb)

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
7. `pip install qiskit-ibmq-provider` then do `pip install qiskit-ibm-runtime`: This is so you can connect to IBM Quantum devices to create and visualize circuits and execute them both on simulations and real quantum devices. You can see an example of this in my project notebook. [Step 4](#step4)
8. `pip install qiskit[visualization]`

Remember to restart the Jupyter kernel if you encounter any import errors after installation.

Should the installs fail, run your command prompt as an administrator and try again from [Step 1](#step1). If you do not have administration permissions on your machine, try adding '--user' after each 'pip install'. Ex: pip install --user "_dependency_"

### **Step 3: Open Project in Visual Studio Code:**

Still in the same terminal window do the following:<br>
code .<br>
This will open VS code and you can now access and run both jupyter notebooks.

### **Step 4: IBM Quantum Platform (_optional_)**

The following is a guide to setup IBM Quantum Platform so you can simulate the Deutsch's Algorithm in a real world IBM Quantum Computer.

1. **Obtain an IBM Quantum Platform API:**<br>
   - You will need to create an account at [IBM Quantum Lab](https://docs.quantum.ibm.com/start/setup-channel#ibm-quantum-platform)
   - Once you have an account you can navigate to the `IBM Quantum Platform Dashboard` and copy your `API Token` from the top right of your screen.
2. **API Token Update:**<br>
   - In the project notebook, users should replace the placeholder `api_token = 'placeholder'` with their own API token from IBM Quantum Platform.
3. **Run the IBM Quantum Simulation:**<br>
   - In the project notebook select `|>|> Run All`. This will run all cells in a linear fashion ensuring the connection to an IBM quantum computer is successful and runs the Deutsch's Algorithm on a real quantum device<br>
     These steps are crucial for users who wish to interact with IBM Quantum Computers and run the Deutsch's Algorithm in my Jupyter notebook.
