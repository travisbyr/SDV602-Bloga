# Week 12

This week I learned how to read a csv file from a URL. Here is how to do it:

```python
import pandas as pd
data = pd.read_csv('https://quakesearch.geonet.org.nz/csv?region=nelsonwestcoast&startdate=2021-09-29T1:00:00&enddate=2021-10-29T2:00:00')
print(data)
```

Pandas is a data analysis library that I will be using to read data from a CSV file. As shown above, this library enables me to read data from the data source I have chosen, which is earthquake data. 

### References

*How to read a CSV file from a URL with Python?* (2018, January 2). ExceptionsHub. Retrieved November 4, 2021, from https://exceptionshub.com/how-to-read-a-csv-file-from-a-url-with-python.html

