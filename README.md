<h1 align="center">IDATG2208 – Introduksjon til maskinlæring</h1>

<p align="center"><strong>Bjørn Ivar Thorsen Høie</strong><br>NTNU Gjøvik · Autumn 2026</p>

My mandatory assignments for IDATG2208, written as Jupyter notebooks.

| # | Topic | Dataset |
|---|-------|---------|
| [1](Assignment%201/Assignment_1_IDATG2208.ipynb) | Regression (linear, polynomial, Ridge/Lasso, random forest) | Superconductivity (UCI) |
| [2](Assignment%202/Assignment-2.ipynb) | Classification (decision trees, SVM) | Adult Census Income (OpenML) |
| [3](Assignment%203/Assignment-3.ipynb) | Deep learning (dense networks, CNNs, dropout) | Fashion-MNIST, CIFAR-100, EuroSAT, KMNIST |

## Run

Requires **Python 3.12** (TensorFlow does not support 3.14 yet).

```bash
pip install numpy pandas matplotlib seaborn scikit-learn ucimlrepo xlrd tensorflow tensorflow-datasets importlib_resources jupyter
jupyter notebook
```

The datasets download automatically when you run a notebook.