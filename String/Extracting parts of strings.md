### Extracting parts of strings
####Indexing:
– **‘abc’[0]** returns the string **‘a’**
– **‘abc’[2]** returns the string **‘c’**
– **‘abc’[3]** is an **error** (as we cannot go beyond the boundaries of the string)
– **‘abc’[-1]** returns the string **‘c’** (essentially counting backwards from the start of the string)

#### Slicing

– If **s** is a string, the expression **s[start:end]** denotes the substring that starts at start, and ends at end-1

```python
'abc'[1:3]
'bc'
```