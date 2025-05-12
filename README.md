# Libft

## Description
Libft is my first project at 42 School, consisting of recoding various standard C library functions, as well as other utility functions that will be useful throughout my curriculum.

## Table of Contents
- Features
- Installation
- Usage
- Functions
- Bonus Functions

## Features
- Reimplementation of useful C standard library functions
- Additional utility functions
- Bonus linked list manipulation functions

## Installation
Clone the repository and compile the library:

```bash
git clone https://github.com/matteo-genovese/libft.git
cd libft
make
```

To include bonus functions:
```bash
make bonus
```

To clean object files:
```bash
make clean
```

To clean everything (objects and library):
```bash
make fclean
```

To recompile:
```bash
make re
```

## Usage
Include the header in your C files:
```c
#include "libft.h"
```

Compile your program with the library:
```bash
gcc -Wall -Wextra -Werror your_program.c -L. -lft -o your_program
```

## Functions

### Character checking
- [`ft_isalpha`](libft/ft_isalpha.c ) - Check if character is alphabetic
- [`ft_isdigit`](libft/ft_isdigit.c ) - Check if character is a digit
- [`ft_isalnum`](libft/ft_isalnum.c ) - Check if character is alphanumeric
- [`ft_isascii`](libft/ft_isascii.c ) - Check if character is ASCII
- [`ft_isprint`](libft/ft_isprint.c ) - Check if character is printable
- [`ft_toupper`](libft/ft_toupper.c ) - Convert character to uppercase
- [`ft_tolower`](libft/ft_tolower.c ) - Convert character to lowercase

### String manipulation
- [`ft_strlen`](libft/ft_strlen.c ) - Get string length
- [`ft_strlcpy`](libft/ft_strlcpy.c ) - Copy string with size limitation
- [`ft_strlcat`](libft/ft_strlcat.c ) - Concatenate strings with size limitation
- [`ft_strchr`](libft/ft_strchr.c ) - Locate character in string (first occurrence)
- [`ft_strrchr`](libft/ft_strrchr.c ) - Locate character in string (last occurrence)
- [`ft_strncmp`](libft/ft_strncmp.c ) - Compare strings up to n characters
- [`ft_strnstr`](libft/ft_strnstr.c ) - Locate substring in a string
- [`ft_strdup`](libft/ft_strdup.c ) - Duplicate a string
- [`ft_substr`](libft/ft_substr.c ) - Extract substring from string
- [`ft_strjoin`](libft/ft_strjoin.c ) - Concatenate two strings
- [`ft_strtrim`](libft/ft_strtrim.c ) - Trim characters from beginning and end of string
- [`ft_split`](libft/ft_split.c ) - Split string into array of strings
- [`ft_strmapi`](libft/ft_strmapi.c ) - Apply function to each character with index
- [`ft_striteri`](libft/ft_striteri.c ) - Apply function to each character with index

### Memory manipulation
- [`ft_memset`](libft/ft_memset.c ) - Fill memory with a constant byte
- [`ft_bzero`](libft/ft_bzero.c ) - Zero out a byte string
- [`ft_memcpy`](libft/ft_memcpy.c ) - Copy memory area
- [`ft_memmove`](libft/ft_memmove.c ) - Copy memory area (handles overlap)
- [`ft_memchr`](libft/ft_memchr.c ) - Locate byte in byte string
- [`ft_memcmp`](libft/ft_memcmp.c ) - Compare byte string
- [`ft_calloc`](libft/ft_calloc.c ) - Allocate and zero memory

### Conversion
- [`ft_atoi`](libft/ft_atoi.c ) - Convert ASCII string to integer
- [`ft_itoa`](libft/ft_itoa.c ) - Convert integer to ASCII string

### File descriptors
- [`ft_putchar_fd`](libft/ft_putchar_fd.c ) - Output character to file descriptor
- [`ft_putstr_fd`](libft/ft_putstr_fd.c ) - Output string to file descriptor
- [`ft_putendl_fd`](libft/ft_putendl_fd.c ) - Output string with newline to file descriptor
- [`ft_putnbr_fd`](libft/ft_putnbr_fd.c ) - Output number to file descriptor

## Bonus Functions

### Linked list manipulation
- [`ft_lstnew`](libft/ft_lstnew.c ) - Create new list element
- [`ft_lstadd_front`](libft/ft_lstadd_front.c ) - Add element at beginning of list
- [`ft_lstsize`](libft/ft_lstsize.c ) - Count elements in a list
- [`ft_lstlast`](libft/ft_lstlast.c ) - Get last element of list
- [`ft_lstadd_back`](libft/ft_lstadd_back.c ) - Add element at end of list
- [`ft_lstdelone`](libft/ft_lstdelone.c ) - Delete element from list
- [`ft_lstclear`](libft/ft_lstclear.c ) - Delete sequence of elements from list
- [`ft_lstiter`](libft/ft_lstiter.c ) - Apply function to content of all list elements
- [`ft_lstmap`](libft/ft_lstmap.c ) - Apply function to content of all list elements into new list

## Author
- Matteo Genovese ([mgenoves](https://profile-v3.intra.42.fr/users/mgenoves))

<img width="998" alt="Screenshot 2024-02-20 at 14 45 13" src="https://github.com/matteo-genovese/libft/assets/67902487/70cbe00c-bfbe-4a5a-852a-a9c453d78795">
