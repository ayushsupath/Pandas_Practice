<div align="center">

# 🐼 Pandas Practice & Exercises

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=150458&center=true&vCenter=true&width=500&lines=Master+Pandas+Data+Manipulation;Daily+Practice+%26+Exercises;Data+Analysis+%26+Transformation" alt="Typing SVG" />

**A comprehensive repository for learning and mastering Pandas** - the most powerful data manipulation and analysis library in Python! 📊

</div>

---

## 🎯 About This Repository

This repository contains **daily practice sessions and comprehensive exercises** focused on mastering **Pandas** for:
- ✅ Data Loading & Inspection
- ✅ Data Cleaning & Preprocessing  
- ✅ Data Manipulation & Transformation
- ✅ Data Aggregation & Grouping
- ✅ Merging & Joining Datasets
- ✅ Time Series Analysis
- ✅ Data Visualization with Pandas

Perfect for beginners to intermediate learners who want to build strong Pandas skills!

---

## 📚 Topics & Notebooks

### 📖 **Core Pandas Concepts**

| Notebook | Description | Topics Covered |
|----------|-------------|-----------------|
| **panda1.ipynb** | Pandas Fundamentals | Series, DataFrames, Basic Operations |
| **dataFrams.ipynb** | DataFrame Mastery | Creating, Indexing, Slicing, Attributes |
| **missingdata.ipynb** | Handling Missing Data | Detecting, Filling, Dropping NULL values |

---

### 🔍 **Key Learning Topics**

#### 1️⃣ **Series & DataFrames**
- Creating Series and DataFrames
- Data types and dtypes
- Indexing and slicing
- Accessing data efficiently

#### 2️⃣ **Data Inspection**
- `head()`, `tail()`, `info()`
- `describe()` for statistical summary
- Data shape and structure
- Data types checking

#### 3️⃣ **Data Cleaning & Preprocessing**
- Handling missing values (NaN, NULL)
- Filling missing data strategically
- Dropping incomplete rows/columns
- Data type conversions
- Handling duplicates

#### 4️⃣ **Data Manipulation**
- Filtering and selection
- Boolean indexing
- `.loc[]` and `.iloc[]` operations
- Column operations
- String operations on data

#### 5️⃣ **Data Aggregation**
- `groupby()` operations
- Aggregation functions (sum, mean, count, etc.)
- Multi-level grouping
- Custom aggregations

#### 6️⃣ **Data Merging & Joining**
- `merge()` - SQL-like joins
- `concat()` - Combining DataFrames
- `join()` - Index-based joining
- Different join types (inner, outer, left, right)

#### 7️⃣ **Time Series Analysis**
- Date/time parsing and conversion
- Time-based indexing
- Resampling
- Rolling windows

#### 8️⃣ **Data Visualization**
- Plotting with Pandas
- Integration with Matplotlib & Seaborn
- Creating insights from data

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.7 or higher** 🐍
- **pip** or **conda** package manager

### Installation

Install required packages:

```bash
# Using pip
pip install pandas numpy matplotlib seaborn jupyter

# Using conda
conda install pandas numpy matplotlib seaborn jupyter
```

### Quick Start

1. **Clone the repository:**
```bash
git clone https://github.com/ayushsupath/Pandas_Practice.git
cd Pandas_Practice
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
# or install manually
pip install pandas numpy matplotlib seaborn
```

3. **Open Jupyter Notebook:**
```bash
jupyter notebook
```

4. **Start exploring!** 🚀
Open any `.ipynb` file to start learning:
- `panda1.ipynb` - Start here for basics
- `dataFrams.ipynb` - Learn DataFrame operations
- `missingdata.ipynb` - Master data cleaning

---

## 📁 Repository Structure

```
Pandas_Practice/
│
├── 📄 README.md                    # This file
├── 📊 panda1.ipynb                 # Pandas basics & fundamentals
├── 📊 dataFrams.ipynb              # DataFrame operations & manipulation
├── 📊 missingdata.ipynb            # Missing data handling & cleaning
│
├── 📁 anaconda_projects/           # Anaconda project files
└── 📁 .ipynb_checkpoints/          # Jupyter checkpoints (auto-generated)
```

---

## 💡 What You'll Learn

### Basic Level ✅
- [ ] Create Series and DataFrames
- [ ] Load data from CSV/Excel
- [ ] Basic indexing and slicing
- [ ] Data inspection methods
- [ ] Handling missing values

### Intermediate Level 📈
- [ ] Advanced filtering with boolean indexing
- [ ] GroupBy and aggregation
- [ ] Data merging and joining
- [ ] Data transformation techniques
- [ ] Working with time series

### Advanced Level 🚀
- [ ] Custom functions with `apply()`
- [ ] Performance optimization
- [ ] Working with large datasets
- [ ] Complex data reshaping
- [ ] Advanced time series operations

---

