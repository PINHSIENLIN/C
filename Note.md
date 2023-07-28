---
title: "C++ Note"
author: "Alvin, Lin"
date: "2023-07-27"
date-format: full
format:
   html:
     code-fold: show
     theme: flatly
     embed-resources: true
toc: true
toc-depth: 3
toc-location: left
execute:
  warning: false 
  eval: false
  keep-md: true
---



# Pointer

::: {.cell}

```{.r .cell-code}
#include<stdio.h>
#include<stdlib.h>
# int has 4 bytes
# Pointer has 4 bytes or 8 bytes
int main(){
  int i,k;
  int *ptr;
  # int *ptr = (int*)10;
  ptr = &i;
  printf("name\taddr\tvalue\n");
  printf(" i\t%d\t%d\n", &i, i);
  printf(" k\t%d\t%d\n", &k, k);
  printf(" ptr\t%d\t%d\n", &ptr, ptr);
  printf(" *ptr\t%d\t%d\n", &*ptr, ptr);
  
   k = *ptr(i of value);
   printf(" k\t%d\t%d\n", &k, k);
}
```
:::
