# ft_strcmp

This repository contains the implementation of the `ft_strcmp` function, a custom version of the standard `strcmp` function in C. The `ft_strcmp` function compares two strings character by character and determines if they are equal, or which one is greater based on the ASCII value of the characters.

## Overview

The function `ft_strcmp` takes two strings, `s1` and `s2`, as arguments and compares them lexicographically. The comparison is done using unsigned characters, so that `\200` is greater than `\0`.

### Function Prototype

```c
int ft_strcmp(char *s1, char *s2);
