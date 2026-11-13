# Deep Learning with Tensorflow and Keras From Codebasics

A hands-on, notebook-first collection for learning the foundations of deep learning and applying them to practical classification and natural language processing tasks. The repository progresses from matrix operations and model fundamentals to TensorFlow/Keras workflows, image models, text embeddings, and efficient input pipelines.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-Deep%20Learning-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter notebooks">
  <img src="https://img.shields.io/badge/NumPy-Arrays-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Gensim-NLP-4B8BBE?style=flat-square" alt="Gensim">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Activation-Sigmoid%20%7C%20Tanh%20%7C%20ReLU-8A2BE2?style=flat-square" alt="Activation function badges">
  <img src="https://img.shields.io/badge/Optimization-Gradient%20Descent%20%7C%20SGD-2E8B57?style=flat-square" alt="Optimization badges">
  <img src="https://img.shields.io/badge/Loss-MAE%20%7C%20Binary%20Cross--Entropy-FF8C00?style=flat-square" alt="Loss function badges">
  <img src="https://img.shields.io/badge/Metrics-Precision%20%7C%20Recall%20%7C%20F1-4682B4?style=flat-square" alt="Metric badges">
  <img src="https://img.shields.io/badge/Models-ANN%20%7C%20CNN%20%7C%20Word2Vec-DC143C?style=flat-square" alt="Model badges">
  <img src="https://img.shields.io/badge/Regularization-Dropout-6A5ACD?style=flat-square" alt="Dropout badge">
</p>

## About

This repository is a practical learning path rather than a packaged Python library. Each numbered folder contains a focused Jupyter notebook, accompanying data, or both. Examples use small implementations and real datasets to show how model inputs are prepared, how training works, and how predictions can be evaluated.

The material covers neural network fundamentals, optimization and loss functions, binary and multiclass classification, common evaluation metrics, regularization, convolutional image classification, transfer learning, word embeddings, and TensorFlow data pipelines. It is useful for learners who want to move from the underlying math to working TensorFlow/Keras examples.

## Learning Path and Contents

Follow the numbered folders in order. Some later topics can also be studied independently.

