# File Handling

- `open("example.txt", "r")` allows you to read the contents of that file.
- `open("example.txt", "w")` allows you to write/overwrite information inside that file.
- `open("example.txt", "a")` allows you to append (adds on) information to that file.
- `open("example.txt", "r+")` allows you to read and write to that file.

- You can place this inside a variable:  `example_file = open("example.txt", "r")`

- Always close the file when finished: `example_file.close()`

- The with statement handles this automatically, no need for .close():
```
with open("example.txt", "r") as example_file:
     print(example_file.readline())
```
- `print(example_file.readline())` prints out one line at a time.
- `print(example_file.readlines())` prints out all lines as a list.

- `example_file.write("Hello")` writes Hello to the file.
- `example_file.write("Hello\nWorld")` \n inserts a newline character.
