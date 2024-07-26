<h1 align="center"><a href="https://github.com/f-corvaro/PUSH_SWAP/tree/main">
	<img src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/ps.png" alt="PUSH_SWAP">
  </a></h1>

<p align="center">
	<b><i>"Algorithm that sorts data using two stacks."</i></b><br>
</p>
<p align="center" style="text-decoration: none;">
    <a href="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/en.subject.pdf"><img alt="subject" src="https://img.shields.io/badge/subject-PUSH_SWAP-yellow" /></a>
    <a href="https://github.com/f-corvaro/PUSH_SWAP"><img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/f-corvaro/PUSH_SWAP?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/PUSH_SWAP"><img alt="Code language count" src="https://img.shields.io/github/languages/count/f-corvaro/PUSH_SWAP?color=yellow" /></a>
    <a href="https://github.com/f-corvaro/PUSH_SWAP"><img alt="GitHub top language" src="https://img.shields.io/github/languages/top/f-corvaro/PUSH_SWAP?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/PUSH_SWAP"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/f-corvaro/PUSH_SWAP?color=yellow" /></a>
</p>

<h3 align="center">Index</h3>
<p align="center">
 <a href="#introduction">Introduction</a><br>
 <a href="#overview">Overview</a><br>
 <a href="#folder-structure">Folder Structure</a><br>
 <a href="#project-requirements---mandatory-part">Project Requirements - Mandatory Part</a><br>
 <a href="#important-rules-and-guidelines">Important Rules and Guidelines</a><br>
 <a href="#program-name">Program name</a><br>
 <a href="#files-to-submit">Files to Submit</a><br>
 <a href="#allowed-external-functions">Allowed External Functions</a><br>
 <a href="#project-objective">Project Objective</a><br>
 <a href="#sorting-rules">Sorting Rules</a><br>
 <a href="#example">Example</a><br>
 <a href="#requirements">Requirements</a><br>
 <a href="#provided-resources">Provided Resources</a><br>
 <a href="#usage-examples">Usage Examples</a><br>
 <a href="#performance-benchmarks">Performance Benchmarks</a><br>
 <a href="#project-requirements---bonus-part">Project Requirements - Bonus Part</a><br>
 <a href="#program-name-1">Program Name</a><br>
 <a href="#files-to-submit-1">Files to Submit</a><br>
 <a href="#external-functs-allowed">External functs. allowed</a><br>
 <a href="#expected-behavior">Expected Behavior</a><br>
 <a href="#usage-examples-1">Usage Examples</a><br>
 <a href="#theoretical-background">Theoretical Background</a><br>
 <a href="#data-structures">Data Structures</a><br>
 <a href="#algorithms">Algorithms</a><br>
 <a href="#sorting-algorithms">Sorting Algorithms</a><br>
 <a href="#algorithm-complexity-and-efficiency">Algorithm Complexity and Efficiency</a><br>
 <a href="#stable-sorting-algorithms">Stable Sorting Algorithms</a><br>
 <a href="#unstable-sorting-algorithms">Unstable Sorting Algorithms</a><br>
 <a href="#additional-resources">Additional Resources</a><br>
 <a href="#organizing-your-first-major-project">Organizing Your First Major Project</a><br>
 <a href="#running-tests">Running Tests</a><br>
 <a href="#memory-leak-detection">Memory Leak Detection</a><br>
 <a href="#installation">Installation</a><br>
 <a href="#usage-ubuntu">Usage Ubuntu</a><br>
 <a href="#usage-macos">Usage macOS</a><br>
 <a href="#graphical-user-interface-gui-for-testing">Graphical User Interface (GUI) for Testing</a><br>
 <a href="#installation-steps">Installation Steps</a><br>
 <a href="#how-to-use-the-visualizer">How to Use the Visualizer</a><br>
 <a href="#additional-resources-1">Additional Resources</a><br>
 <a href="#evaluation-process">Evaluation Process</a><br>
 <a href="#testing-your-project">Testing Your Project</a><br>
 <a href="#correction-sheet">Correction Sheet</a><br>
 <a href="#developed-skills">Developed Skills</a><br>
 <a href="#references">References</a><br>
 <a href="#support-and-contributions">Support and Contributions</a><br>
 <a href="#author">Author</a><br>
