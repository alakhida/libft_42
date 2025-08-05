# 📚 Libft - First C Library in 42 school

Welcome to **Libft**, the first project in the 42 Common Core curriculum!  
This project is about **recreating standard C library functions** from scratch — a great way to improve understanding of low-level programming, memory management, and writing clean, reusable code in C.

## 🚀 Project Overview

Libft is a **static C library** that implements a selection of functions from the C standard library (like `strlen`, `memset`, `strcpy`, etc.), along with some **additional helper functions** (like `ft_split`, `ft_itoa`, etc.).

This is a **mandatory foundational project** at 42 schools, meant to solidify your knowledge of pointers, memory, strings, and coding discipline.

## 🧠 What I Learned

- Writing a reusable C library
- Understanding how C standard functions work under the hood
- Memory management (malloc, free)
- Organizing code with headers and Makefiles

## ✅ Functions Implemented

### Part 1 – libc functions
- `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`
- `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`
- `ft_strncmp`, `ft_strnstr`, `ft_atoi`
- `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- `ft_toupper`, `ft_tolower`
- `ft_calloc`, `ft_strdup`

### Part 2 – Additional functions
- `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`
- `ft_itoa`, `ft_strmapi`, `ft_striteri`
- `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

## 🔧 How to Use

```bash
# Clone the repo
git clone https://github.com/alakhida/libft_42.git
cd libft

# Compile the library
make

# Use libft in your C project
gcc main.c -L. -lft
```

To clean up:
```bash
make clean      # Removes object files
make fclean     # Removes object files + libft.a
make re         # Recompiles everything
```

## 🛠 Tips for Success

- Test every function separately using your own `main.c`.
- Use `valgrind` to avoid memory leaks.
- Stick to the **42 coding style** (Norminette).
- Comment your code – future you will thank you!

---

## 📍 Status
🔳 Completed  


---


