# Python Tutorial for Beginners: Biology & Data Science

A comprehensive, hands-on Python tutorial designed for beginners in biology, bioinformatics, and data science. This repository contains interactive Jupyter notebooks that guide you through Python fundamentals, data visualization, and statistical analysis with real-world biological examples.

## 📚 Overview

This tutorial is designed to help you:
- Learn Python programming from scratch
- Understand data manipulation with pandas
- Create effective visualizations with matplotlib and seaborn
- Perform statistical tests on biological data
- Apply Python skills to real clinical and biological datasets

## 🎯 Target Audience

- Biology students with no programming experience
- Researchers transitioning to computational biology
- Anyone interested in data analysis for life sciences

## 📖 Notebooks Guide

### 1. **`slides-nosolution-claude.ipynb`** - Introduction to Python
**What you'll learn:**
- What is programming and why Python?
- Python's history and philosophy
- Core concepts: variables, data types, functions, and classes
- Python package management (pip, conda)
- The Python ecosystem and community

**When to use:** Start here if you're completely new to Python or want to understand the fundamentals and philosophy behind the language.

---

### 2. **`visualization-tutorial.ipynb`** - Data Visualization
**What you'll learn:**
- Creating dataframes with pandas
- Generating synthetic clinical data
- Multi-panel boxplots with custom styling
- Line plots with error bands
- Color gradients for time-series data
- Double x-axis labeling for complex categorical data

**When to use:** After understanding Python basics, use this notebook to learn how to visualize biological and clinical data effectively.

**Key features:**
- Simulates immune system subpopulation data
- Treatment arms comparison (Placebo, Low Dose, High Dose)
- Responder vs. Non-Responder analysis
- Time-point progression visualization

---

### 3. **`statistical-tests-example.ipynb`** - Statistical Analysis
**What you'll learn:**
- Performing t-tests (independent, paired, one-sample)
- ANOVA for multi-group comparisons
- Non-parametric tests (Mann-Whitney, Wilcoxon)
- Visualizing statistical significance with annotations
- Using scipy.stats for hypothesis testing
- Effect size calculations

**When to use:** Once comfortable with data visualization, use this notebook to learn how to perform rigorous statistical analysis on your data.

**Covered tests:**
- Independent samples t-test
- Paired samples t-test
- One-sample t-test
- Mann-Whitney U test
- Wilcoxon signed-rank test
- ANOVA (Analysis of Variance)
- Correlation analysis (Pearson, Spearman)

---

## 🛠️ Prerequisites & Installation

### Required Software

This tutorial requires two main software packages:

#### 1. **Anaconda** (Python Distribution)

Anaconda provides Python along with essential data science packages and tools.

**Installation:**

