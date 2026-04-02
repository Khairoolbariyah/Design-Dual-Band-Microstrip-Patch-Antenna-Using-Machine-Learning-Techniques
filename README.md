# Antenna Design Optimization using Machine Learning (FYP)

This project focuses on the **Design of a Dual-Band Microstrip Patch Antenna** for wireless communication applications, optimized using **Machine Learning** techniques.

## 📡 Project Overview
The main goal was to automate the antenna design process. Instead of traditional trial-and-error in CST Studio Suite, I implemented ML models to predict antenna parameters accurately and efficiently.

## 🤖 Machine Learning Implementation
I compared two main architectures to optimize the antenna's dimensions:
* **Random Forest Regressor:** For initial parameter prediction.
* **Artificial Neural Networks (ANN):** To achieve higher accuracy in predicting S-parameters (S11).
* Reverse Design 
Input = Physical Dimensions (Wp, Lp, etc.)
Output = Simulation Results (Freq/S11)
* Inverse Design 
Input = Simulation Results (Freq/S11)
Output = Physical Dimensions (Wp, Lp, etc.)

## 🛠 Tech Stack
* **Simulation:** CST Studio Suite (also for generate dataset)
* **Programming:** Python (Scikit-Learn, TensorFlow/Keras, Pandas, Matplotlib)
* **Optimization:** Machine Learning (Random Forest & ANN)

## 📊 Results
* Successfully predicted dual-band frequencies at **2.4 GHz** and **5.2 GHz** for both ML in forward and inverse design.
* Significant reduction in simulation time compared to manual parametric sweeps.
