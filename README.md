# ChatGPT from Scratch

The goal is to build a GPT-style language model from scratch, starting from the very basics and gradually working up to transformers. Rather than relying on high-level libraries that do everything for you, the idea is to actually understand what is happening at each step. This readme covers my progress through the first four weeks.

---

## Week 1 - Data Science Tools

Spent this week getting comfortable with the core tools used in most machine learning work. Nothing too deep, just making sure I had a solid base before moving on.

- Python basics - syntax, loops, functions, data structures
- NumPy - working with arrays and doing numerical operations efficiently
- Pandas - loading datasets, cleaning data, and basic analysis
- Matplotlib - visualizing data through plots and graphs

---

## Weeks 2 and 3 - Neural Networks

These two weeks were about understanding how neural networks actually work, not just using them. Spent a good amount of time on the math behind training before writing any code.

- How neurons, layers, and activation functions are structured
- Forward pass and how loss is computed
- Backpropagation and gradient descent explained from scratch
- Tuning hyperparameters like learning rate, batch size, and epochs
- Regularization techniques like dropout to prevent overfitting

Followed the StatQuest playlist (videos 74 to 84). The explanations are simple and to the point, watched most of it at 2x.

---

## Week 4 - Convolutional Neural Networks

Built on the neural network foundation and looked at CNNs, which are designed for data that has some spatial structure to it.

- How convolutional layers work - filters, pooling, and feature maps
- Why CNNs are well suited for image and pattern recognition tasks
- How to stack layers to learn increasingly abstract features
- Some practical notes on training and avoiding common mistakes

Followed StatQuest again for this one (videos 86 to 91).

---

## What is coming next

- Week 5 - Getting into PyTorch and learning how to build models using it
- Week 6 - The main project: building a GPT-style language model from scratch
- Weeks 7 and 8 - Optional extensions like fine-tuning pretrained models or building a small web app around the final model
