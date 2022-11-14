# task4
Task4 for "System analysis and decision making" course

Example of using the function:
```
import task4

reference = 6.5

with open('data.csv') as file:
  csvString = file.read()
  result = task4.task(csvString)
  print(result == reference)
```
