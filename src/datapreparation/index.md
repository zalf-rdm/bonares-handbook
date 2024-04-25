---
label: Data Preparation
icon: versions
expanded: false
order: 600
---
# Data Preparation

### General dataset properties  

A dataset summarizes research data on a delimited situation in a structured manner. The research data should be prepared
in such a way that **easy reuse** is possible. In principle, the data record should be **tabular and column-based**. In
most cases, soil and agricultural data have a **spatial reference**. The spatial position of the measuring points or
areas should be given in the table as detailed as possible.

A typical dataset for data transfer to the BonaRes Repository has the following properties:
- Each column (attribute) of the table contains the attribute name in the first row and the attribute values in the
following rows, which means the data within the **table are column-oriented**. 
- Each table or dataset must be given a short, concise name. 
- For widespread reuse, work should be done in English if possible.

Typically, each table contains the following standard column names:

_Table 1: Example table with typical standard column names of a data table_
<img src="/static/img/table_format.png" alt=" table format" />

<br>

### Formal criterias for datasets

The following formal criteria for tabular data especially submitted as Excel files must be met:

#### Table criteria

{.compact}
| **No.**   | **General criteria for tables**                                                                                                                  |
| --- | ---------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Tables** are unformatted (do not contain graphical elements, colored lines, …)                                                    |
| 2   | There are no internal references or formulas within a table    
| 3   | Tables contain only **one** worksheet (avoid Excel folders with multiple sheets)                                                   |

#### Column criteria
                                                                    
{.compact}
| **No.**  | **Criteria for column**      
| --- | ---------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Each column contains a unique attribute name (between upper and lower case not differentiated z. B. “beetles” and “Beetles” |
| 2   | **Column delimiter** is consistent and clearly identifies throughout the table (e. g. ”;” or “,”)                                  |
| 3   | Column names contain **no spaces** (an underscore „_“ is allowed to use), special characters, umlauts, “ß” or units             |
| 4   | Column names are a maximum of 30 characters long                                                                                             |
| 5   | Column names **do not** start with a number                                                                                                  |
| 6   | Column names are only assigned **once**
| 7   | Values within a column are constant (**no change of reference variable or unit**)                                                  |

#### Cell criteria
{.compact}
| **No.**  | **Criteria for cells**      
| --- | ---------------------------------------------------------------------------------------------------------------------------------- |
| 1  | **Missing values** are explicitly marked and clearly differ from “none specification "and" 0 "                                     |
| 2  | Values in the cells contain no units, explanations or abbreviations e. g. "Under detection limit” or “< 0.00 ”                     |
| 3  | Only one value specified per cell                                                                                                  |
| 4  | Cells **are not** connected                                                                                                        |
| 5  | Cells do not contain separators such as “;” (decimal numbers are uniformly written with “.” or “,” and differ from column delimiter) |
| 6  | Cells contain no spaces                                                                                                             |
| 7  | IDs are only assigned **once**                                                                                                     |
| 8  | Each line is available **once**(there are no double lines e. g. due to copy errors)                                                |


### Preferred file formats

In case of **tabular data**, the prepared dataset should be submitted in the file formats:
- Textfile (*.txt)
- Comma separated value file (*.csv)
- Excel sheet (*.xls or *.xslx).

Avoid file formats that cannot be read with common programs. For example, formats for
special company software for data loggers. In addition to tables, the BonaRes Repository 
also publishes **all formats of research data** that are common in science, such as:
- pictures, 
- videos, 
- texts. 

The BonaRes Repository also is able to deal with **complex file structures**, e.g.: 
- MS Access
- SQL 
- Shape files
- ... 

In this case contact the [support team](mailto:support-data@bonares.de) of BonaRes Repository.

