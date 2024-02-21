---
label: Data Preparation
icon: versions
expanded: false
order: 600
---
# Data Preparation

A dataset summarizes research data on a delimited situation in a structured manner. The research data should be prepared
in such a way that **easy reuse** is possible. In principle, the data record should be **tabular and column-based**. In
most cases, soil and agricultural data have a **spatial reference**. The spatial position of the measuring points or
areas should be given in the table as detailed as possible.

A typical dataset for data transfer to the BonaRes Data Centre has the following properties:

Each column (attribute) of the table contains the attribute name in the first row and the attribute values in the
following rows, which means the data within the **table are column-oriented**. Each table or dataset must be given a
short, concise name. For widespread reuse, work should be done in English if possible.

Typically, each table contains the following standard attributes:

_Table 1: Example table with typical standard attributes of a data table_

<div class="table-wrapper scrollbar overflow-hidden">
   <table class="comfortable">
   <thead style="font-size: 24px; background-color: #A8A8A8">
      <thead>
         <tr>
            <th><strong>Identifier</strong></th>
            <th><strong>x-coordinate</strong></th>
            <th><strong>y-coordinate</strong></th>
            <th><strong>Date</strong></th>
            <th><strong>beetles</strong></th>
            <th><strong>Attribute 2</strong></th>
            <th><strong>Attribute n</strong></th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <td>1</td>
            <td>52,460126<br>
            <td>13,296310<br>
            <td>17.04.2018<br>
            <td>5<br>
            <td>...<br>
            <td>...<br>
         </tr>
      </tbody>
   </table>
</div>

{.compact}
**The following formal criteria must be met:**
---
1. **Tables** are unformatted (do not contain grafical elements, colored lines, …) 
2. There are no internal references or formulas within a table |
3. Tables contain only **one** worksheet (avoid Excel folders with multiple sheets)
4. **In case of multiple sheets**, upload each sheet as a **separate table**
5. Each column contains a unique attribute name (between upper and lower case not differentiated z. B. “beetles” and “Beetles”)
6. **Column delimiter** is consistent and clearly identifies throughout the table (e. g. ”;” or “,”)
7. Attribute names contain **no spaces** (an underscore „_“ is allowed to use), special characters, umlauts, “ß” or units
8. ...are a maximum of 30 characters long
9. ...**do not** start with a number
10. ...are only assigned **once**
11. **Missing values** are explicitly marked and clearly differ from “none specification "and" 0 "
12. Values within a column are constant (**no change of reference variable or unit**)
13. Values in the cells contain no units, explanations or abbreviations e. g. "Under detection limit” or “< 0.00 ”
14. Only one value specified per cell
15. Cells **are not** connected
16. ... do not contain separators such as “;” (decimal numbers are uniformly written with “.” or “,” and differ from column delimiter)
17. IDs are only assigned **once**
18. Each line is available **once**(there are no double lines e. g. due to copy errors)
19. Cells contain no spaces
 

The prepared dataset should be submitted in the **file format txt, csv, xls or xslx.** Avoid file formats that cannot be read with common programs. For example, formats for special company software for data loggers. In addition to tables, the BonaRes Repository also publishes all formats of research data that are common in science, such as pictures, videos, texts. The BonaRes Centre also is able to deal with complex file structures (Access, SQL, Shape, ...). In this case contact the [support of BonaRes Repository](mailto:support-data@bonares.de).

!!!success File Formats
Datasets submitted in file formats, which can be integrated to the SQL database of the BonaRes Data Centre is made available with full service (options for file formats and coordinate system, description of the data model, ...). Other research data e.g., Pictures, videos or comparable formats can be downloaded by the re-user in the file format as submitted. If you have any questions, contact the [support of BonaRes Repository](mailto:support-data@bonares.de)
!!!
