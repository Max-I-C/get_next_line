# get_next_line

This project consists of implementing a function that uses the read system call to read a text file pointed to by a file descriptor, one line at a time. The function returns the line that has been read. If there is nothing left to read or if an error occurs, it returns NULL.

At 42, this project serves as an introduction to static variables. This function can and should also be added to your libft for use in future projects.
## Method

Context: this project requires a maximum of 10 functions, each with a maximum of 25 lines. It is up to you to determine the method you want to use in order to achieve this.

This version of the function uses a linked list to perform the reading process. Below is a representation of how a singly linked list works.

All blocks of a linked list come from a structure that is used with two parameters for a one-way linked list:

| data | next |      
| :-------- | :------- |
| `INT/CHAR/....` | `next node of the list`  |


## Installation

- Build a test file that includes the header and uses the get_next_line function
- Compile and execute the program

```bash
  gcc test.c get_next_line.c get_next_line_utils.c -o prog
  ./prog
```
    
<div align="center">
    <h3>Languages & Tools</h3>
    <p>
        <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
    </p>
</div>