## 🎓 Learning Path

Follow this sequence to master Pandas step by step:

```
Start Here → panda1.ipynb (Fundamentals)
    ↓
Next → dataFrams.ipynb (DataFrame Mastery)
    ↓
Then → missingdata.ipynb (Data Cleaning)
    ↓
Practice → Create your own mini-projects
    ↓
Master! 🎉
```

---

## 📊 Code Examples

### Loading & Inspecting Data
```python
import pandas as pd

# Load data
df = pd.read_csv('data.csv')

# Inspect data
print(df.head())          # First 5 rows
print(df.info())          # Data types and info
print(df.describe())      # Statistical summary
print(df.shape)           # Dimensions (rows, columns)
```

### Handling Missing Data
```python
# Check for missing values
print(df.isnull().sum())

# Fill missing values
df.fillna(0)              # Fill with 0
df.fillna(method='ffill') # Forward fill

# Drop missing values
df.dropna()               # Remove rows with NaN
```

### GroupBy & Aggregation
```python
# Group and aggregate
df.groupby('category').sum()
df.groupby('date').mean()
df.groupby(['year', 'month']).size()
```

### Merging DataFrames
```python
# Merge two DataFrames
merged = pd.merge(df1, df2, on='key', how='inner')

# Concatenate
combined = pd.concat([df1, df2], axis=0)
```

---

## 📚 Resources & References

### Official Documentation
- 📖 [Pandas Official Documentation](https://pandas.pydata.org/)
- 📋 [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- 📚 [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/)

### External Resources
- 🎥 YouTube: Pandas tutorials and walkthroughs
- 📖 Books: "Python for Data Analysis" by Wes McKinney
- 🌐 Kaggle: Real-world datasets for practice

### Useful Links
- [10 Minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
- [Essential Basic Functionality](https://pandas.pydata.org/docs/user_guide/basics.html)
- [Indexing and Selecting Data](https://pandas.pydata.org/docs/user_guide/indexing.html)

---

## 🎯 Practice Exercises

### Beginner Exercises
- [ ] Load a CSV file and explore its structure
- [ ] Calculate mean, median, and standard deviation
- [ ] Filter data based on conditions
- [ ] Handle and remove missing values
- [ ] Create new columns from existing data

### Intermediate Exercises
- [ ] Group data and perform aggregations
- [ ] Merge multiple datasets
- [ ] Pivot tables and reshaping
- [ ] Time series operations
- [ ] Data normalization and scaling

### Advanced Exercises
- [ ] Build data pipelines
- [ ] Performance optimization with large datasets
- [ ] Complex data transformations
- [ ] Statistical analysis
- [ ] Creating custom analysis functions

---

## 💼 Use Cases

Real-world applications of Pandas:

✅ **Financial Analysis** - Stock prices, portfolios, trading  
✅ **Business Intelligence** - Sales, customer data, KPIs  
✅ **Data Science** - Feature engineering, data preprocessing  
✅ **Research** - Statistical analysis, data exploration  
✅ **Machine Learning** - Data preparation and transformation  
✅ **Web Analytics** - Traffic analysis, user behavior  

---

## 🤝 Contributing

Have improvements or new exercises to add? **Contributions are welcome!** 🎉

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-exercise`)
3. Commit your changes (`git commit -m 'Add amazing new exercise'`)
4. Push to the branch (`git push origin feature/amazing-exercise`)
5. Open a Pull Request

---

## 📝 Tips for Success

1. **Practice Daily** - Consistent practice builds muscle memory 💪
2. **Experiment** - Try different methods and compare results 🔬
3. **Read Errors** - Error messages guide you to solutions 🎯
4. **Write Notes** - Document what you learn 📝
5. **Build Projects** - Apply learning to real datasets 🚀
6. **Refer Documentation** - Official docs are your best friend 📚

---

## 🔗 Quick Links

- 👤 [GitHub Profile](https://github.com/ayushsupath)
- 💼 [LinkedIn](https://www.linkedin.com/in/ayushsupath/)
- 🌐 [Portfolio](https://portfolio-rust-eta-76.vercel.app/)
- 📧 [Email](mailto:ayushsupath1829@gmail.com)

---

## 📄 License

This project is open source and available under the **MIT License**.

Feel free to use this repository for learning, teaching, and personal projects!

---

## ⭐ Support

If you found this repository helpful:

- ⭐ **Star this repository** to show your support
- 🔄 **Share** with friends and colleagues who are learning Pandas
- 💬 **Provide feedback** in the issues section
- 🤝 **Contribute** your own exercises and examples

---

<div align="center">

## 🎓 Happy Learning!

**"Data is the new oil, and Pandas is your refinery!" 🔧**

Master Pandas and unlock powerful data manipulation skills! 🚀

---

**Made with ❤️ by Ayush Supath**

*Last Updated: June 2025*

</div>