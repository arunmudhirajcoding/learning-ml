# Tensor (Ndarray)
**Def**
A tensor is a mathematical object that generalizes scalars(0D), vectors(1D), and matrices(2D) to higher dimensions. It can be thought of as a multi-dimensional array of numerical values that can represent various types of data, such as images, audio, or text. 

## Terminology
- **Rank**: The number of dimensions/axis in a tensor. For example, a scalar has rank 0, a vector has rank 1, a matrix has rank 2, and so on.
- **Shape**: The size of each dimension in a tensor. For example, a 3x4 matrix has a shape of (3, 4).

## Vectors
- 1D Tensor is Vector.
- Example: [1, 2, 3] is a vector in 3D space, where each element represents a coordinate along a specific axis.
- 3D Tensors examples:  texts , timeseries data
- 4D Tensors examples: videos, 3D images


# Working with Anaconda / jupyter notebook
- install Anaconda from https://www.anaconda.com/products/distribution
- open Anaconda Navigator and launch Jupyter Notebook
- create a new notebook and start coding in Python
- it is recommended to create new env by using `conda create -n myenv python=3.8` and activate it by `conda activate myenv` before installing any libraries
- Or u can use Google Colab for free GPU access and easy sharing of notebooks
- install libraries using pip or conda, for example: `!pip install numpy pandas matplotlib scikit-learn tensorflow`

# Working with JSON, CSV, and SQL
- pd.read_csv() to read CSV files
- pd.read_json() to read JSON files
- Use mysql-connector-python library to connect to MySQL databases and execute SQL queries
- Example of connecting to MySQL database:
```python
import mysql.connector
conn = mysql.connector.connect(
    host='localhost',
    user='root',
    password='root',
    database='world'
    )
df = pd.read_sql_query("SELECT * FROM countrylanguage",conn)
print(df.head())
```

# Dummy Variable trap
- It is a situation where the independent variables are highly correlated with each other, which can lead to multicollinearity and affect the performance of the model.
- To avoid dummy variable trap, we can drop one of the dummy variables from the dataset.