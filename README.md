# 🚀 workload_vae

> A modular and extensible Python library for processing and generating synthetic workload data/logs of real parallel workloads from production systems using Variational Autoencoders (VAEs) 🔬📊

---

## 📚 Overview

`workload_vae` provides an end-to-end pipeline to:

- ✅ Load and clean CSV workload logs in SWF (Standard Workload Format)
- 📊 Perform exploratory data analysis (EDA)
- 🧠 Build and train deep VAE models for learning latent representations
- 🧪 Generate synthetic workload data
- 📈 Compare real vs. synthetic distributions for statistical fidelity

Whether you're a researcher, engineer, or data scientist working in performance modeling, resource scheduling, or workload synthesis — this library is for you.

---

## 📦 Installation

You can install this library directly from GitHub using:

```bash
pip install git+https://github.com/RakeshHG/vae_workload.git
```

---

## 🧰 Features

| Feature                       | Description |
|------------------------------|-------------|
| 🧹 Data Cleaning              | Impute missing values, drop invalid fields, apply transformations |
| 📊 Visual EDA                | Histograms, count plots, correlation heatmaps |
| 🧠 VAE Architecture           | Encoder, decoder, latent space, customizable layers |
| 🏋️‍♀️ Training & Validation   | Train loop with β-VAE regularization, loss plots |
| 🧬 Sample Generation          | Draw from latent space to synthesize new job entries |
| 🧪 Distribution Comparison    | KDE-based plots of feature distributions |

---

## 🧪 Example Usage

```python
#Coming soon

```

---

## 🗂 Project Structure

```
workloadgen/
│
├── workloadgen/                  # Python package
│   ├── __init__.py              # Make it a package
│   ├── data_preprocessing.py    # Data cleaning, scaling, etc.
│   ├── vae_model.py             # VAE model definition
│   ├── train.py                 # Training loop and validation
│   ├── generate.py              # Sample generation and postprocessing
│   ├── evaluate.py              # Data comparison and plotting
│
├── scripts/
│   ├── train_and_generate.py    # CLI entry-point to train and generate
│
├── tests/                       # Unit tests
│   ├── test_data_preprocessing.py
│   ├── test_generate.py
│
├── examples/                    # Jupyter or Python scripts using the library
│   └── example_usage.ipynb
│
├── README.md                    # Project overview
├── LICENSE                      # Choose a license (e.g., MIT)
├── setup.py                     # For setuptools-based installation
├── pyproject.toml               # Modern build system config
├── requirements.txt             # List dependencies
├── .gitignore                   # Ignore virtual envs, model files, etc.

```

---

## 🧑‍💻 Development

To contribute:

```bash
# Clone and install in editable mode
git clone https://github.com/RakeshHG/vae_workload.git
cd vae_workload
pip install -e .
```

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgements

This project is inspired by real-world HPC workloads and research into workload modeling with deep generative models. Kudos to the community for SWF datasets and PyTorch ❤️

---

