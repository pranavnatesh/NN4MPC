# NN4MPC

Structured necessary Python Notebooks for training and testing Neural Networks for the Model Predictive Control (**NN4MPC**) of a Switch-Averaged Model of a DC-DC converter.

Training Pipeline:
1. Generate a grid using Generators/Grid_Generator
2. Generate training data using Generators/Training_Data_Generator
3. Train a NN using Generators/NN_Trainer
4. Evaluate performance using Simulation_and_Visualisations/NN4MPC

During the trainig pipeline, pay close attention to what data is being accessed. The grid, training data, and NN models are saved in folders and need not be accessed manually.