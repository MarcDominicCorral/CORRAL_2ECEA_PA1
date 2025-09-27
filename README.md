# CORRAL_2ECEA_PA1

# ECE2112

# Programming_Assignment_1
This Programming Assignment contains Python Code solution to Alphabet Soup, Emoticon and Unpacking List Problems. This is made by Marc Dominic C. Corral from 2-ECE-A as a programming assignment for ECE 2112 - Advance Computer Programming and Algorithms course.

# Alphabet Soup Problem 
This Python Code creates a function that arrange the letters of a given word to be in alphabetical order.

# Steps:
1.) Set up the function using def function()
```python
def alphabet_soup(string) #It is the function that takes the string and rearranges it alphabetically.
```
2.) Set up the actual command, for this particular problem, I used various commands to arrange the letters alphabetically.
```python
"".join() #It takes the list of sorted letters and joins it back together into a single string.
sorted() #This takes the string and coverts it into a sorted list based on ASCII values.
string.replace("","") #It replaces the words from their original form to arranged alphabetically.
```
3.) Combine all the commands and construct the Python Code/Script.
```python
def alphabet_soup(string):
  string = "".join(sorted(string.replace(",")))
  return string
```
4.) Test the results.

<img width="1453" height="193" alt="image" src="https://github.com/user-attachments/assets/a80d7109-abf6-47fa-846d-0fa73bb479bc" />

# Emoticon Problem 
This Python Code creates a function that changes a specific word into an emoticon within the given phrase.

# Steps:
1.) Assign a function using def function()
```python
def emotify(string) #It is the function that will be used to replace certain strings with emoticons.
```
2.) Create a variable, which we can use to replace the certain words assigned.
```python
emoticons ={} #It is a dictionary function that set a certain string into an emoticon.
```
3.) Construct a loop statement.
```python
for word, emoticon in emoticons.items() #It is a for loop that iterates every item in the emoticons dictionary.
```
4.) Use the command .replace() to change the word into emoticons.
```python
string = string.replace(word, emoticon) #It replaces the words in the input with their respective set of emoticons.
```
5.) Combine all the commands and construct the Python Code/Script.
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
6.) Test the result.

<img width="1454" height="362" alt="image" src="https://github.com/user-attachments/assets/ffeae4d2-a33d-4996-9ef9-cbfad1a2edf1" />

# Unpacking List Problem 
This Python Code unpacks a given list into its first, middle, and last segments then prints all three variables.

# Steps:
1.) Create the function using def function()
```python
def unpack_list_slicing(input): #It is the function where the unpacking is made.
```
2.) Using input[], we will get each element of the input, using indexes to get a certain value.
```python
first = input[0] #It gets the first element.
middle = input[1:-1] #It gets the elements between the first and the last.
last = input[-1] #It gets the last element.
```
3.) Print the Statement.
```python
print(f"first: {first}\tmiddle: {middle}\tlast: {last}") #It prints the formatted output with tab spacing (\t)
return first, middle, last #It returns a tuple containing the three values.

unpack_list_slicing(input = [1,2,3,4,5,6])
```
4.) Combine all the commands and construct the Python Code/Script.
```python
def unpack_list_slicing(input):
    first = input[0]
    middle = input [1:-1]
    last = imput[-1]

    print(f"first: {first}\tmiddle: {middle}\tlast: {last}")
    return first, middle, last

    unpack_list_slicing(input = [1,2,3,4,5,6])
```
5.) Run the Python Code/Script.

<img width="562" height="65" alt="image" src="https://github.com/user-attachments/assets/459e2df1-b397-4b6b-9f1b-0e0a1fb8683a" />