</p>
<br>

## Introduction

<p align="justify">

The push_swap project is a part of the 42 school curriculum and aims to develop a program named `push_swap` that sorts a list of integers using two stacks. The goal of the project is to achieve the lowest possible number of operations to sort the stack A, while adhering to a limited set of instructions and utilizing the stack B.

</p>
<br>

### Overview

<p align="justify">

The `push_swap` program follows a set of rules and operations to manipulate the stacks. These operations include swapping elements, pushing elements between stacks, and rotating elements within a stack. By applying these operations strategically, the program can efficiently sort the stack A.

The project requirements include writing the program in C, adhering to the Norm coding style, properly managing memory allocation, and providing a Makefile to compile the source files. The program should display the smallest list of instructions possible to sort the stack A, with the smallest number being at the top.

To evaluate the program's performance, the number of instructions generated by `push_swap` is compared against predefined limits for different stack sizes. The project also allows the use of the `libft` library and requires error handling for invalid input.

By completing the push_swap project, students gain experience in algorithm design, stack manipulation, and optimization. It challenges their problem-solving skills and encourages them to find efficient sorting strategies within the given constraints.

<p>
<br>

## Folder Structure

<p align="justify">

```
.
├── push_swap
│   ├── include
│   │   └── push_swap.h
│   ├── lib
│   ├── srcs
│   │   ├── ft_error_handling.c
│   │   ├── ft_free.c
│   │   ├── ft_id_stack_a.c
│   │   ├── ft_id_stack_b.c
│   │   ├── ft_init_op.c
│   │   ├── ft_input_preparation.c
│   │   ├── ft_op_p.c
│   │   ├── ft_op_r.c
│   │   ├── ft_op_rr.c
│   │   ├── ft_op_s.c
│   │   ├── ft_stack_calc_a.c
│   │   ├── ft_stack_calc_b.c
│   │   ├── ft_stack_calc.c
│   │   ├── ft_stack_half_opa.c
│   │   ├── ft_stack_half_opb.c
│   │   ├── ft_stack_op.c
│   │   ├── ft_stack_searching_op.c
│   │   ├── ft_stack_sorting.c
│   │   ├── ft_utils.c
│   │   └── main.c
│   ├── srcs_b
│   │   ├── ft_checker.c
│   │   └── main.c
│   └── Makefile
├── resources_given
│   ├── checker_linux
│   └── checker_Mac
└── README.md
```

<br>

## Project Requirements - Mandatory Part

### Important Rules and Guidelines

<p align="justify">

- Your project must be written in C, adhering to the Norm.
- Your functions should not terminate unexpectedly (e.g., segmentation fault, bus error, double free) except in cases of undefined behavior.
- All dynamically allocated memory must be properly freed when no longer needed.
- You must submit a Makefile that compiles your source files to the required output using the flags `-Wall`, `-Wextra`, and `-Werror`. The Makefile should use `cc` and must not relink. It must include at least the following rules: `$(NAME)`, `all`, `clean`, `fclean`, and `re` (include `bonus` for maximum score).
- If your project allows the use of your `libft`, you must copy its source files and associated Makefile into a `libft` folder. Your project's Makefile must compile the library using its Makefile before compiling the project.
- Global variables are forbidden.

<p>

### Program name

<p align="justify">

The program is called `push_swap` and takes a stack A (a list of integers) as its arguments.

</p>

### Files to Submit

<p align="justify">

You need to submit the following files: `Makefile`, `*.h`, `*.c`.

</p>

### Allowed External Functions

<p align="justify">

You are permitted to use the `libft` library, along with the following functions:

1. `read, write, malloc, free, exit`
2. `ft_printf` and any equivalent functions you have coded

</p>
<br>

### Project Objective

<p align="justify">

The objective is to sort the stack with the minimum number of operations. 

</p>

#### Sorting Rules

<p align="justify">

