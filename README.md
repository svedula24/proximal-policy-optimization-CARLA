# Proximal Policy Optimization using CARLA Driving Simulator
This repo is describes how to run a Reinforcement Learning (RL) experiement with CARLA. We worked with the Proximal Policy Optimization Algorithim using StableBaselines3.

Documentation: https://stable-baselines3.readthedocs.io/en/master/
## Package Setup
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

## Run Files on the GUI
#### Disclaimer
I used Visual Studio Code for my IDE on Nautilus, but you may use whichever IDE you want. Just make sure to follow the same steps, however the execution could be slightly different based on which IDE you use. 

### 1. Open the files train.py and carenv.py in your IDE, and activate the Conda Environment in your terminal 
![image](https://github.com/user-attachments/assets/934c9a01-c2f7-49d3-8164-a823b5151cbc)

- Run `conda activate [env-name]` in your IDE terminal.
- You should see an indication that you are in the environment, as presented below
![image](https://github.com/user-attachments/assets/d90807f7-d6dd-47cf-b070-8b965a76578c)

### 2. Run the file train.py in the terminal

- `python train.py`
  
![image](https://github.com/user-attachments/assets/e8c8bebc-b766-4f72-9a39-13a71e0f6adb)

### 3. Watch as your model trains!

![image](https://github.com/user-attachments/assets/c4d744fd-21af-42b9-9bf8-529eba039a0d)




