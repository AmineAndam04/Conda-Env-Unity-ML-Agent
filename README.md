# Conda-Env-Unity-ML-Agent

Unity ML Agent is a useful toolkit for researchers and hobbyists to create custom environments for their Reinforcement Learning (RL) projects. However, downloading all the necessary packages may be frustrating, especially the dependency conflicts between different libraries.

In this repository, you can  a YAML file that presents a ready-to-use Anaconda environment, purpose-built for your Unity ML-Agents toolkit. This spares you the need to tackle dependency conflicts one by one. 

# How to use (1)
  1. Create a conda environment (use python 3.8 )
  2. Install the libraries in the  requirements.txt file
# How to use (2) [Works for MacOS]
 1. Download the yaml file.
 2. Run:
    ```conda env create -f ml-agents.yaml```

 3. Clone the ML-Agents Toolkit Repository:  ```git clone --branch release_20 https://github.com/Unity-Technologies/ml-agents.git```
 4. Activate the newly created environment ```conda activate ml-agents```
 5. Run:
```sh
cd /path/to/ml-agents
python -m pip install ./ml-agents-envs
python -m pip install ./ml-agents
```
  5. To test run ```mlagents-learn --help```. If it executes without errors, you're all set

Step 3 & 4 are from [ML agents docs](https://github.com/Unity-Technologies/ml-agents/blob/develop/docs/Installation.md)