You have two stacks named `a` and `b`. Stack `a` contains a random amount of unique negative and/or positive numbers, while stack `b` is initially empty. The goal is to sort the numbers in ascending order in stack `a`. To achieve this, you have the following operations at your disposal:

| Operation | Description |
| --------- | ----------- |
| `sa` (swap a) | Swap the first two elements at the top of stack `a`. Do nothing if there is only one or no elements. |
| `sb` (swap b) | Swap the first two elements at the top of stack `b`. Do nothing if there is only one or no elements. |
| `ss` | Perform `sa` and `sb` simultaneously. |
| `pa` (push a) | Take the first element at the top of `b` and put it at the top of `a`. Do nothing if `b` is empty. |
| `pb` (push b) | Take the first element at the top of `a` and put it at the top of `b`. Do nothing if `a` is empty. |
| `ra` (rotate a) | Shift up all elements of stack `a` by one. The first element becomes the last one. |
| `rb` (rotate b) | Shift up all elements of stack `b` by one. The first element becomes the last one. |
| `rr` | Perform `ra` and `rb` simultaneously. |
| `rra` (reverse rotate a) | Shift down all elements of stack `a` by one. The last element becomes the first one. |
| `rrb` (reverse rotate b) | Shift down all elements of stack `b` by one. The last element becomes the first one. |
| `rrr` | Perform `rra` and `rrb` simultaneously. |

</p>

#### Example

<p align="justify">

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="450" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/example.png">

</p>

#### Requirements

<p align="justify">

- The first argument should be at the top of the stack.
- Instructions must be separated by a newline (`\n`) and nothing else.
- The program must display the smallest list of instructions possible to sort stack `a`, with the smallest number at the top.
- If no parameters are specified, the program must not display anything and should return the prompt.
- In case of an error, the program must display `"Error"` followed by a newline (`\n`) on the standard error. Errors include:
  - Some arguments are not integers.
  - Some arguments exceed the integer limit (MAXINT).
  - There are duplicate arguments.

</p>

#### Provided Resources

<p align="justify">

