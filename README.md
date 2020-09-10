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

```
