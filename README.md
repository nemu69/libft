<p align="center">
    <img alt="42-lyon" src="https://user-images.githubusercontent.com/45235527/106354618-6ec65a00-62f3-11eb-8688-ba9e0f4e77de.jpg" />
</p>

# libft

<img alt="Note" src="https://user-images.githubusercontent.com/45235527/96751780-e4a25780-13cd-11eb-9d06-aa687ff25143.png" width="250" height="200" />
  
### <strong>Description</strong>

The aim of this project is to code a C library regrouping usual functions that
you’ll be allowed to use in all your other projects.

<p align="center">
  <img alt="make" src="https://user-images.githubusercontent.com/45235527/104592712-eac36f80-566e-11eb-8713-aae03bff77c3.gif" />
</p>

# Regles

```
make (re, clean, fclean, bonus)
```


# II.2 Part 1 - Libc Functions

*In this first part, you must re-code a set of the libc functions, as defined in their
man. Your functions will need to present the same prototype and behaviors as the originals. Your functions’ names must be prefixed by “ft_”. For instance strlen becomes
ft_strlen.*

You must re-code the following functions. These function do not need any external
functions:

- `memset`
- `bzero`
- `memcpy`
- `memccpy`
- `memmove`
- `memchr`
- `memcmp`
- `strlen`
- `isalpha`
- `isdigit`
- `isalnum`
- `isascii`
- `isprint`
- `toupper`
- `tolower`
- `strchr`
- `strrchr`
- `strncmp`
- `strlcpy`
- `strlcat`
- `strnstr`
- `atoi`


You must also re-code the following functions, using the function “malloc” :

- `calloc`
- `strdup`


# II.3 Part 2 - Fonctions supplémentaires

In this second part, you must code a set of functions that are either not included in the
libc, or included in a different form. Some of these functions can be useful to write Part
1’s functions.

- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- `ft_strmapi`
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`


# Partie bonus

If you successfully completed the mandatory part, you’ll enjoy taking it further. You can
see this last section as Bonus Points.

Having functions to manipulate memory and strings is very useful, but you’ll soon
discover that having functions to manipulate lists is even more useful.


```
typedef struct s_list
{
void *content;
struct s_list *next;
} t_list;
```

Here is a description of the fields of the t_list struct:

- `content` : The data contained in the element. The void * allows to store any kind of data
- `next` : : The next element’s address or NULL if it’s the last element.

The following functions will allow you to easily use your lists.
- `ft_lstnew`
- `ft_lstadd_front`
- `ft_lstsize`
- `ft_lstlast`
- `ft_lstadd_back`
- `ft_lstdelone`
- `ft_lstclear`
- `ft_lstiter`
- `ft_lstmap`
