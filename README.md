# Libft

## Project Overview
Libft is a custom C library that implements essential functions from the standard C library (`libc`) along with additional useful utilities. This project aims to deepen your understanding of fundamental C functions by recreating them, providing a reliable set of tools for future projects.

## Features
- Implementation of standard `libc` functions (e.g., `ft_strlen`, `ft_memcpy`, `ft_strncmp`, etc.).
- Additional utility functions for string manipulation and memory management.
- Custom linked list functions for handling dynamic data structures.
- Makefile for compilation and automation.

## Directory Structure
```
./
├── Makefile
├── libft.h
├── ft_*.c
```

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/ElmehdiBennix/Libft_42.git
   cd libft
   ```
2. Compile the library:
   ```sh
   make
   ```
3. Use `libft.a` in your projects:
   ```sh
   gcc -Wall -Wextra -Werror your_file.c -L. -lft -o your_program
   ```

## Mandatory Functions
- Standard `libc` functions prefixed with `ft_`:
  - `ft_strlen`, `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`
  - `ft_strlcpy`, `ft_strlcat`, `ft_toupper`, `ft_tolower`
  - `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_memchr`, `ft_memcmp`
  - `ft_strnstr`, `ft_atoi`, `ft_calloc`, `ft_strdup`

## Additional Functions
- `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_itoa`
- `ft_strmapi`, `ft_striteri`, `ft_putchar_fd`, `ft_putstr_fd`
- `ft_putendl_fd`, `ft_putnbr_fd`

## Bonus Functions
- Linked list manipulation functions:
  - `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`
  - `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

## Makefile Targets
- `make`: Compiles `libft.a`
- `make clean`: Removes object files
- `make fclean`: Removes object files and `libft.a`
- `make re`: Cleans and recompiles the library

## Notes
- All functions follow the `norminette` standard.
- Memory leaks are strictly avoided.
- The library is built using `ar` (no `libtool` allowed).
