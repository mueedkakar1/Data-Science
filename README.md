# Data-Science
Data science is an interdisciplinary academic field that uses statistics, scientific computing, scientific methods, processes, algorithms and systems to extract or extrapolate knowledge and insights from noisy, structured, and unstructured data.

Data science also integrates domain knowledge from the underlying application domain (e.g., natural sciences, information technology, and medicine). Data science is multifaceted and can be described as a science, a research paradigm, a research method, a discipline, a workflow, and a profession.

Data science is a "concept to unify statistics, data analysis, informatics, and their related methods" in order to "understand and analyse actual phenomena" with data. It uses techniques and theories drawn from many fields within the context of mathematics, statistics, computer science, information science, and domain knowledge. However, data science is different from computer science and information science. Turing Award winner Jim Gray imagined data science as a "fourth paradigm" of science (empirical, theoretical, computational, and now data-driven) and asserted that "everything about science is changing because of the impact of information technology" and the data deluge.

# Data Science Process:
1. Data collention.
2. Data cleaning and processing.
3. Statistical analysis and modeling.
4. Machine learning and predictive modeling.
5. Data visualization and communication.
6. Developing data-driven solutions to real-world problems. The process is iterative and involves going back and forth between different steps as necessary

# Introduction to Python (Week 2)
In week 2 we studied few basic python commands and learned the use 
1. Functions
2. Types and sequences
3. Strings
4. Reading and writing CVS files
5. Using data and times
6. Objects and Map()
7. Lambda and list comprehensions

# Introduction to Numpy
Numpy is a powerful library in Python used for numerical computations. It stands for "Numerical Python" and provides support for large, multi-dimensional arrays and matrices, along with a wide range of mathematical functions to operate on these arrays efficiently.
Hello! Numpy is a powerful library in Python used for numerical computations. It stands for "Numerical Python" and provides support for large, multi-dimensional arrays and matrices, along with a wide range of mathematical functions to operate on these arrays efficiently.

Here are some of the key features and functionalities provided by Numpy:

1. **Arrays:** Numpy's primary data structure is the `ndarray`, which stands for "n-dimensional array." These arrays can be used to store elements of the same data type in multiple dimensions, making it suitable for tasks involving large datasets and numerical computations.
2. **Array Creation:** Numpy provides several methods to create arrays easily, such as `numpy.array()`, `numpy.zeros()`, `numpy.ones()`, `numpy.arange()`, `numpy.linspace()`, etc.
3. **Array Operations:** You can perform various mathematical and element-wise operations on Numpy arrays. For example, addition, subtraction, multiplication, division, exponentiation, etc. These operations are efficiently vectorized, making Numpy code fast and concise.
4. **Indexing and Slicing:** Numpy allows you to access elements of arrays using indexing and slicing operations, similar to Python lists.
5. **Broadcasting:** Broadcasting is a powerful feature of Numpy that allows you to perform operations on arrays with different shapes, automatically handling shape compatibility under certain conditions.
6. **Mathematical Functions:** Numpy provides a wide range of mathematical functions like trigonometric, logarithmic, statistical, linear algebra, and more.

# Data Types and Sources (Week 3)
In Python, data types define the type of data that can be stored in variables or objects. Python is dynamically typed, which means the data type is determined at runtime based on the value assigned to a variable. Here are some of the commonly used data types in Python:

1. **Numeric Types:**
   - `int`: Integer type (e.g., 5, -12, 0).
   - `float`: Floating-point type (e.g., 3.14, -2.7, 0.0).
   - `complex`: Complex numbers with a real and imaginary part (e.g., 3 + 2j).
2. **Text Type:**
   - `str`: String type (e.g., "hello", 'world', "123").
3. **Sequence Types:**
   - `list`: Ordered and mutable collection of elements (e.g., [1, 2, 3]).
   - `tuple`: Ordered and immutable collection of elements (e.g., (1, 2, 3)).
   - `range`: Represents a range of numbers (e.g., range(0, 10)).
4. **Mapping Type:**
   - `dict`: Collection of key-value pairs (e.g., {"name": "John", "age": 30}).
5. **Set Types:**
   - `set`: Unordered collection of unique elements (e.g., {1, 2, 3}).
   - `frozenset`: Immutable set (e.g., frozenset({1, 2, 3})).
6. **Boolean Type:**
   - `bool`: Represents a boolean value (`True` or `False`).
7. **None Type:**
   - `None`: Represents the absence of a value or a null value.

