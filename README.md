# 42_libft
libft project in 42

A custom implementation of the standard C library functions, written entirely from scratch. This library serves as a foundational project for mastering C programming and understanding low-level programming concepts. It includes common utility functions for string manipulation, memory management, list handling, and more.

---

## Features

- **String Functions**: Custom implementations of `strlen`, `strchr`, `strdup`, `strjoin`, `strtrim`, and more.
- **Memory Management**: Functions like `memset`, `memcpy`, `calloc`, and `bzero` for efficient memory handling.
- **Character Checks**: Includes functions like `isalnum`, `isalpha`, `isdigit`, `isascii`, `isprint`, and their counterparts for case conversion (`toupper`, `tolower`).
- **Linked List Utilities**: Comprehensive linked list operations such as `lstadd_front`, `lstadd_back`, `lstclear`, `lstdelone`, `lstsize`, and more (in the bonus files).
- **Utility Functions**: Additional helper functions like `itoa`, `atoi`, `split`, and more.

---

## Tech Stack

- **Language**: C
- **Build System**: Makefile for compilation.

---

## Files Overview

### Core Library Files
These files implement various standard C library functions:

- `ft_atoi.c`: Convert a string to an integer.
- `ft_bzero.c`: Set a block of memory to zero.
- `ft_calloc.c`: Allocate and initialize memory.
- `ft_isalnum.c`: Check if a character is alphanumeric.
- `ft_isalpha.c`: Check if a character is alphabetic.
- `ft_isascii.c`: Check if a character is part of the ASCII set.
- `ft_isdigit.c`: Check if a character is numeric.
- `ft_isprint.c`: Check if a character is printable.
- `ft_itoa.c`: Convert an integer to a string.
- `ft_memchr.c`: Locate a byte in a block of memory.
- `ft_memcmp.c`: Compare two blocks of memory.
- `ft_memcpy.c`: Copy a block of memory.
- `ft_memmove.c`: Move a block of memory.
- `ft_memset.c`: Fill a block of memory with a specific value.
- `ft_putchar_fd.c`: Output a character to a file descriptor.
- `ft_putendl_fd.c`: Output a string with a newline to a file descriptor.
- `ft_putnbr_fd.c`: Output a number to a file descriptor.
- `ft_putstr_fd.c`: Output a string to a file descriptor.
- `ft_split.c`: Split a string into an array using a delimiter.
- `ft_strchr.c`: Locate the first occurrence of a character in a string.
- `ft_strdup.c`: Duplicate a string.
- `ft_striteri.c`: Apply a function to each character of a string (with index).
- `ft_strjoin.c`: Concatenate two strings.
- `ft_strlcat.c`: Concatenate strings with size constraints.
- `ft_strlcpy.c`: Copy strings with size constraints.
- `ft_strlen.c`: Calculate the length of a string.
- `ft_strmapi.c`: Create a new string by applying a function to each character.
- `ft_strncmp.c`: Compare two strings up to a specified number of characters.
- `ft_strnstr.c`: Locate a substring in a string (with length limit).
- `ft_strrchr.c`: Locate the last occurrence of a character in a string.
- `ft_strtrim.c`: Trim characters from the beginning and end of a string.
- `ft_substr.c`: Extract a substring from a string.
- `ft_tolower.c`: Convert a character to lowercase.
- `ft_toupper.c`: Convert a character to uppercase.


### Linked List (Bonus)
- `ft_lstadd_front_bonus.c`: Add a new element to the start of a linked list.
- `ft_lstsize_bonus.c`: Count the number of elements in a linked list.
- `ft_lstclear_bonus.c`: Free an entire linked list.

### Header File
- `libft.h`: Contains function prototypes and necessary includes.

---
## Usage

### Cloning the Repository
To clone the repository, use the following commands:

```bash
git clone https://github.com/PabloXOC/42_minishell.git libft
cd libft
```

### Building the Library
Run the following command to compile the library:

```bash
make
```

### Cleaning Up
Use the following commands for cleanup:

- `make clean`: Remove object files.
- `make fclean`: Remove object files and the compiled library.
- `make re`: Rebuild the library from scratch.
