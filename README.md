# ETF_Analysis

This program aims to create a database to measure the performance of an ETF including 4 stocks with tricker symobols PYPL,GOST, GS,and SQ from 2016 to 2020. The program uses Voila library in addition to Python and SQL to conduct analysis while providing interactive dashboards.


---

## Technologies

The technologies required to use for this project on either Mac or PC include:

Python 3.11.1

Jupyter Lab

Pandas 

Voila 

sqlalchemy



---

## Installation Guide

Please make sure `SQLAlchem` and `Voila` are installed in the `Conda dev` environment.


`pip install SQLAlchemy`


`conda install -c conda-forge voila`


And then we can import the required libraries and create temorary SQL database to start the program:


# Importing the required libraries and dependencies


`import numpy as np`


`import pandas as pd`


`import hvplot.pandas`


`import sqlalchemy`

Create a temporary SQLite database and populate the database with content from the etf.db seed file


`database_connection_string = 'sqlite:///etf.db'`

 Create an engine to interact with the SQLite database


`engine = sqlalchemy.create_engine(database_connection_string)`

Confirm that table names contained in the SQLite database.


`engine.table_names()`





---

## Usage

The following charts will appear upon running the program:
 
 
 
 
![Screenshot](https://raw.githubusercontent.com/sg3956/ETF_Analysis/main/PYPL_Daily_Returns.png)






![Screenshot](https://raw.githubusercontent.com/sg3956/ETF_Analysis/main/PYPL_Cummulative_Return.png)






![Screenshot](https://raw.githubusercontent.com/sg3956/ETF_Analysis/main/ETF_Cumulative_Returns.png)





---

## Contributors

Soheil Gityforoze

sg3956@columbia.edu

[LinkedIn](https://www.linkedin.com/feed/)

---

## License

MIT License

Copyright (c) [2023]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
