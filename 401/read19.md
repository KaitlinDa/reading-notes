# Read 19 Automation

## Reading Questions
1. How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary module to work with them?
* In Python, the `re` module is used to work with regular expressions (regex), allowing for powerful pattern matching and text processing capabilities. Functions like `re.search()`, `re.findall()`, and `re.sub()` enable searching, finding all occurrences, and replacing patterns in strings, respectively. By compiling patterns into regex objects with `re.compile()`, you can efficiently search for patterns, making the `re` module an essential tool for text analysis and manipulation in Python.

2. What is the purpose of the shutil module in Python, and provide an example of a common use case for file or directory management with this module?
* The `shutil` module in Python helps you manage files and folders easily, like copying or moving them. An example of this is when you use `shutil.copy(source, destination)` to copy a file, or `shutil.copytree(source, destination)` to copy an entire folder with everything inside it. This makes it simple to work with files and folders in Python.

3. Compare and contrast the os and shutil modules. When would you choose to use one over the other?
* The `os` module helps you talk to your computer's operating system to do things like making and deleting files or folders. The `shutil` module is for when you want to move files around, like copying or moving a whole folder at once. You would use `os` for basic tasks and working with file paths, and `shutil` when you need to copy or move files and folders easily.

## Things I want to know more about
I would like to know more about how to use `os` and `shutil` in real programming situations. 