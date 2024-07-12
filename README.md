# nosql-challenge
Module 12 Challenge

## Imports and Dependencies
### Setup File
```
from pymongo import MongoClient
from pprint import pprint
```
### Analysis File
```
from pymongo import MongoClient
import pandas as pd
from pprint import pprint
```
### Importing JSON Data
To import the JSON data to MongoDB, use the following code in terminal:
```
mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
```

## Navigation of Files
* [Starter File (Setup](NoSQL_setup_starter.ipynb))
* [Starter File (Analysis)](NoSQL_analysis_starter.ipynb)
* [Resources File (JSON Format)](Resources/establishments.json)