Python also supports more specialized data types through various modules and libraries, such as Numpy arrays for numerical computations, Pandas DataFrames for data manipulation, and more.
As for data sources in Python, it depends on what you want to do with the data. Python can read data from a variety of sources, such as:
1. **Files:** Python can read and write data to/from text files, CSV files, JSON files, Excel spreadsheets, and more. Python's built-in `open()` function is commonly used to work with files.
2. **Databases:** Python has libraries to interact with various databases like MySQL, PostgreSQL, SQLite, MongoDB, etc. For example, you can use libraries like `sqlite3`, `pymysql`, or `pymongo` to work with different databases.
3. **Web APIs:** Python can interact with web APIs to fetch data from various online sources. The `requests` library is commonly used for making HTTP requests.
4. **Web Scraping:** Python can also scrape data from websites using libraries like `BeautifulSoup` or `Scrapy`.
5. **Streaming Data:** For real-time data processing, Python can connect to streaming platforms like Kafka, RabbitMQ, etc.
6. **Sensor Data:** For IoT applications, Python can interface with sensors using libraries like `gpiozero` or `pyserial`.

These are just a few examples of data sources in Python. The language's versatility and the extensive collection of third-party libraries make it a popular choice for various data-related tasks.

# Data Cleaning and Preprocessing (Week 4)
Data cleaning and preprocessing are essential steps in the data analysis and machine learning workflow. These processes involve identifying and handling missing or incorrect data, transforming data into a suitable format, and preparing it for analysis or modeling. Python offers various libraries and tools to perform data cleaning and preprocessing tasks effectively. Here's a step-by-step guide on how to approach data cleaning and preprocessing using Python:

1. **Importing Libraries:**
   Start by importing the necessary libraries. Commonly used libraries for data cleaning and preprocessing include Pandas, NumPy, and Scikit-learn.
2. **Loading the Data:**
   Load your dataset into a Pandas DataFrame. The data may come from CSV files, Excel spreadsheets, SQL databases, or other sources.
3. **Handling Missing Data:**
   Check for missing data in the dataset and handle it appropriately. Missing data can be imputed (filled in) or removed, depending on the situation.
4. **Data Transformation:**
   Transform the data to the required format. This step may include changing data types, encoding categorical variables, scaling numerical features, and feature engineering.
5. **Handling Outliers:**
   Detect and handle outliers in the data. Outliers can be treated by either removing them or applying transformations.
6. **Feature Scaling and Normalization:**
   Depending on the machine learning algorithms you plan to use, feature scaling or normalization might be necessary to bring all features to a similar scale.
7. **Feature Selection:**
   If your dataset has many features, consider selecting the most relevant ones to improve model performance and reduce overfitting.
8. **Splitting the Data:**
   Split the dataset into training and testing sets to evaluate your model's performance accurately.
   
After data cleaning and preprocessing, you can proceed with model training and evaluation using machine learning algorithms. The choice of algorithms will depend on the type of problem you are trying to solve (classification, regression, clustering, etc.).

Remember that data cleaning and preprocessing can significantly impact the performance of your models, so it's crucial to spend time understanding the data and choosing appropriate methods to handle different data issues.

# Exploratory Data Analysis (Week 5)
In data science and statistics, the terms univariate, bivariate, and multivariate refer to the number of variables or features being analyzed in a dataset. These terms help categorize the type of analysis or visualizations used to study the relationships between variables. Let's explore each of these concepts:

1. **Univariate Analysis:**
   Univariate analysis focuses on a single variable at a time. It involves examining the distribution, central tendency, and dispersion of a single variable to understand its characteristics. Common methods of univariate analysis include histograms, box plots, bar charts, and summary statistics.

   Examples of univariate analysis:
   - Examining the distribution of exam scores for a single subject.
   - Analyzing the distribution of ages in a population.
   - Studying the frequency of occurrence of a specific word in a text document.

2. **Bivariate Analysis:**
   Bivariate analysis involves analyzing the relationship between two variables simultaneously. It helps understand how two variables are related to each other and how changes in one variable affect the other. Common methods of bivariate analysis include scatter plots, correlation analysis, and contingency tables.

   Examples of bivariate analysis:
   - Studying the correlation between temperature and ice cream sales.
   - Analyzing the relationship between study hours and exam scores.
   - Investigating the association between gender and job satisfaction.

3. **Multivariate Analysis:**
   Multivariate analysis deals with the simultaneous analysis of three or more variables. It examines the relationships among multiple variables to uncover more complex patterns and dependencies. Multivariate analysis is particularly useful in understanding how multiple variables interact to influence outcomes. Techniques used in multivariate analysis include principal component analysis (PCA), factor analysis, and cluster analysis.

   Examples of multivariate analysis:
   - Understanding the factors that influence customer satisfaction, considering factors like product quality, price, and customer service.
   - Analyzing the impact of marketing campaigns on sales, considering factors like advertising spend, time of the campaign, and target audience.

The choice of univariate, bivariate, or multivariate analysis depends on the research questions or insights sought from the data. Exploratory Data Analysis (EDA) often begins with univariate analysis to understand each variable's distribution and characteristics. Bivariate and multivariate analyses are then used to explore relationships and dependencies between variables, which can lead to more advanced modeling and insights in data science.