**Windows:**
1. Download Anaconda from [https://www.anaconda.com/download](https://www.anaconda.com/download)
2. Run the installer (`.exe` file)
3. Follow the installation wizard
4. Check "Add Anaconda to PATH" (recommended for this tutorial)
5. Complete installation

**macOS:**
1. Download Anaconda from [https://www.anaconda.com/download](https://www.anaconda.com/download)
2. Open the downloaded `.pkg` file
3. Follow the installation wizard
4. Open Terminal and verify installation:
   ```bash
   conda --version
   ```

**Linux:**
1. Download Anaconda from [https://www.anaconda.com/download](https://www.anaconda.com/download)
2. Open Terminal and navigate to download directory
3. Run:
   ```bash
   bash Anaconda3-*-Linux-x86_64.sh
   ```
4. Follow prompts, accept license, and allow initialization
5. Restart terminal and verify:
   ```bash
   conda --version
   ```

#### 2. **Visual Studio Code** (Code Editor)

VS Code is a lightweight but powerful code editor with excellent Jupyter notebook support.

**Installation:**

**Windows:**
1. Download VS Code from [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Run the installer (`.exe` file)
3. Follow installation wizard
4. Launch VS Code

**macOS:**
1. Download VS Code from [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Open the downloaded `.zip` file
3. Drag `Visual Studio Code.app` to Applications folder
4. Launch from Applications

**Linux:**
1. Download `.deb` or `.rpm` from [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. For Ubuntu/Debian:
   ```bash
   sudo dpkg -i code_*.deb
   sudo apt-get install -f
   ```
3. For Fedora/RHEL:
   ```bash
   sudo rpm -i code-*.rpm
   ```

**Configure VS Code for Jupyter:**
1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
3. Search for "Python" and install the official Microsoft extension
4. Search for "Jupyter" and install the official Microsoft extension

---

## 📦 Required Python Packages

The following packages are used throughout the tutorial:

```bash
# Core packages
pandas
numpy
matplotlib
seaborn
scipy

# Statistical visualization
statannotations

# Excel file support
openpyxl
```

### Installing Packages

After installing Anaconda, open Terminal (macOS/Linux) or Anaconda Prompt (Windows) and run:

```bash
# Install all required packages
conda install pandas numpy matplotlib seaborn scipy openpyxl -y

# Install statannotations via pip
pip install statannotations
```

---

## 🚀 Getting Started

### Step 1: Clone or Download Repository

**Option A: Clone with Git**
```bash
git clone https://github.com/LeonardoAlchieri/python-tutorial-for-beginners-biology.git
cd python-tutorial-for-beginners-biology
```

**Option B: Download ZIP**
1. Click the green "Code" button at the top of this page
2. Select "Download ZIP"
3. Extract the ZIP file to your preferred location

### Step 2: Open in VS Code

1. Launch Visual Studio Code
2. Click "File" → "Open Folder"
3. Navigate to the repository folder and select it
4. VS Code will open the folder with all notebooks visible

### Step 3: Start Learning!

1. Open `slides-nosolution-claude.ipynb` to begin
2. Click the "Select Kernel" button in the top-right
3. Choose your Python environment (usually "base" from Anaconda)
4. Follow the notebooks in order (slides → visualization → statistics)
5. Run cells by clicking the play button or pressing Shift+Enter

---

## 📊 Example Dataset

The tutorial uses a synthetic clinical dataset (`data/clinical-example-1.xlsx`) that simulates:
- **100 subjects** across 3 treatment arms (Placebo, Low Dose, High Dose)
- **5 timepoints** (T0 through T5)
- **15 immune system subpopulations** (Leukocytes, Neutrophils, Eosinophils, etc.)
- **Response classification** (Responder vs. Non-Responder)

This dataset is designed to mimic real-world clinical trial data while being safe for educational use.

---

## 🎓 Learning Path

### For Complete Beginners:
1. Start with `slides-nosolution-claude.ipynb` - Understand Python fundamentals
2. Practice the concepts in the Python REPL or simple scripts
3. Move to `visualization-tutorial.ipynb` - Learn to work with data
4. Complete `statistical-tests-example.ipynb` - Analyze your data scientifically

### For Those with Some Python Experience:
1. Skim `slides-nosolution-claude.ipynb` as a refresher
2. Focus on `visualization-tutorial.ipynb` for pandas and plotting techniques
3. Deep dive into `statistical-tests-example.ipynb` for statistical methods

---

## 🤝 Contributing

Found a bug? Have a suggestion? Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

---

## 📧 Contact

**Leonardo Alchieri**  
Università della Svizzera Italiana

For questions or feedback about this tutorial, please open an issue on GitHub.

---

## 📄 License

This educational material is provided as-is for learning purposes. Feel free to use and adapt for educational contexts.

---

## 🙏 Acknowledgments

This tutorial was developed for teaching Python programming and data analysis to biology students at Istituto Nazionale dei Tumori, Milano.

Special thanks to the Python, pandas, matplotlib, seaborn, and scipy communities for creating the amazing tools that make scientific computing accessible to everyone.

---

## 📚 Additional Resources

- [Python Official Documentation](https://docs.python.org/3/)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/index.html)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [SciPy Stats Reference](https://docs.scipy.org/doc/scipy/reference/stats.html)
- [Real Python Tutorials](https://realpython.com/)

---

**Happy Learning! 🐍📊🧬**
