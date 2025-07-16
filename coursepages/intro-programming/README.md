# Học Python cơ bản

This course has been created by Professor Charles Severance from the University of Michigan.
> Learn to Program and Analyze Data with Python. Develop programs to gather, clean, analyze, and visualize data.

**Link**: <https://www.py4e.com/lessons>

**Textbook**: [PDF](http://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf) / [EPUB](http://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.epub)

### Instructions

Chỉ cần hoàn thiện đến bài: [Regular Expressions](https://www.py4e.com/lessons/regex) là được. Còn lại là tùy chọn.

### Course Materials

3. [Variables, expressions and statements](https://www.py4e.com/lessons/memory)
4. [Conditional Execution](https://www.py4e.com/lessons/logic)
5. [Functions](https://www.py4e.com/lessons/functions)
6. [Loops and Iterations](https://www.py4e.com/lessons/loops)
7. [Strings](https://www.py4e.com/lessons/strings)
8. [Files](https://www.py4e.com/lessons/files)
9. [Lists](https://www.py4e.com/lessons/lists)
10. [Dictionaries](https://www.py4e.com/lessons/dictionary)
11. [Tuples](https://www.py4e.com/lessons/tuples)
12. [Regular Expressions](https://www.py4e.com/lessons/regex)
13. [Network Programming](https://www.py4e.com/lessons/network) (Optional)
14. [Using Web Services](https://www.py4e.com/lessons/servces) (Optional)
15. [Object-Oriented Programming](https://www.py4e.com/lessons/Objects) (Optional)
16. [Databases](https://www.py4e.com/lessons/database) (Optional)
17. [Data Visualization](https://www.py4e.com/lessons/dataviz) (Optional)

### Fixes

1. If you're doing the BeautifulSoup4 lesson, there is an issue with Python 3.10+ that will give you an error referencing the Collections library. We have a fix for you. We don't expect you to understand it, just put this in front of your code in the imports block:

```python
import collections
collections.Callable = collections.abc.Callable

from bs4 import BeautifulSoup 
```

Doing this should fix the compatibility issue and allow your code to run.
