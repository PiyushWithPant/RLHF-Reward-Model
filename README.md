# RLHF Pipeline - Reward Model 🚀

### Description 📝

This notebook demonstrates the Reward Model pipeline within the Reinforcement Learning with Human Feedback (RLHF) framework. It outlines the steps to train a reward model using preference data, which is a key component in aligning AI behavior with human intent.
The RLHF pipeline consist of 3 phases -

1. Supervised Fine-tuning
2. Reward Model
3. Fine-Tuning with Reinforcement learning (PPO usually).

This notebook only focuses on the second phase i.e. _Reward Model_

### Features 🌟

- Loads and preprocesses preference data for reward model training.
- Defines and initializes the reward model architecture.
- Training Reward Model using LLAMA (2), or any other LLM
- Applying PEFT and LORA to save memory and time!
- Training and Testing the Reward model
- Training with a powerful GPU (you can choose not to use it)

### Prerequisites 📦

- Python 3.x
- TensorFlow/PyTorch (or other supported frameworks)
- Required Python libraries (mentioned in the notebook)
- If you are training a big LLM like Llama 2 7b+, you will require GPU (I used Ax100 40GB for this project, without PEFT, you will require 2 or 3 of these bad boyz)
- Basic knowledge of Reinforcement Learning (to understand what's going on)

### How to Use 🛠️

1. Open the notebook in Jupyter or your preferred IDE.
2. Follow the cells step-by-step to execute the pipeline (try not to skip any).
3. Modify parameters as needed for custom datasets.

### Outputs 📊

- The ouput should be a SCALAR value i.e. the reward for the response for a given prompt
- Now your model will distinguish between a good response and a bad response - How coooool!

### Acknowledgments 🙌

This pipeline is part of the RLHF methodology, which incorporates human feedback for creating safer and more aligned AI systems. If you encounter any issue with the code or want to know something, please feel free to contact me! Thank youuu :-)

> By Piyush Pant ( पियूष पंत )
