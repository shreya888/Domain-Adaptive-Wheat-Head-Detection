# ENGN8536-project

### Running instructions ###

To run in the default settings please follow the following steps:

1. Install the dependencies listed in `./requirements.txt`
2. Paste the `dataset.zip` file in the `./data` ditectory.
3. Go into the `./src/` directory and run `python main.py` to run the project using default hyperparameters.
4. Hyperparameters can be changed from the `./src/utils.py` file's `get_args()` function.
5. To separately evaluate the model run `python evaluate_results.py` from inside the `./src/` directory.

*** It is recommended to run the project in a Linux environment as 
all the functionalities were tested in a Linux machine. *** 

### Directory Structure ###
```
├── data
│   └── *                   <- put the dataset.zip here before running
├── results                 <- contains results about different metrics in different modes
├── documents               <- original paper PDF
├── notebooks               <- notebooks for explorations / prototyping
├── experiments             <- code for all the experiments performed
└── src                     <- all source code, internal org as needed
```
