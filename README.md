# Multilayer Perceptron (Fashion-MNIST)

Deep vs. wide fully-connected networks on Fashion-MNIST in PyTorch — comparing
architecture shape, weight initialization, learning rate, batch size, and optimizers.

Built for an Artificial Neural Networks course assignment.

## What this project covers

- Deep and wide MLP architectures with train/validation splits
- He, Xavier, and random weight initialization
- Learning-rate and batch-size sweeps (Q3.1, Q3.2)
- Adam vs. SGD optimizer comparison

## Project layout

| File | Description |
|------|-------------|
| `main.ipynb` | Models, training loops, and experiments |
| `Project_Description.pdf` | Assignment brief |
| `Report.pdf` | Report |
| `requirements.txt` | Python dependencies |

## Quick start

```bash
python -m venv .venv
.venv\Scripts\activate          # macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

Fashion-MNIST downloads to `./data` on first run. Notebook outputs are saved so plots render on GitHub.
