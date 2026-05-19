# level-2-task-8
# import (file) as pd.

df = pd.read_csv('balance.txt', sep=('))

df.head()
# selects top row of the dataset

df.tail(value)
# this shows/references the specified value of the dataset

df.index
RangeIndex(start= enter starting value, stop= enter specified value, step = counting method)
# this helps you know how to refer to your observations. 

df.describe()
# this shows a quick stastistic summary of your data.

df.sort.values()
# this helps you arrange observations in a well ordered manner.

COMPULSORY TASK
# select tehe limit and Rating columns of the first five observations
df.Rating.head(5)
Name : Rating, dtype : 'object'

df.Limit.head(5)
Name : Limit, dtype :'object'

df.Rating.head()
# selecting a single column in the data, which yields a series. 

df[? : ?]
# selecting values via[], which slices the rows.

df.loc{? : ?]
# locates values via th syntax[]

df[df.d.type]
# specifies characteristics of the categorical data in the dataset
