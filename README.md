# MLP for Approximate Low-thrust Transfers

In this repository, a simple Multi-layer Perceptron (MLP) network is implemented for approximating optimal low-thrust transfers. The main reference for this project is [[1]](#1). The authors have shared the datasets that can be downloaded from [Zenodo](https://data.niaid.nih.gov/resources?id=zenodo_10972837).

## Installation & Requirements

To work with this repository, one should have [Python](https://www.python.org/) version that is [3.10](https://www.python.org/downloads/release/python-3100/), since [Tensorflow](https://www.tensorflow.org/) is employed.

Then, one goes to [this](https://data.niaid.nih.gov/resources?id=zenodo_10972837) and download the ```fuel_optimal_db.txt``` file. Then, paste this into a folder called:

```txt
datasets/fuel_optimal_db.csv
```

Finally, one can install the required packages via:

```bash
pip install -r requirements.txt
```

## Usage

The main script is [space_traj_mlp.ipynb](space_traj_mlp.ipynb), and shows how to create a MLP with 2 hidden layers with 64 and 32 neurons, respectively.

The model is then trained over a small number of epochs, and the results are plotted.

## Contributing

Currently, only invited developers can contribute to the repository.

## License

The work is under license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc/4.0/), that is an Attribution Non-Commercial license.


## References
<a id="1">[1]</a> 
Acciarini, G., Gondelach, D., & Izzo, D. (2024). 
Computing low-thrust transfers in the asteroid belt, a comparison between astrodynamical manipulations and a machine learning approach.
https://www.researchgate.net/publication/380974504_Computing_low-thrust_transfers_in_the_asteroid_belt_a_comparison_between_astrodynamical_manipulations_and_a_machine_learning_approach.
