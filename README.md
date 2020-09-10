```python
# Finding dublicate column in dataframe
duplicate_columns = df.columns[df.columns.duplicated()]
duplicate_columns


# Reversing string
my_string = "ABCDE"
reversed_string = my_string[::-1]
print(reversed_string)


# Title case
str = "my name is Ajinkz"
# using the title() function of string class
new_str = str.title()
print(new_str)


# Find unique element from string
my_string = "aavvccccddddeee"
# stitching set into a string using join
new_string = ''.join(set(my_string))


# Split a String Into a List of Substrings
string_1 = "My name is Ajinkz"
string_2 = "sample/ string 2"

# default separator ' '
print(string_1.split())
# ['My', 'name', 'is', 'Ajinkz']

# defining separator as '/'
print(string_2.split('/'))
# ['sample', ' string 2']


# Combining a List of Strings Into a Single String
list_of_strings = ['My', 'name', 'is', 'Ajinkz']
# Using join with the comma separator
print(','.join(list_of_strings))
# Output
# My,name,is,Ajinkz


# Finding frequency of each element in a list
from collections import Counter
my_list = ['a','a','b','b','b','c','d','d','d','d','d']
count = Counter(my_list) # defining a counter object
print(count) # Of all elements
# Counter({'d': 5, 'b': 3, 'a': 2, 'c': 1})
print(count['b']) # of individual element
# 3
print(count.most_common(1)) # most frequent element
# [('d', 5)]


# Find Whether Two Strings are Anagrams
from collections import Counter
str_1, str_2 = "acbde", "abced"
cnt_1, cnt_2 = Counter(str_1), Counter(str_2)

if cnt_1 == cnt_2:
    print('1 and 2 anagram')


# Enumerate to Get Index/Value Pairs
my_list = ['a', 'b', 'c', 'd', 'e']

for index, value in enumerate(my_list):
    print('{0}: {1}'.format(index, value))

# 0: a
# 1: b
# 2: c
# 3: d
# 4: e


# Memory usage check
import sys
num = 21
print(sys.getsizeof(num))


# Merging two dict
dict_1 = {'apple': 9, 'banana': 6}
dict_2 = {'banana': 4, 'orange': 8}
combined_dict = {**dict_1, **dict_2}
print(combined_dict)
# Output
# {'apple': 9, 'banana': 4, 'orange': 8}


# Flattening the list

from iteration_utilities import deepflatten

l = [[1,2,3],[3]]
print(flatten(l))
# [1, 2, 3, 3]


# 
```
