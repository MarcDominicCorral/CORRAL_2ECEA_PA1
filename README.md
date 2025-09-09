# CORRAL_2ECEA_PA1

# ECE2112

# Programming_Assignment_1
This Programming Assignment contains Python Code solution to Alphabet Soup, Emoticon and Unpacking List Problems. This is made by Marc Dominic C. Corral from 2-ECE-A as a programming assignment for ECE 2112 - Advance Computer Programming and Algorithms course.

# Alphabet Soup Problem 
This Python Code creates a function that arrange the letters of a given word to be in alphabetical order.

# Python Code:
```python
def alphabet_soup(string):
  string = "".join(sorted(string.replace(",")))
  return string
```
# Test:
<img width="1453" height="193" alt="image" src="https://github.com/user-attachments/assets/a80d7109-abf6-47fa-846d-0fa73bb479bc" />

# Code Eplanation:
```python
alphabet_soup() #It is the function that takes the string and rearranges it alphabetically.
"".join() #It takes the list of sorted letters and joins it back together into a single string.
sorted() #This takes the string and coverts it into a sorted list based on ASCII values.
string.replace("","") #It replaces the words from their original form to arranged alphabetically.
```

# Emoticon Problem 
This Python Code creates a function that changes a specific word into an emoticon within the given phrase.

# Python Code:
```python
def emotify(string)
    emoticons = {
        "smile":":)",
        "grin":":D",
        "sad":":((",
        "mad":">:("
    }
    for word, emoticon in emoticons.items():
        string = string.replace(word,emoticon)
    return string
```

# Test:
<img width="1454" height="362" alt="image" src="https://github.com/user-attachments/assets/ffeae4d2-a33d-4996-9ef9-cbfad1a2edf1" />

# Code Eplanation:
```python
emoticons ={} #It is a dictionary function that set a certain string into an emoticon.
for word, emoticon in emoticons.items() #It is a for loop that iterates every item in the emoticons dictionary.
string = string.replace(word, emoticon) #It replaces the words in the input with their respective set of emoticons.
```

# Unpacking List Problem 
This Python Code unpacks a given list into its first, middle, and last segments then prints all three variables.

# Python Code:
```python
def unpack_list_slicing(input):
    first = input[0]
    middle = input [1:-1]
    last = imput[-1]

    print(f"first: {first}\tmiddle: {middle}\tlast: {last}")
    return first, middle, last

    unpack_list_slicing(input = [1,2,3,4,5,6])
```

# Output 
<img width="562" height="65" alt="image" src="https://github.com/user-attachments/assets/459e2df1-b397-4b6b-9f1b-0e0a1fb8683a" />

# Code Explanation:
```python
unpack_list_slicing() #It is the function where the unpacking is made.
first = input[0] #It gets the first element.
middle = input[1:-1] #It gets the elements between the first and the last.
last = input[-1] #It gets the last element.
```
