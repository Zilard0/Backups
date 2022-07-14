[[Python MOC]]

### Using Variables in Strings
In some situations, you’ll want to use a variable’s value inside a string. For example, you might want two variables to represent a first name and a last name respectively, and then want to combine those values to display someone’s full name.

```python
first_name = "ada"
last_name = "lovelace"
full_name = f"{first_name} {last_name}"
print(full_name)

//Output
ada lovelace
```

