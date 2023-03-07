---
title: "Exploring .txt file using Python"
datePublished: Tue Mar 07 2023 06:28:12 GMT+0000 (Coordinated Universal Time)
cuid: clexvdr2w00010al65cj78rnk
slug: exploring-txt-file-using-python
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/Oaqk7qqNh_c/upload/8f9b26b0b3156c7969d0557d7a498a64.jpeg
tags: python, data-science, pandas, text-editors, files

---

Welcome to the first article in the Series "Python and Files" where I will be using Python to open, read and write different file formats.

In this episode, We will be reading and writing text files in Python.

Python provides in-built standard libraries that are capable of writing and reading text files

### Reading a TXT file in Python

There are different ways we might want to read our text files, these are some of them.

* Read the entire text file all at once
    

```python
with open('file.txt', 'r') as file:
    contents = file.read()
    print(contents)
```

First, we use the open() method to open the file in our program and we use the "r" to signify that we are going to be reading the file.

Then we save the content of the file to a variable with the method "read()"

* Read line by line
    

```python
with open('file.txt', 'r') as file:
    contents = file.readlines()
    for i in contents:
            print(i)
```

### Writing a TXT file in Python

Similarly to reading a text file, Writing a text has multiple methods, and below are some of those methods

* Write the entire text file at once
    

```python
with open('file.txt', 'w') as file:
    file.write('Hello, world!')
```

In this case, we use the "w" to signify that we are going to be writing to the file.

Then we write to the file by using the "write() method"

* Write line by line
    

```python
lines = ['Hello', 'world', 'how', 'are', 'you']
with open('file.txt', 'w') as file:
    file.writelines('\n'.join(lines))
```

**You can use 'a' in place of 'w' when writing to an existing file ('a' stands for append)**

*That's all for "Exploring .txt file with Python"*

*Follow to get notified when new articles drop*

You can reach me on [Twitter](https://twitter.com/Daevid_Thegreat) 🐦