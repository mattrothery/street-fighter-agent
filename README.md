# A Google Colab implementation to train an agent to play Street Fighter II, using OpenAI Gym Retro and PPO2

This colab notebook takes advantage of OpenAI's Gym Retro (https://openai.com/blog/gym-retro/) environments, in particular the premade environment for Street Fighter II. Note that the ROM file for the game is not included for copyright reasons.

The model used to train the agent is PPO2 (Proximal Policy Optimization, from this paper: https://arxiv.org/abs/1707.06347). This model has been incorporated in the Stable Baselines package (https://stable-baselines.readthedocs.io/en/master/index.html), which allows for syntax similar to sklearn for Reinforcement Learning algorithms.

Using this notebook, an agent can be trained/tested by playing against the games own AI. Videos can be exported of the trained model playing the game!
