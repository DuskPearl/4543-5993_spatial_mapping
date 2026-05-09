# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` ___.append()________________

2. How can you remove an item from a list by value?  
   `Answer:` ___.remove()________________

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` ___2, 4, 6, 8_______________

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.
fav_Foods = ['Chicken Alfredo', 'Boudin', 'Licorice']
fav_Foods.append('Pecan Pie')
fav_Foods.remove('Licorice')
print(fav_Foods)
```


---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` _Lists are mutable and tuples are immutable_

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` _No they are unchangeable.__

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
favNums = (6, 27, 13)
numOne, numTwo, numThree = favNums
print (numOne, numTwo, numThree)
```

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` ___returns the value of the item with the specified key__________

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` __with a for loop___________

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
hobbyBook = dict(name = "Joseph", age = 48, hobby = "Crochet")
print("Keys and Values:")
for key, value in zip(hobbyBook.keys(), hobbyBook.values()):
	print(f"{key}: {value}")
```

---

## 🧾 Submit Checklist

- [✅] I practiced creating and modifying lists.
- [✅] I understand how tuples are different from lists.
- [✅] I accessed and looped through dictionary items.
