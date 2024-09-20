```python
import csv
```


```python
with open("D:\\23BCA298\\sqlite3\\csv\\emp2.csv","r")as read_obj:
    r=csv.reader(read_obj)
    for row in r:
        print(row)
```

    ['eid', 'ename', 'dept', 'basci', 'branch']
    ['1', 'katha', 'account', '20000', 'surat']
    ['2', 'akshu', 'hr', '40000', 'navsari']
    ['3', 'tiya', 'inventory', '56000', 'bardoli']
    ['4', 'siya', 'it', '30000', 'surat']
    ['5', 'kiya', 'account', '20000', 'bardoli']
    


```python
update emp2 set salary = salary * 1.10 where branch = 'Surat'

```


      Cell In[12], line 1
        update emp2 set salary = salary * 1.10 where branch = 'Surat'
               ^
    SyntaxError: invalid syntax
    



```python

```
