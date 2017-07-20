# Awesome Machine Learning for Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


Machine Learning is becoming a common technique to address robotics tasks. This repository intends cover this usage from a broad point of view.


# Papers
## Learned Approximate Inference
* [Auto-Encoding Variational Bayes](http://arxiv.org/abs/1312.6114), by Kingma et Al.
* [Stochastic Backpropagation and Approximate Inference in Deep Generative Models](https://arxiv.org/abs/1401.4082), by Rezende et Al.
* [Variational Inference with Normalizing Flows](https://arxiv.org/pdf/1505.05770v6.pdf), by Rezende et Al.
* [Improved Variational Inference with Inverse Autoregressive Flows](https://fr.arxiv.org/pdf/1706.02326), By Kingma et Al.
* [Gradient Estimation Using Stochastic Computation Graphs](https://arxiv.org/abs/1506.05254) by Schulman et Al.
* [Deep Variational Bayes Filters: Unsupervised Learning of State Space Models from Raw Data](https://arxiv.org/abs/1605.06432) by Karl et Al.
* [Deep Kalman Filters](https://arxiv.org/abs/1511.05121) by Krishnan et Al.
* [Variational Inference: Foundations and Modern Methods](http://www.cs.columbia.edu/~blei/talks/2016_NIPS_VI_tutorial.pdf), byu Blei et Al.

## Reinforcement Learning
### Deep Reinforcement Learning
* Deep Q-Learning: [Human-level control through deep reinforcement learning](https://www.nature.com/nature/journal/v518/n7540/full/nature14236.html), by Mnih et Al.
* DDPG: [Continuous control with Deep Reinforcement Learning](https://arxiv.org/abs/1509.02971), by Lillicrap et Al.
* [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952), by Schaul et Al.
* Auxiliary tasks: [Reinforcement learning with unsupervised auxiliary tasks](https://deepmind.com/blog/reinforcement-learning-unsupervised-auxiliary-tasks/), by Jaderberg et Al.
### Reinforcement Learning Theory
* REINFORCE: [Simple statistical gradient-following algorithms for connectionist reinforcement learning](http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf), Williams et Al.
* Policy Gradient Theorem: [Policy Gradient Methods for Reinforcement Learning with Function Approximation](https://papers.nips.cc/paper/1713-policy-gradient-methods-for-reinforcement-learning-with-function-approximation.pdf), Sutton et Al.
* [Deterministic Policy Gradient Algorithms](http://proceedings.mlr.press/v32/silver14.pdf), Silver et Al.

### Policy Search
* Policy search suvery: [Reinforcement learning of motor skills with policy gradients](http://www.kyb.mpg.de/fileadmin/user_upload/files/publications/attachments/Neural-Netw-2008-21-682_4867%5b0%5d.pdf), by Peters and Schaal.
* [Guided policy search](https://graphics.stanford.edu/projects/gpspaper/gps_full.pdf), by Levine et Al.

## Meta-Learning
### Curriculum learning
* [Automated curriculum learning](https://arxiv.org/abs/1704.03003), by Graves et Al.
### Multi-task learning
* [Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks](https://arxiv.org/abs/1703.03400), by Finn and Al.

# Implementations
* [OpenAI Gym](https://gym.openai.com/): A Python library providing many simulation environments.
* [OpenAI baselines](https://github.com/openai/baselines): Implementations of Deep Reinforcement Learning algorithms by experts.
* [Guided Policy Search](http://rll.berkeley.edu/gps/): Implementation of the Guided Policy Search algorithm.
* [Keras-RL](https://github.com/matthiasplappert/keras-rl): A keras-compatible Deep Reinforcement Learning framework (DQN, SARSA, DDPG...).
* [Deepmind DQN](https://github.com/deepmind/dqn): Deepmind's implementation used for the [Nature paper](https://www.nature.com/nature/journal/v518/n7540/full/nature14236.html).
* [Devsisters DQN](https://github.com/devsisters/DQN-tensorflow): A nice DQN implementation.

## Implementing RL algorithms
* [Best pratices in implementing Deep RL algorithms](https://blog.openai.com/openai-baselines-dqn/), as part of this blog post.
* [A note about gradient clipping](https://github.com/devsisters/DQN-tensorflow/issues/16), by Karpathy. Further explained in a [blog post](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b)
