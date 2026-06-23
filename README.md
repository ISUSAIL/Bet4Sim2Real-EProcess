# Sim-to-Real Betting on the E-Process

Bringing "simulators" to anytime-valid confidence sequences. The notebook
[`demo.ipynb`](demo.ipynb) implements **Algorithm 1 (Approximate-Kelly betting
confidence sequence)** and reproduces the bound-width / coverage figures.

## Requirements

- [conda](https://docs.conda.io/en/latest/miniconda.html) (Miniconda or Anaconda)
- Python 3.9+


## Setup

Clone this repository and enter it:

```bash
git clone https://github.com/ISUSAIL/Bet4Sim2Real-EProcess.git
cd Bet4Sim2Real-EProcess
```

Create and activate a conda environment, and install Jupyter:

```bash
conda create -n bet4sim2real python=3.10 -y
conda activate bet4sim2real
pip install notebook
```

## Run

Open [`demo.ipynb`](demo.ipynb) in VSCode and run all
cells (**Cell → Run All**). The first
cell installs `numpy` / `scipy` / `matplotlib` and clones `Bet4Sim2Real`, so an
internet connection is needed the first time you run it.

## Acknowledgments

The synthetic examples (distribution definitions and simulator banks) are inherited from <https://github.com/ISUSAIL/Bet4Sim2Real.git>, which the notebook clones on first run.

