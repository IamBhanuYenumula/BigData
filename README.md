# BigData
Pyspark

## Transformations

###Map and flatMap:

>>> name = sc.parallelize(["bhanu","prakash"])
>>> name.collect()
['bhanu', 'prakash']
>>> b=name.map(lambda name:(name,1))
>>> b.collect()
[('bhanu', 1), ('prakash', 1)]
>>> 
