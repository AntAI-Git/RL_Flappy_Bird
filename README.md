# Reinforcement Learning : Flappy Bird Text
The notebook presents the implementation of the Q-Learning and Monte Carlo algorithms to solve the Text-Flappy-Bird game

![TFB_agent](https://github.com/AntAI-Git/RL_Flappy_Bird/blob/934f8b0025401b3e75e0b9c26a8734d718a7d6b7/TFB_agent.gif)

## Text flappy bird game

The implementation of the environment can be found here:
https://gitlab-research.centralesupelec.fr/stergios.christodoulidis/text-flappy-bird-gym


## Performance

The average sum of rewards achieved by both agents on a given episode (during testing):
```python 
Q-Learning: 120
Monte Carlo: 45000
```

Note:
The Monte Carlo agent has perfectly master the game (no death of the bird) after 3000 episodes of training. Thus the sum of rewards has been limited artificially and correspond to the score limit I fixed at 100,000,000.