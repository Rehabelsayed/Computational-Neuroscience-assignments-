# Computational Neuroscience Assignments

<p align="center">
  <img src="ai_cover.png" alt="Neural Network Illustration" width="500"/>
</p>

Welcome to the official repository for **Computational Neuroscience Assignments**.  
This repo contains practical implementations and solutions for assignments related to modeling neurons and building basic artificial neural networks using Python.

---

## About the Course

**Computational Neuroscience** blends biology and computation to simulate how real neurons behave. Through these assignments, we aim to:
- Understand biological neuron models
- Simulate artificial neurons and networks
- Explore learning mechanisms like backpropagation
- Implement core neural architectures such as RNNs and MLPs

---

## Repository Structure

Each assignment is written in a standalone `.ipynb` file with clear, step-by-step implementations.

| File Name                                 | Topic                                           |
|-------------------------------------------|-------------------------------------------------|
| `Back propagation.ipynb`                  | Backpropagation learning algorithm              |
| `RNN_MODEL.ipynb`                         | Recurrent Neural Network implementation         |
| `Computational_Neuroscience_Assignment.ipynb` | Basic Feedforward ANN using tanh activation |

---

## How to Run the Code

1. Clone this repository to your machine:
```bash
git clone https://github.com/your-username/Computational-Neuroscience-assignments.git
```

2. Navigate to the folder and open the notebooks with Jupyter:
```bash
jupyter notebook
```

3. Run the cells and follow the comments in each notebook.

---

## Sample Code Snippet

```python
# Custom tanh activation function
def tanh(x):
    return (math.exp(x) - math.exp(-x)) / (math.exp(x) + math.exp(-x))
```

---

## Tools Used

- Python 3.x
- Jupyter Notebook
- Standard libraries: `math`, `random`

---

## License & Notes

This repository is created for academic purposes under the guidelines of fair educational use.  
All assignments reflect independent effort and comply with university integrity policies.

---

**Created by:** [Your Name]  
**Course:** Computational Neuroscience  
**Instructor:** Dr. [Instructor Name]  
**University:** [University Name]
