# Libft

> [!IMPORTANT]
> None of my code is publicly available here, but if you're a recruiter, I'd be happy to share it with you upon request.

<p align="center">
  <img width="317" height="268" alt="Screenshot from 2025-07-23 08-57-06" src="https://github.com/user-attachments/assets/bfae2c73-7a26-403d-acda-06b6cd9f967a" />
</p>

***Libft*** is one of the first core projects at 42, where I had to re-implement a selection of functions from the standard C library entirely from scratch. The goal is to build a personal library of essential tools in pure C, without relying on external code.

During this project, I developed functions for:
* Memory manipulation (`memset`, `memcpy`, `calloc`, etc.)
* String handling (`strdup`, `strjoin`, `substr`, etc.)
* Character checks and transformations (`isalpha`, `isdigit`, `toupper`, etc.)
* Number conversion (`atoi`)
* Writing to file descriptors (`write`, `putchar_fd`, etc.)

For the bonus part, I implemented a series of linked list (chained list) functions, such as:
* Creating and adding nodes (`ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back`)
* Iterating through the list (`ft_lstiter`)
* Mapping data (`ft_lstmap`)
* Deleting nodes or clearing the entire list (`ft_lstdelone`, `ft_lstclear`)
This part significantly improved my understanding of dynamic memory, pointers, and how data structures are built and managed in low-level programming.

What I learned:
* Writing clean, modular, and efficient code
* Managing memory manually in C (including avoiding leaks)
* Implementing fundamental data structures from scratch
* Thinking carefully about edge cases and writing robust tests

Libft gave me a strong foundation in C programming and taught me the importance of building reliable, reusable code from the ground up.
