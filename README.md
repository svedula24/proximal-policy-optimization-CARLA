# StableBaselines3-with-Carla-Tutorial
This repo is a simple tutorial describing how to run an RL experiment with StableBaselines3. A few changes have been made to the files in this repository for it to be compatible with the current version of stable baselines 3. 
The files provided are courtesy of the Youtube channel 'Full Sim Driving'. 

The link to the video can be found here: https://www.youtube.com/watch?v=f31Mu5Yxc60&list=PLKtcx3w8WPyP7rxCHByn9pt66sT4hi3Jp.

The carenv.py and train.py files have been slightly altered to fit the current standards. 

Documentation: https://stable-baselines3.readthedocs.io/en/master/
## Package Setup
### 1. Create a conda environment if you have not already done so. 

- https://docs.anaconda.com/miniconda/
- `conda create -n carla python=3.8`
- Keep in mind, this will require python 3.8 to run Carla properly
- Remember that you can always create a new environment, if an old one has been messed up.


### 2. Activate your Conda Environment in the command line

- `conda activate [env_name]`


### 3. Install Stable Baselines 3 with the following command.

- `pip install stable-baselines3`


### 4. Install python packages Tensorflow and Open-CV.

- `pip install tensorflow`
-  `pip install opencv-python`


### 5. Run Carla on your terminal at the specifed port number
- `./CarlaUE4.sh -carla-rpc-port=2000 -norelativemousemode` # port 2000 is the port number we are using


![image](https://github.com/user-attachments/assets/b319b76a-bdbf-46e6-b5f6-813453eb55e3)

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




