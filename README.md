# Starcraft2_RL

## Installation

- Install the stable baseline library that gathers several Reinforcement Learning algorithms :  
```pip install stable-baselines3```  
This should also install the dependencies like PyTorch, Gym, ...

- Install StarCraft II game proto on Linux or WSL at the following [link](https://github.com/Blizzard/s2client-proto "StarCraft2 proto"). Also download the SMAC Maps archive [here](https://github.com/oxwhirl/smac "SMAC") in the SMAC Maps section. Place the map file 3s5z.SC2Map in the Maps folder of the StarcraftII installation folder. 

- Set the StarCraft path to the folder where you installed the game:  
```export SC2PATH="~/StarCraftII/"```

- Install the burnysc2 library, that makes the connection between Python code and the StarCraft II game:  
```pip install burnysc2```  

## Training

To run the training simply enter this command line in the SC2_RL folder:  
```python trainppo.py```
