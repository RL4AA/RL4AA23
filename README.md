# 1st collaboration workshop on Reinforcement Learning for Autonomous Accelerators (RL4AA'23)

This repository contains the material for the second day of the [RL4AA'23](https://indico.scc.kit.edu/event/3280/overview) event.

Homepage for RL4AA Collaboration: [https://rl4aa.github.io/](https://rl4aa.github.io/)

## Workshop organizing committee

- Andrea Santamaria Garcia (KIT)
- Simon Hirländer (University of Salzburg)
- Jan Kaiser (DESY)
- Chenran Xu (KIT)

## Slides

- [Welcome and basics of RL](https://github.com/RL4AA/RL4AA23/blob/main/slides/SantamariaGarcia_intro_to_RL.pdf), Andrea Santamaria Garcia
- [Advanced concepts in RL](https://github.com/RL4AA/RL4AA23/blob/main/slides/Hirlaender_advanced_concepts.pdf), Simon Hirländer
- [RL in particle accelerator control: are we there yet?](https://github.com/RL4AA/RL4AA23/blob/main/slides/Hirlaender_IBPT_seminar.pdf), Simon Hirländer

## Python tutorial: reinforcement learning implementation example

- Github repository containing the material: [https://github.com/RL4AA/RL4AA23](https://github.com/RL4AA/RL4AA23)
- Tutorial in slide form: [here](https://rl4aa.github.io/RL4AA23/tutorial.slides.html#/)

## Getting started

- First, download the material to your local disk by cloning the repository:
`git clone https://github.com/ansantam/RL4AA23`
- If you don't have git installed, you can click on the green button that says "Code", and choose to download it as a `.zip` file.

### Install `ffmpeg`

- OS X: `brew install ffmpeg`
- Ubuntu: `sudo apt-get install ffmpeg`
- Ubuntu 14.04: sudo apt-get install libav-tools`
- With pip: `pip install imageio-ffmpeg`

### Setup the environment locally

- Open terminal app
- (Suggested) Create a virtual envrionment using `conda` or `venv`.

#### venv

```bash
python3 -m venv rl4aa
source rl4aa/bin/activate
pip3 install -r requirements.txt
jupyter notebook
```

- Open the tutorial notebook `tutorial.ipynb` in the jupyter server in browser
- When you are done type `deactivate`

#### conda only

Instructions to install conda [here](https://docs.conda.io/projects/conda/en/4.6.1/user-guide/install/index.html)

```bash
conda env create -f environment.yml
conda activate rl4aa
jupyter notebook
```

- Open the tutorial notebook `tutorial.ipynb` in the jupyter server in browser
- When you are done type `conda deactivate` to deactivate the virtual environment

#### conda + pip

```bash
cd path_to_your_folder/RL4AA23
```

```bash
conda create -n rl4aa python=3.10
conda activate rl4aa
pip3 install -r requirements.txt
jupyter notebook
```

- Open the tutorial notebook `tutorial.ipynb` in the jupyter server in browser
- When you are done type `conda deactivate` to deactivate the virtual environment
