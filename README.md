# 📘 PA 1 – Programming Assignment
👨‍💻 Author: Jasper F. Ancheta <br>
📅 Date: 09/14/2025 <br>
📚 Course: ECE2112 – Programming Assignment

# 🛠 Software(s) Used  

<p align="left">
  <img src="https://www.python.org/static/community_logos/python-logo.png" alt="Python Logo" width="120"/>
  <img src="https://jupyter.org/assets/homepage/main-logo.svg" alt="Jupyter Logo" width="90"/>
</p>

# 📂 Repository Information

About: Contains solutions for PA 1 (3 Problems)

# Languages Used:

Python (100%)

# 📌 Version History

V1.0 ([09-14-2025]) – Initial Release and Submission of GitHub Link

V1.1 ([09-14-2025]) – Edited Documentation in the README File and Added Code Formatting and Design in the README File

# 📌 Problem 1: Alphabet Soup Problem

This problem takes a string as input and rearranges its letters in alphabetical order.

Example:

Input: "jasper"

Output: "aejprs"

# PA 1 – Problem 1: ALPHABET SOUP PROBLEM
# ✅ Input:
```
def alphabet(x):
    # Sort the characters in the input string 'x'
    return ''.join(sorted(x))

print(alphabet("jasper"))
```
# ✅ Output:
```
aejprs
```
# 📌 Problem 2: Emoticon Problem

This problem replaces specific keywords in a sentence with their corresponding emoticon symbols.

Mappings Used:

"smile" → :)

"grin" → :D

"sad" → :((

"mad" → >:(

# Problem 2: EMOTICON PROBLEM
# ✅ Input:
```
def remoticon(sentence):
    emo_dict = {
        'smile': ':)',
        'grin': ':D',
        'sad': ':((',
        'mad': '>:('
    }
    for word, emoticon in emo_dict.items():
        sentence = sentence.replace(word, emoticon)
    return sentence

print(remoticon('I am grin'))
```

# ✅ Output:
```
I am :D
```
# 📌 Problem 3: Unpacking List Problem

This problem demonstrates how to unpack a list into first, middle, and last elements using Python’s unpacking syntax.

# Problem 3: UNPACKING LIST PROBLEM
```
writeyourcodehere = [1, 2, 3, 4, 5, 6]
first, *middle, last = writeyourcodehere

print('First:', first)
print()
print('Middle:', middle)
print()
print('last:', last)
```

✅ Output:
```
First: 1

Middle: [2, 3, 4, 5]

last: 6
```