Two programs named `checker` are provided: one for Linux and one for macOS. You can download them from [here](https://github.com/f-corvaro/PUSH_SWAP/tree/main/resources). To use these executables correctly, you need to modify their permissions. Run the following command:

```bash
chmod 777 <name_of_the_executable>
```

</p>

#### Usage Examples

<p align="justify">

The `push_swap` program takes the unsorted list of integers as input and processes it using its sorting algorithm. It generates a list of instructions that describe the steps required to sort the list.

```bash
$>ARG="4 67 3 87 23"; ./push_swap $ARG | ./checker_OS $ARG
OK
$>
```

If the program `checker_OS` displays "KO", it means that your `push_swap` program generated a list of instructions that does not correctly sort the numbers.

The command `ARG="4 67 3 87 23"` initializes a variable `ARG` and assigns the string "4 67 3 87 23" to it. This string contains a sequence of space-separated numbers: 4, 67, 3, 87, and 23. These numbers represent the unsorted list of integers that will be passed to the `push_swap` program. The `ARG` variable acts as a placeholder for the unsorted list of integers and is used later in the command to pass the list to the `push_swap` program.

A pipe (`|`) is used to connect the output of the `push_swap` program to the input of the `wc -l` command. Each instruction generated by the `push_swap` program represents a separate line. The `wc -l` command counts the number of lines in its input, effectively counting the number of instructions generated by the `push_swap` program.

```bash
$>./push_swap 2 1 3 6 5 8
sa
pb
pb
pb
sa
pa
pa
pa
```

```bash
$>./push_swap 0 one 2 3
Error
```

```bash
$>ARG="4 67 3 87 23"; ./push_swap $ARG | wc -l
6
```

<p>

#### Performance Benchmarks

<p align="justify">

The performance of your `push_swap` program will be evaluated based on the number of operations required to sort different sets of numbers. The benchmarks are as follows:

- **Required:**
  - Sort 3 numbers with ≤ 3 operations
  - Sort 5 numbers with ≤ 12 operations

- **Scored:**
  - Sort 100 numbers:
    - ≤ 700 operations (max score)
    - ≤ 900 operations
    - ≤ 1100 operations
    - ≤ 1300 operations
    - ≤ 1500 operations (min score)
  - Sort 500 numbers:
    - ≤ 5500 operations (max score)
    - ≤ 7000 operations
    - ≤ 8500 operations
    - ≤ 10000 operations
    - ≤ 11500 operations (min score)

<p>
<br>

## Project Requirements - Bonus Part

<p align="justify">

The bonus task involves creating your own checker program. This checker takes the initial stack `a` as a list of integers passed as arguments. The first argument should be at the top of the stack (be mindful of the order). If no argument is given, the program should stop and display nothing. The checker will then wait and read instructions from the standard input, with each instruction followed by a newline (`\n`). Once all instructions have been read, the program must execute them on the stack received as an argument.

</p>

### Program Name

<p align="justify">

The program is named `checker` and takes as arguments a stack `A` (a list of integers).

</p>

### Files to Submit

<p align="justify">

You need to submit the following files:

- `*.h`
- `*.c`

</p>


### External functs. allowed:**

<p align="justify">

You are allowed to use the following external functions:

- Functions from the `Libft` library.
- Standard library functions: `read`, `write`, `malloc`, `free`, `exit`.
- `ft_printf` or any equivalent function that you have coded.

</p>

### Expected Behavior

<p align="justify">

- **Correct Execution**: If, after executing the instructions, stack `a` is sorted in ascending order and stack `b` is empty, the program must display `"OK"` followed by a newline (`\n`) on the standard output.
- **Incorrect Execution**: In all other cases, the program must display `"KO"` followed by a newline (`\n`) on the standard output.
- **Error Handling**: In case of an error, the program must display `"Error"` followed by a newline (`\n`) on the standard error. Errors include:
  - Non-integer arguments.
  - Arguments exceeding the integer limit.
  - Duplicate arguments.
  - Non-existent or incorrectly formatted instructions.

</p>

### Usage Examples

<p align="justify">

```bash
$>./checker 3 2 1 0
rra
pb
sa
rra
pa
OK
```

```bash
$>./checker 3 2 1 0
sa
rra
pb
KO
```

```bash
$>./checker 3 2 one 0
Error
```

```bash
$>./checker "" 1
Error
$>
```

<p align="justify">

You do not have to reproduce the exact behavior of the provided binary. It is mandatory to manage errors, but you can decide how to parse the arguments.

<p>
<br>

## Theoretical Background

### Data Structures

<p align="justify">

- **Stacks**: Stacks are a type of data structure that follows the LIFO (Last In, First Out) principle. In a stack, the last element added is the first one to be removed. Stacks are commonly used in various applications, including the `push_swap` program.

  - **Operations**: Stacks support several operations:

    - `push`: This operation adds an element to the top of the stack.

    - `pop`: This operation removes the top element from the stack.

    - `peek`: This operation allows you to access the top element of the stack without removing it.

    - `isEmpty`: This operation checks if the stack is empty or not.

  Stacks are efficient for managing data that needs to be accessed in a last-in, first-out manner. They are widely used in programming and can be implemented using arrays or linked lists.

<p>
<br>

### Algorithms

<p align="justify">

An algorithm is a step-by-step procedure or set of rules for solving a specific problem or accomplishing a specific task. It is a well-defined sequence of instructions that takes an input and produces an output. Algorithms are used in various fields, including computer science, mathematics, and engineering, to solve complex problems efficiently and effectively. 

<p>
<br>

#### Sorting Algorithms

<p align="justify">

A sorting algorithm, on the other hand, is a specific type of algorithm that arranges a collection of elements in a particular order. The goal of a sorting algorithm is to rearrange the elements in ascending or descending order, based on a specified comparison criterion. Sorting algorithms are widely used in computer science and data processing to organize and retrieve data efficiently. There are various sorting algorithms available, each with its own advantages and disadvantages in terms of time complexity, space complexity, and stability. Some common sorting algorithms include merge sort, insertion sort, bubble sort, and quicksort. These algorithms employ different techniques and strategies to achieve the desired sorting outcome. Overall, sorting algorithms play a crucial role in data manipulation and analysis, enabling efficient searching, filtering, and processing of large datasets. 

<p>
<br>

#### Algorithm Complexity and Efficiency

<p align="justify">

When analyzing algorithms, it is important to understand their complexity and efficiency. This helps us determine how the algorithm's performance scales with the size of the input.

One commonly used notation for describing algorithm complexity is Big O notation. It provides an upper bound on the running time of an algorithm, indicating how the algorithm's performance grows as the input size increases.

Here are some common Big O notations and their corresponding time complexities:

- **O(1)**: Constant time complexity. The algorithm's running time remains constant regardless of the input size. This is the most efficient time complexity.

- **O(log n)**: Logarithmic time complexity. The algorithm's running time increases logarithmically with the input size. Algorithms with this complexity often divide the input in half at each step, such as binary search.

- **O(n)**: Linear time complexity. The algorithm's running time grows linearly with the input size. As the input doubles, the running time also doubles. This is a common time complexity for algorithms that iterate through each element in the input.

- **O(n log n)**: Linearithmic time complexity. The algorithm's running time grows in proportion to the product of the input size and its logarithm. This complexity is often seen in efficient sorting algorithms like merge sort and quicksort.

- **O(n^2)**: Quadratic time complexity. The algorithm's running time grows quadratically with the input size. As the input doubles, the running time quadruples. This complexity is common in algorithms that involve nested loops.

- **O(2^n)**: Exponential time complexity. The algorithm's running time grows exponentially with the input size. This is the least efficient time complexity and should be avoided whenever possible.

By understanding the time complexity of an algorithm, we can make informed decisions about which algorithm to use for a given problem. It allows us to assess the trade-off between efficiency and scalability, ensuring that our programs can handle larger inputs without significant performance degradation.

Remember, Big O notation provides an upper bound on the running time, so an algorithm with a better time complexity is generally more efficient. However, other factors like memory usage and implementation details should also be considered when evaluating algorithm efficiency.

In addition to time complexity, algorithm analysis also involves evaluating other factors such as space complexity, which measures the amount of memory an algorithm requires to solve a problem. Space complexity is typically expressed in terms of the input size and can be analyzed using similar notations as time complexity.

Furthermore, algorithm analysis may consider factors like algorithmic correctness, stability, and adaptability. Correctness ensures that the algorithm produces the expected output for all valid inputs. Stability refers to whether the algorithm preserves the relative order of equal elements during sorting or other operations. Adaptability refers to the algorithm's ability to handle different types of inputs or adapt to changing circumstances efficiently.

Overall, algorithm analysis is a crucial step in designing and optimizing algorithms. It helps us understand their behavior, make informed decisions, and improve the efficiency and scalability of our programs.

<p>
<br>


#### Stable Sorting Algorithms

<p align="justify">

Stable sorting algorithms are designed to preserve the relative order of equal elements during the sorting process. This means that if two elements have the same value, their original order will be maintained in the sorted output. Stable sorting algorithms are particularly useful when sorting objects with multiple keys or when the original order of equal elements is important.

Some examples of stable sorting algorithms include:

- **Merge Sort**: Merge sort is a divide-and-conquer algorithm that recursively divides the input into smaller subproblems, sorts them, and then merges the sorted subproblems to produce the final sorted output. Merge sort has a time complexity of O(n log n) and is considered one of the most efficient sorting algorithms.

- **Insertion Sort**: Insertion sort is a simple sorting algorithm that builds the final sorted array one element at a time. It iterates through the input array, comparing each element with the elements before it and inserting it into the correct position. Insertion sort has a time complexity of O(n^2) for average and worst cases, but it performs well on small input sizes and partially sorted arrays.

- **Bubble Sort**: Bubble sort is a simple sorting algorithm that repeatedly swaps adjacent elements if they are in the wrong order. It continues this process until the entire array is sorted. Bubble sort has a time complexity of O(n^2) and is not efficient for large input sizes, but it is easy to understand and implement.

- **Binary Tree Sort**: Binary tree sort builds a binary search tree from the input elements and then performs an in-order traversal of the tree to retrieve the sorted output. Binary tree sort has a time complexity of O(n log n) and requires additional space for the tree structure.

#### Unstable Sorting Algorithms

Unstable sorting algorithms do not guarantee the preservation of the relative order of equal elements during the sorting process. This means that the original order of equal elements may change in the sorted output. Unstable sorting algorithms are often faster and more memory-efficient than stable sorting algorithms.

Some examples of unstable sorting algorithms include:

- **Quicksort**: Quicksort is a divide-and-conquer algorithm that selects a pivot element and partitions the input array into two subarrays, one with elements less than the pivot and one with elements greater than the pivot. It then recursively sorts the subarrays. Quicksort has an average time complexity of O(n log n) and a worst-case time complexity of O(n^2), but it is often faster in practice due to its efficient partitioning.

- **Heap Sort**: Heap sort builds a binary heap from the input elements and repeatedly extracts the maximum element from the heap to produce the sorted output. Heap sort has a time complexity of O(n log n) and is an in-place sorting algorithm, meaning it does not require additional space beyond the input array.

- **Selection Sort**: Selection sort repeatedly selects the minimum element from the unsorted part of the array and swaps it with the first unsorted element. It continues this process until the entire array is sorted. Selection sort has a time complexity of O(n^2) and is not efficient for large input sizes, but it has the advantage of minimizing the number of swaps.

It's important to consider the stability of sorting algorithms when the relative order of equal elements is significant. Stable sorting algorithms are preferred in such cases to ensure the desired order is maintained. However, if the relative order of equal elements is not important or if performance is a priority, unstable sorting algorithms can be more suitable.

<br>

#### Additional Resources

- [Top 10 Sorting Algorithms You Need to Know](https://www.crio.do/blog/top-10-sorting-algorithms/)
- [Big O Notation Explained](https://www.bigocheatsheet.com/)

</p>
<br>

## Organizing Your First Major Project

<p align="justify">

Embarking on your first significant project can be daunting, but with the right approach, you can manage it effectively. Here are some steps to help you get started:

1. **Understand the Requirements**: Begin by thoroughly understanding what the program needs to accomplish. Study the necessary theory and decide on the algorithm you want to implement.
2. **Break Down the Project**: Divide the project into smaller, manageable tasks. This will make it easier to tackle each part individually and avoid feeling overwhelmed.

To help you visualize this process, here is an example of an organization pattern:

Firstly, you need to understand what this program should do. You need to study all the theory that you need and understand which algorithm you want to implement in your code. Secondly, you need to do a pattern to understand how to divide this project into many smaller ones. So, don't panic. I will show you my organization pattern:

<a href="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/Push_Swap.png"><img src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/Push_Swap.png">

</p>
<br>

## Running Tests

<p align="justify">

My project is based on a brute force sorting algorithm. I have completed both the mandatory and bonus parts, and each function includes a Doxygen style comment explaining its purpose.

To generate a set of random numbers for testing, I used the following Python script:

```py
import random
numbers = random.sample(range(-2147483648, 2147483647), 500)
random.shuffle(numbers)
print(' '.join(map(str, numbers)))
```

You can run this script on this [online Python interpreter](https://www.online-python.com/).

</p>
<br>

### Memory Leak Detection

<p align="justify">

To find memory leaks and errors, I used `Valgrind`. Below are the steps for installation and usage:

#### Installation

Depending on your Linux distribution, use one of the following commands to install Valgrind:

```shell
sudo apt install valgrind  # Ubuntu, Debian, etc.
sudo yum install valgrind  # RHEL, CentOS, Fedora, etc.
sudo pacman -Syu valgrind  # Arch, Manjaro, Garuda, etc.
sudo pkg ins valgrind      # FreeBSD
```

#### Usage Ubuntu

To check for memory leaks and errors, use the following Valgrind command:

```shell
valgrind --leak-check=full --show-leak-kinds=all --track-origins=yes -s ./a.out
```

- `--leak-check=full`: Perform a detailed memory leak check.
- `--show-leak-kinds=all`: Show all kinds of leaks, including definitely lost, indirectly lost, possibly lost, and still reachable.
- `--track-origins=yes`: Track the origins of uninitialized values.
- `-s`: Provide a summary of the leak check.
- ADDITIONAL `--log-file`: Directs Valgrind's output to a specified file. This is useful for preserving extensive output that exceeds terminal capacity, allowing for easier review and analysis.

#### Usage macOS

To check for memory leaks and errors on macOS, use the following `leaks` command:

```leaks -atExit -- ./your_program > leaks_report.txt```

  - `-atExit`: Perform the leak check at the exit of the program.
  - `--`: Indicates the end of options and the start of the program to be checked.
  - `> leaks_report.txt`: Redirects the output to a file named leaks_report.txt for easier review and analysis. This is useful for preserving extensive output that exceeds terminal capacity, allowing for easier review and analysis.

<br>

### Graphical User Interface (GUI) for Testing

<p align="justify">

To visualize the stacks, I used the [push-swap-gui 1.1](https://pypi.org/project/push-swap-gui/) package, written in Python. This package is available on PyPI and can be installed using `pip3`. To run the GUI, navigate to your `push_swap` folder and execute the command: `push_swap_gui`.

#### Installation Steps

1. **Install the GUI Package**:
   
 ```bash
 pip3 install push_swap_gui
 ```

2. **Run the GUI**

 ```bash
 push_swap_gui
 ```

**Troubleshooting**

 If you encounter an error similar to the following:

 ```bash
 ERROR: Command errored out with exit status 1:
 command: /usr/bin/python3 -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'/tmp/pip-install-amjzzxzo/pyttk/setup.py'"'"'; __file__='"'"'/tmp/pip-install-amjzzxzo/pyttk/setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' egg_info --egg-base /tmp/pip-install-amjzzxzo/pyttk/pip-egg-info
 cwd: /tmp/pip-install-amjzzxzo/pyttk/
 Complete output (7 lines):
 Traceback (most recent call last):
 File "<string>", line 1, in <module>
 File "/tmp/pip-install-amjzzxzo/pyttk/setup.py", line 2, in <module>
 import ttk
 File "/tmp/pip-install-amjzzxzo/pyttk/ttk.py", line 36, in <module>
 import tkinter as Tkinter
 ModuleNotFoundError: No module named 'tkinter'
 ----------------------------------------
 ERROR: Command errored out with exit status 1: python setup.py egg_info Check the logs for full command output.
 ```

 You need to install Tkinter, the standard GUI library for Python. Tkinter provides a fast and easy way to create GUI applications with a powerful object-oriented interface to the Tk GUI toolkit. To install Tkinter on Linux, run the following command:

 ```bash
 sudo apt-get install python3-tk
 ```

#### How to Use the Visualizer

To use the visualizer for your `push_swap` project, follow these steps:

1. **Select a Range of Numbers**: Choose a range of numbers to generate stack A. Remember that 0 counts as 1.
2. **Configure the Visualizer**:
   - Uncheck the square flag.
   - Select the path to your `push_swap` executable.
3. **Calculate Moves**: Calculate the number of moves required.
4. **Run the Visualizer**: Click the play button to view the visualizer's moves. You can control the speed of the visualization.

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img align="center" alt="running test" width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/visualizer_my_ps.gif">

### Additional Resources

For automated testing, you can use the [Push_Swap Tester](https://github.com/Aldisti/push_swap-tester) by [Aldisti](https://github.com/Aldisti).

</p>
<br>

## Evaluation Process

<p align="justify">

Test the following notable cases: 0, 1, 3, 5, 50, 100, 250, and 500. Perform multiple iterations for each case to thoroughly evaluate and understand the efficiency of the algorithm.

</p>

### Testing Your Project

<p align="justify">

To ensure your project meets all requirements, perform the following tests:

1. **Norm Check**: Run `norminette -R CheckForbiddenSourceHeader` in the `push_swap` directory to check for norm compliance.
2. **Command Tests**: Verify the commands requested using `make`.
3. **Memory Leak Tests**: Check for memory leaks.
4. **Error Management**: Ensure proper error handling.
5. **Push_Swap Tests**: Test the functionality of your `push_swap` implementation.
6. **Checker Tests**: Validate the checker program.

### Correction Sheet

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/.cs/cs1.png">

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/.cs/cs2.png">

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/.cs/cs3.png">

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/.cs/cs4.png">

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/.cs/cs5.png">

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/.cs/cs6.png">

<a href="https://github.com/f-corvaro/PUSH_SWAP"><img width="650" src="https://github.com/f-corvaro/PUSH_SWAP/blob/main/.extra/.cs/cs7.png">

</p>
<br>

## Developed Skills

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,c,vim,vscode" />
  </a>
</p><br>

## References

- [Analysis of Algorithms](https://en.wikipedia.org/wiki/Analysis_of_algorithms) - An overview of algorithm analysis, including time and space complexity.

- [Stack Data Structure](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)) - Detailed explanation of the stack abstract data type and its operations.

- [Binary Search Algorithm](https://en.wikipedia.org/wiki/Binary_search_algorithm) - Comprehensive guide to the binary search algorithm, its implementation, and use cases.

- [Push_swap Algorithm](https://medium.com/@jamierobertdawson/push-swap-the-least-amount-of-moves-with-two-stacks-d1e76a71789a) - An article on solving the push_swap problem with the least number of moves using two stacks.

- [Linked Lists in C](https://www.learn-c.org/en/Linked_lists) - Tutorial on implementing and using linked lists in the C programming language.

- [Basics of Sorting Algorithms](https://medium.com/basecs/sorting-out-the-basics-behind-sorting-algorithms-b0a032873add) - Introduction to the fundamental concepts behind sorting algorithms.

- [Quicksort Algorithm](https://lamfo-unb.github.io/2019/04/21/Sorting-algorithms/#:~:text=%2B1%5D%20%3D%20temp-,Quicksort,greater%20numbers%20on%20the%20right.) - In-depth explanation of the quicksort algorithm and its implementation.

- [Top 10 Sorting Algorithms](https://www.crio.do/blog/top-10-sorting-algorithms/) - Overview of the top 10 sorting algorithms, their complexities, and use cases.

- [Understanding Quicksort](https://medium.com/basecs/pivoting-to-understand-quicksort-part-2-30161aefe1d3) - Detailed article on the quicksort algorithm, focusing on the pivot selection.

- [Efficient Push_swap Algorithm](https://medium.com/@ayogun/push-swap-c1f5d2d41e97) - Exploration of the most efficient algorithms for solving the push_swap problem.

- [Fastest Push_swap Algorithm](https://zainab-dnaya.medium.com/fastest-push-swap-algorithm-2f510028602b) - Analysis of the fastest known algorithm for the push_swap problem.
<br>

## Support and Contributions

<p align="center">
If you find this repository helpful, please consider starring it to show your support. Your support is greatly appreciated!</p>

<p align="center">
<a href="https://ko-fi.com/fcorvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-ko-fi.svg"><alt=""></a>
<a href="https://github.com/sponsors/f-corvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-github.svg"><alt=""></a>

<br>

## Author

<p align="center"><a href="https://profile.intra.42.fr/users/fcorvaro"><img style="height:auto;" src="https://avatars.githubusercontent.com/u/102758065?v=4" width="100" height="100"alt=""></a>
<p align="center">
<a href="mailto:fcorvaro@student.42roma.it"><kbd>Email</kbd><alt=""></a>
<a href="https://github.com/f-corvaro"><kbd>Github</kbd><alt=""></a>
<a href="https://www.linkedin.com/in/f-corvaro/"><kbd>Linkedin</kbd><alt=""></a>
<a href="https://42born2code.slack.com/team/U050L8XAFLK"><kbd>Slack</kbd><alt=""></a>

<hr/>
