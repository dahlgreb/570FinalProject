# CSC 570 Final Project - Cal Poly
Instructor: Dr. Rodrigo Canaan

Team Members: Ben Dahlgren, Sanjana Gundala, Gabe Hyun, Sean Nesbit

## Resources
- OpenAI Gym (https://www.gymlibrary.ml/)
- Pytorch(https://pytorch.org/)
- Code adapted from (https://towardsdatascience.com/deep-q-network-dqn-iii-c5a83b0338d2)

Packages

    pip install numpy
    pip install gym[atari,accept-rom-license]==0.21.0
    pip install opencv-python
    pip install torch==1.10.1+cu113
    pip install torchvision==0.11.2+cu113
    pip install torchaudio===0.10.1+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html
    pip install tensorboard (for tensorboard training data plots)

## How to Run Simlation

> python run_sim.py \<atari-game-code\> \<model-path\>

The game codes are the following:

    Breakout: "Breakout-v0"
    Pong: "Pong-v0"
    Space Invaders: "SpaceInvaders-v0"
    

The models can be found in the model_weights directory.

Have fun!

## How to Run Training
    
Training was done in the DRL_DQN notebooks. Transfer learning is enabled by passing the path to trained model weights in a .dat file to the DQN constructor.

Training can be done locally with a properly configured environment and fairly beefy hardware or you can just run on [Google Colab](https://colab.research.google.com/github/dahlgreb/570FinalProject/blob/master/training/DRL_DQN_pong_transfer.ipynb). Running on colab may require downloading model weights from this repo and uploading to Colab.

## Results

You can find some of our results in the screenshots section.
