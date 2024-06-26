
<p align="center">
	<a href="#about">About</a> •
	<a href="#how-to-use">How to use</a> •
	<a href="#mandatory">Mandatory</a> •
	<a href="#bonus">Bonus</a> •
	<a href="#norminette">Norminette</a> •
	<a href="#license">License</a>
</p>

## ABOUT
The first project at 42, libft, involves learning how the standard functions of C programming work by writing them from scratch and creating a personal library. This project is vital as the library will be used in future assignments at 42.

If you're a 42 student, it's highly recommended that you go through the process of writing your own code and testing it yourself rather than copying and pasting code that you only partially understand. If you've successfully completed your piscine, there's no reason why you couldn't tackle this project on your own! Be patient and thorough.

<a href="https://github.com/MarouanDoulahiane/libft/blob/main/subject/libft.pdf">Click here</a> for the subject of this project.

## HOW TO USE
#### COMPILATION
#### 1º - Clone the repository
```bash
git clone git@github.com:MarouanDoulahiane/libft.git
```

#### 2º - Enter the project folder and run `make`
```bash
cd libft/libft
make
```

#### 3º - To use in your code, include the header
```c
#include "libft.h"
```

#### MAKEFILE RULES

`make` - Compile libft **mandatory** files.

`make bonus` - Compile libft **bonus** files.

`make all` - Compile **mandatory** + **bonus** files.

`make clean` - Delete all .o (object files) files.

`make fclean` - Delete all .o (object file) and .a (executable) files.

`make re` - Use rules `fclean` + `all`.

## MANDATORY
The mandatory functions in libft include both functions from the standard C library and other functions that are useful for character, string, and memory manipulation. These **34 mandatory functions** are essential to achieving a **grade of 100**.

#### Check and manipulate characters:

- [x] `ft_isalpha`
- [x] `ft_isdigit`
- [x] `ft_isalnum`
- [x] `ft_isascii`
- [x] `ft_toupper`
- [x] `ft_tolower`

#### Manipulate strings:

- [x] `ft_strlen`
- [x] `ft_strlcpy`
- [x] `ft_strlcat`
- [x] `ft_strchr`
- [x] `ft_strrchr`
- [x] `ft_strncmp`
- [x] `ft_strnstr`
- [x] `ft_substr`
- [x] `ft_strjoin`
- [x] `ft_strtrim`
- [x] `ft_split`
- [x] `ft_strmapi`
- [x] `ft_striteri`

#### Manipulate memory:

- [x] `ft_calloc`
- [x] `ft_memset`
- [x] `ft_bzero`
- [x] `ft_memcpy`
- [x] `ft_memmove`
- [x] `ft_memchr`
- [x] `ft_memcmp`
- [x] `ft_strdup`

#### Manipulate numbers:

- [x] `ft_atoi`
- [x] `ft_itoa`

#### Write to a file descriptor:

- [x] `ft_putchar_fd`
- [x] `ft_putstr_fd`
- [x] `ft_putendl_fd`
- [x] `ft_putnbr_fd`

## BONUS
The bonus functions in libft are focused on list manipulation and are worth an additional 25 towards the final grade. To achieve a **grade of 125**, **all 9 bonus functions and 34 mandatory functions** must be completed accurately.

- [x] `ft_lstnew`
- [x] `ft_lstadd_front`
- [x] `ft_lstsize`
- [x] `ft_lstlast`
- [x] `ft_lstadd_back`
- [x] `ft_lstdelone`
- [x] `ft_lstclear`
- [x] `ft_lstiter`
- [x] `ft_lstmap`

## NORMINETTE
At 42 School, it is expected that almost every project is written in accordance with the Norm, which is the coding standard of the school.

```
- No for, do...while, switch, case, goto, ternary operators and variable-length arrays are allowed
- Each function must be a maximum of 25 lines, not counting the function's curly brackets
- Each line must be at most 80 columns wide, comments included
- A function can take 4 named parameters maximum
- No assigns and declarations in the same line (unless static)
- You can't declare more than 5 variables per function
- ...
```

* [42 Norms](https://github.com/MarouanDoulahiane/MarouanDoulahiane/blob/main/1337/pdf/norm.pdf) - Information about 42 code norms. `PDF`
* [Norminette](https://github.com/42School/norminette) - Tool by 42, to respect the code norm. `GitHub`
* [42 Header](https://github.com/42Paris/42header) - 42 header for Vim. `GitHub`

## LICENSE
<p>
This work is published under the terms of <a href="https://github.com/MarouanDoulahiane/libft/blob/main/LICENSE.md">MIT LICENSE</a>.
</p>