| # | Topic | What you will explore |
|---:|---|---|
| 1 | [Handwritten digit classification with an ANN](1%20Neural%20Network%20For%20Handwritten%20Digits%20Classification/Neural%20Network%20For%20Handwritten%20Digits%20Classification.ipynb) | MNIST, input normalization and flattening, dense layers, predictions, and a confusion matrix. |
| 2 | [Activation functions](2%20Activation%20Functions/Activation%20Functions.ipynb) | Implement sigmoid, tanh, ReLU, and leaky ReLU and inspect their outputs. |
| 3 | [Matrix basics](3%20Matrix%20Basics/Matrix%20Basics.ipynb) | NumPy arrays, element-wise operations, and matrix multiplication through business examples. |
| 4 | [Loss and cost functions](4%20Loss%20or%20Cost%20Function/Loss%20or%20Cost%20Function.ipynb) | Implement mean absolute error and binary cross-entropy (log loss), including numerical safeguards. A second notebook is also available in the folder. |
| 5 | [Gradient descent for a neural model](5%20Gradient%20Descent%20For%20Neural/Gradient%20Descent%20For%20Neural%20Network.ipynb) | Logistic regression, sigmoid predictions, binary cross-entropy, and a hand-written gradient descent loop. |
| 6 | [Gradient descent with TensorFlow/Keras comparison](6%20Gradient%20Descent%20For%20Neural%20Network/Gradient%20Descent%20For%20Neural%20Network.ipynb) | Compare learned weights and predictions with a simple gradient descent implementation. |
| 7 | [Implement a neural network in Python](7%20Implement%20Neural%20Network%20In%20Python/Implement%20Neural%20Network%20In%20Python.ipynb) | Build a small custom model and compare its predictions with a Keras model. |
| 8 | [Batch, stochastic, and mini-batch gradient descent](8%20Stochastic%20Gradient%20Descent%20vs%20Batch%20Gradient%20Descent%20vs%20Mini%20Batch%20Gradient%20Descent/homeprices_banglore.csv) | The folder currently contains the Bangalore home-price dataset for this lesson. Add or restore the lesson notebook to make the walkthrough available. |
| 9 | [TensorBoard introduction](9%20Tensorboard%20Introduction/Tensorboard%20Introduction.ipynb) | Train an MNIST network and inspect training with TensorBoard. |
| 10 | [Customer churn prediction with an ANN](10%20Customer%20churn%20prediction%20using%20ANN/Customer%20churn%20prediction%20using%20ANN.ipynb) | Prepare customer data, encode categories, scale values, train a binary classifier, and review classification results. |
| 11 | [Precision, recall, F1 score, and true positives](11%20Precision%2C%20Recall%2C%20F1%20score%2C%20True%20Positive/Precision%2C%20Recall%2C%20F1%20score%2C%20True%20Positive.ipynb) | Read a confusion matrix and calculate class-wise precision, recall, and F1. |
| 12 | [Dropout regularization](12%20Dropout%20Regularization/Dropout%20Regularization.ipynb) | Train a binary classifier on sonar data and explore dropout as a regularization technique. |
| 13 | [Handling imbalanced datasets](13%20Handling%20imbalanced%20dataset%20in%20machine%20learning/Handling%20imbalanced%20dataset%20in%20machine%20learning.ipynb) | Compare class weighting, undersampling, oversampling, SMOTE, and ensemble-style undersampling for churn data. |
| 14 | [CIFAR-10 image classification with a CNN](14%20Image%20classification%20using%20CNN%20%28CIFAR10%20dataset%29/Image%20classification%20using%20CNN%20%28CIFAR10%20dataset%29.ipynb) | Compare a dense baseline with a convolutional network and inspect multiclass predictions. A Python script version is included in the folder. |
| 15 | [Data augmentation to address overfitting](15%20Data%20augmentation%20to%20address%20overfitting/Data%20augmentation%20to%20address%20overfitting.ipynb) | Explore image augmentation as a way to improve image-model generalization. |
| 16 | [Data augmentation (additional notebook)](16%20Data%20augmentation%20to%20address%20overfitting/Data%20augmentation%20to%20address%20overfitting.ipynb) | A second notebook on the same topic, kept in its own numbered folder. |
| 17 | [Transfer learning](17%20Transfer%20Learning/Transfer%20Learning.ipynb) | Apply a pretrained image model to an image classification example. |
| 18 | [Word embeddings with the Keras Embedding layer](18%20Word%20embedding%20using%20keras%20embedding%20layer/Word%20embedding%20using%20keras%20embedding%20layer.ipynb) | Represent text as trainable dense vectors and use embeddings in a Keras workflow. |
| 19 | [Implement Word2Vec with Gensim](19%20Implement%20word2vec%20in%20gensim/Implement%20word2vec%20in%20gensim.ipynb) | Prepare review text, train Word2Vec, and explore similar words and vector similarity. |
| 20 | [Word2Vec, part 2](20%20Word2Vec%20Part%202/Word2Vec%20Part%202.ipynb) | Continue Word2Vec training and similarity exploration with the review dataset. |
| 21 | [TensorFlow input pipeline with `tf.data.Dataset`](21%20Tensorflow%20Input%20Pipeline%20tf%20Dataset/Tensorflow%20Input%20Pipeline%20tf%20Dataset.ipynb) | Create datasets and apply filter, map, shuffle, and batch transformations. |
| 22 | [Optimize TensorFlow pipelines with prefetch and cache](22%20Optimize%20Tensorflow%20Pipeline%20Performance%20prefetch%20%26%20cache/Optimize%20Tensorflow%20Pipeline%20Performance%20prefetch%20%26%20cache.ipynb) | Use benchmarks to explore prefetching and caching for pipeline performance. |

