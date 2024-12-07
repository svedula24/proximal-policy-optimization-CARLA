# Proximal Policy Optimization using CARLA Driving Simulator
This repo is describes how to run a Reinforcement Learning (RL) experiement with CARLA. We worked with the Proximal Policy Optimization Algorithim using StableBaselines3.

Documentation: https://stable-baselines3.readthedocs.io/en/master/
## Instructions
### 1. Create a conda environment. 

- https://docs.anaconda.com/miniconda/
- `conda create -n carla python=3.8`
- This requires python 3.8 in order to work with CARLA properly

### 2. Activate your Conda Environment in the command line

- `conda activate [env_name]`


### 3. Install the following dependencies.

- `pip install stable-baselines3`
- `pip install tensorflow`
-  `pip install opencv-python`

### 5. Run Carla on your terminal at the specifed port number
- `./CarlaUE4.sh -carla-rpc-port=2000 -norelativemousemode` # port 2000 is the port number we are using


### 6. Open the files train.py and carenv.py in your IDE, and activate the Conda Environment in your terminal 
- Run `conda activate [env-name]` in your IDE terminal.
- You should see an indication that you are in the environment, as presented below

### 7. Run the file train.py in the terminal
- `python train.py`

### 8. Watch as your model trains!





