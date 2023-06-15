# Data and Data preprocessing

# What is Data, Attribute, Object?

### **Data / Data sets**

is a collection of data objects and their attributes

### Attribute

is a property or characteristic of data object

### **Attribute Values**

are numbers or symbols assigned to an attribute

### Note !

Object = Raw = Record = Entity = Instance

Attribute = Column = Feature = Characteristic 

## Types of Attributes

| Type | Qualitative or Quantitative  | Example |
| --- | --- | --- |
| Nominal | Categorical (Qualitative) | Name, States, Zip Code, Eye Color.. etc |
| Ordinal | Categorical (Qualitative) | Values Have Meaningful order (RANKING) Like :                             - size= {Small, Medium, Large}       -Grade = {Good , Bad , Perfect} |
| Interval | Numeric (Quantitative ) | - Measured on scale of equal-sized units                     - Values have order : Temperature, Length, time second |
| Ratio | Numeric (Quantitative ) | floating values like temperature on Kelvin, Time with minutes |
|  |  |  |

## Properties of Attribute Values

The type of attribute depends on which of the following properties it posses :

| Property | Accepted Symbols | Attribute type |
| --- | --- | --- |
| Distinctness |  =  ≠ | Nominal |
| Order | < > | Ordinal |
| Addition | + - | Interval |
| Multiplication | * / | Ratio |

## Types of Data sets

- **Record**
    - Relational Records
    - Data Matrix
    - Document Data
    - Transaction Data
- **Graph and Network**
    - WWW
    - Social Information networks
    - Molecular Structures
- **Spatial, image and multimedia**
    - Image Data
    - Video Data
    - Spatial Data :Like  **Maps**
    
- **Ordered**
    - Video Data : Sequence of images
    - Temporal Data : Time-series
    - Sequential Data : Transaction Sequences
    - Genetic sequence data
    

---

## Data Quality

When We have Data for machine training , we may  face some problems like 

- Noise and Outliers
- Missing Values
- Duplicate data

### Noise

this is Like invalid values that exists on data sets like : 

| NAME | JOB | SALARY |
| --- | --- | --- |
| Yousef | Data Analyst | - 800 |

### Outliers

Data objects with characterstics that are considerably different than most of the other data objects

### Missing Values

The data sets may have no value in one attribute the reasons may be the sensor did not collect this attribute value (Hardware) or the user missed to input it (Software like online survey)

How to handle this missing values ? 

There are 3 approaches

1. eliminate missing values
2. estimate missing values
3. replace with all possible values

### Duplicate data

Data sets may include data object that are duplicated when merging data from various sources

So We Do Data Cleaning to eliminate duplicated rows of data objects