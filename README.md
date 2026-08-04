# Machine-Learning-for-the-Characterization-of-the-Earthquake-Nucleation-Process
My BSc thesis: predicting fault friction parameters from simulated earthquake slip profiles with deep learning (Sapienza University of Rome, 2026)

This project investigates whether the physical parameters governing rate-and-state fault friction - *b*, *Dc* (critical slip distance), and *σn* (effective normal stress) - can be estimated from spatio-temporal slip velocity maps of simulated earthquakes, using convolutional neural networks. The goal is to relate these parameters to the critical nucleation length *h\**, the scale beyond which a fault patch can sustain a self-accelerating seismic rupture. 
Since fault properties are not directly observable in the field, this explores whether the inverse relationship, from observable slip data back to underlying friction parameters, can be learned by a neural network trained on synthetic data from the quasi-dynamic simulator [QDYN](https://github.com/ydluo-c/qdyn).

## Usage

1. Run the data generation notebook to build the dataset (or use a pre-generated `dataset_completo.npz`).
2. Run either model notebook to train and evaluate.
3. Use `predici_evento` to run inference on a single event.

## Author

Luca Montefusco, Sapienza University of Rome, 2026

Supervisors: Prof. Chris Marone, Prof. Marco Scuderi, Prof. Giacomo Mastella
