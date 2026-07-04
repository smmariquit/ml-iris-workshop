# Python Data Science Tutorial Collection

A full collection of Python tutorials covering essential data science libraries: **Pandas**, **Scikit-Learn**, and **Scikit-Image**. This repository contains hands-on examples and exercises perfect for learning data manipulation, machine learning, and image processing.

## 📁 Project Structure

```
QCU/
├── README.md                    # This file
├── polyA_helix_CA.pdb          # Protein structure file
├── iris/                       # Dataset folder
│   ├── database.sqlite         # SQLite database
│   └── Iris.csv               # Famous Iris flower dataset
├── pandas/                     # Pandas tutorials
│   ├── pandas01.py            # Introduction to data structures
│   ├── pandas02.py            # Data manipulation basics
│   ├── pandas03.py            # Advanced data operations
│   ├── pandas04.py            # Data analysis techniques
│   ├── pandas05.py            # Data visualization
│   └── pandas06.py            # Real-world data processing
├── sklearn/                    # Scikit-Learn tutorials
│   └── sklearn_tutorial.py    # Complete ML tutorial with Iris dataset
└── skimage/                    # Scikit-Image tutorials
    └── skimage_tutorial.py     # Complete image processing tutorial
```

## 🐼 Pandas Tutorials

The `pandas/` folder contains a progressive series of tutorials covering:

- **pandas01.py**: Introduction to Pandas data structures (Series, DataFrame)
- **pandas02.py**: Data manipulation and basic operations
- **pandas03.py**: Advanced data operations and transformations
- **pandas04.py**: Data analysis and statistical operations
- **pandas05.py**: Data visualization with matplotlib integration
- **pandas06.py**: Real-world data processing examples

### Getting Started with Pandas
```bash
cd pandas
python pandas01.py
```

## 🤖 Scikit-Learn Tutorial

The `sklearn/` folder contains a full machine learning tutorial:

- **sklearn_tutorial.py**: Complete ML workflow using the Iris dataset
 - Data loading and exploration
 - Data preprocessing and feature scaling
 - Multiple ML algorithms (Logistic Regression, Decision Trees, Random Forest, SVM)
 - Model evaluation and comparison
 - Visualizations and insights

### Running the ML Tutorial
```bash
cd sklearn
python sklearn_tutorial.py
```

**Note**: The tutorial automatically loads the Iris dataset from the `../iris/` directory. If the CSV file is not found, it falls back to scikit-learn's built-in dataset.

## 🖼️ Scikit-Image Tutorial

The `skimage/` folder contains a full image processing tutorial:

- **skimage_tutorial.py**: Complete guide to image processing
 - Loading and displaying images
 - Basic image operations
 - Filtering and enhancement
 - Edge detection and feature extraction
 - Morphological operations
 - Image segmentation
 - Real-world applications

### Running the Image Processing Tutorial
```bash
cd skimage
python skimage_tutorial.py
```

## 📊 Dataset Information

### Iris Dataset (`iris/`)
- **Iris.csv**: The famous iris flower dataset
- **database.sqlite**: SQLite version of the dataset
- Contains 150 samples of iris flowers with 4 features each
- Perfect for classification tasks and ML learning

## 🚀 Prerequisites

Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scikit-image
```

## 📝 Usage Instructions

1. **Start with Pandas**: Begin with the pandas tutorials to understand data manipulation
2. **Progress to ML**: Move to the sklearn tutorial to learn machine learning
3. **Explore Image Processing**: Use the skimage tutorial for computer vision tasks

Each tutorial is self-contained and includes:
- ✅ Detailed explanations and comments
- ✅ Code examples with output
- ✅ Visualizations and plots
- ✅ Progressive difficulty levels
- ✅ Real-world applications

## 🎯 Learning Path

### Beginner
- Start with `pandas01.py` for basic data structures
- Practice with `pandas02.py` for data manipulation
- Explore `sklearn_tutorial.py` for your first ML project

### Intermediate
- Work through all pandas tutorials (`pandas01.py` - `pandas06.py`)
- Complete the sklearn tutorial with different datasets
- Begin with basic image processing in `skimage_tutorial.py`

### Advanced
- Combine techniques from all three libraries
- Modify tutorials for your own datasets
- Experiment with advanced algorithms and techniques

## 🔧 Troubleshooting

- **Import Errors**: Make sure all required libraries are installed
- **File Not Found**: Ensure you're running scripts from the correct directory
- **Dataset Issues**: The sklearn tutorial will automatically fallback to built-in datasets if files are missing

## 📚 Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)
- [Scikit-Image Documentation](https://scikit-image.org/)

---

**Happy Learning!** 🎉

*This tutorial collection was organized and documented by GitHub Copilot on September 25, 2025.*