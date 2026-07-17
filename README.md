# Seaborn-Notes

# 📊 Seaborn

A beginner-friendly repository to learn **Seaborn**, one of the most popular Python libraries for creating beautiful and informative data visualizations. This repository includes examples of different plots, customization techniques, and real-world visualization projects.

## 🚀 Features

- Beginner to Advanced Seaborn concepts
- Easy-to-understand examples
- Built-in datasets
- Statistical visualizations
- Plot customization
- Real-world projects

## 📚 Topics Covered

- Introduction to Seaborn
- Installation
- Built-in Datasets
- Themes and Styles
- Color Palettes
- Line Plot
- Scatter Plot
- Bar Plot
- Count Plot
- Histogram
- KDE Plot
- Box Plot
- Violin Plot
- Strip Plot
- Swarm Plot
- Heatmap
- Pair Plot
- Joint Plot
- Regression Plot
- Cat Plot
- Facet Grid
- Saving Figures

## 💻 Installation

Install Seaborn using pip:

```bash
pip install seaborn
```

## 📥 Import Seaborn

```python
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd
```

## 📊 Example

```python
import seaborn as sns
import matplotlib.pyplot as plt

tips = sns.load_dataset("tips")

sns.scatterplot(
    data=tips,
    x="total_bill",
    y="tip",
    hue="sex"
)

plt.show()
```

## 📂 Built-in Datasets

- tips
- iris
- titanic
- penguins
- diamonds
- flights
- mpg
- planets
- exercise
- taxis

## 🎯 Learning Goals

- Understand Seaborn basics
- Create different types of plots
- Customize visualizations
- Work with real datasets
- Build data visualization projects

## 🛠 Requirements

- Python 3.x
- Seaborn
- Pandas
- Matplotlib
- NumPy

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, improve the examples, and submit a pull request.

## ⭐ Support

If you found this repository helpful, please give it a ⭐ on GitHub.

## 📄 License

This project is licensed under the MIT License.

---

**Happy Learning! 🚀**