## Algorithms and Techniques

The badges above highlight algorithms and concepts demonstrated in the notebooks:

| Area | Algorithms and techniques |
|---|---|
| Activations | Sigmoid, tanh, ReLU, and leaky ReLU |
| Optimization | Gradient descent, batch gradient descent, stochastic gradient descent, and mini-batch gradient descent |
| Losses | Mean absolute error (MAE) and binary cross-entropy (log loss) |
| Evaluation | Confusion matrix, accuracy, precision, recall, and F1 score |
| Model training | Dense artificial neural networks (ANNs), convolutional neural networks (CNNs), and transfer learning |
| Generalization and imbalance | Dropout, data augmentation, class weighting, undersampling, oversampling, SMOTE, and ensemble-style undersampling |
| NLP | Keras word embeddings and Word2Vec with Gensim |
| Input performance | `tf.data` transformations, caching, and prefetching |

## Repository Structure

```text
Learn-Deep_Learning/
├── 1 Neural Network For Handwritten Digits Classification/
├── 2 Activation Functions/
├── 3 Matrix Basics/
├── ...
├── 22 Optimize Tensorflow Pipeline Performance prefetch & cache/
├── LICENSE
└── README.md
```

Each numbered folder groups a lesson with any data or supporting files it needs. Open the notebook from its own folder so relative dataset paths resolve as expected. The examples may download datasets such as MNIST and CIFAR-10 through TensorFlow/Keras on first use.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Md-Emon-Hasan/Learn-Deep_Learning.git
cd Learn-Deep_Learning
```

### 2. Create an environment (recommended)

```bash
python -m venv .venv
```

Activate it on macOS/Linux:

```bash
source .venv/bin/activate
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install the notebook and common libraries

```bash
python -m pip install --upgrade pip
python -m pip install jupyter numpy pandas matplotlib seaborn scikit-learn tensorflow gensim imbalanced-learn
```

TensorFlow's supported Python versions vary by release and operating system. If installation fails, use a Python version supported by the TensorFlow release available for your platform, then install the remaining packages in the same environment.

### 4. Open a lesson

```bash
jupyter notebook
```

Choose a numbered folder and open its `.ipynb` file. Run cells from top to bottom. Some notebooks depend on CSV, JSON, image, or model files stored beside the notebook; keep those files in place. MNIST and CIFAR-10 may be downloaded automatically on first run.

## Data and Reproducibility Notes

- Several notebooks use data files included in their lesson folders; inspect the folder before moving a notebook or running it from a different working directory.
- The MNIST and CIFAR-10 examples use TensorFlow/Keras datasets and may need an internet connection for the first download.
- The Word2Vec notebooks use Amazon product-review data and include model/data artifacts. Git LFS is configured for JSON files in this repository; install Git LFS and run `git lfs pull` if a data file is a pointer instead of usable JSON after cloning.
- The notebooks are educational examples. Package APIs, random seeds, and training results can differ between library versions and runs. Set seeds and record package versions when you need repeatable experiments.
- Folder 8 currently has its CSV dataset but no lesson notebook in the repository.

## Contributing

Contributions that improve explanations, fix notebook issues, or add a well-scoped lesson are welcome.

1. Fork the repository and create a branch.
2. Keep new lessons in a numbered, clearly named folder where practical.
3. Include brief Markdown explanations, required data instructions, and any dependencies specific to the lesson.
4. Avoid committing credentials, private data, generated caches, or unnecessarily large artifacts.
5. Open a pull request describing the change and how to follow the lesson.

## License

This project is distributed under the Apache License 2.0. See [LICENSE](LICENSE) for the full text.

## Connect With Me

- 🌐 **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- 💻 **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- 💼 **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- 🤗 **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- 📧 **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- 📱 **WhatsApp:** [+8801834363533](https://wa.me/8801834363533)

---

If you find the tutorials useful, consider starring the repository. For questions, feedback, or collaboration, use any of the contact links above.
