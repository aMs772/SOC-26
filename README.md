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

``Built a small neural network to identify hand written digits. The relevant code is uploaded to a branch in this repo``

## week 5-6
learnt about pytorch and transformers

built my first ever transformer of 10 Million parameter approx. I used the book series ``Percy jackson and the olympians`` as my dataset in an attempt to replicate the author's tone and character traits like sarcastic, self thinking

input.txt is the combined data file
GPT.ipynb is the jupyter notebook containg the entire code

The model takes about 45 minutes to train for 5000 iterations.

## Results

Although the gpt doesent produce perfect english sentences, it has learnt the author tone and style. The text produced is inclined towards first person, witty and sarcastic tone.



