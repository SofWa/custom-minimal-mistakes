---
title: "c언어 버블정렬"
author: SofWa
categories:
    - c
    - study
---
## c언어 버블정렬  

```c
/*
버블정렬
Created by SofWa
*/
#include <stdio.h>

int main(void)
{
    int list[5] = { 30, 40, 10, 50, 20 };
    int i = 0, j = 0, tmp = 0;

    for (i = 0; i < 5; ++i)
    {
        for (j = 0; j < 4 - i; ++j)
        {
            if (list[j] > list[j+1])
            {
                tmp = list[j];
                list[j] = list[j + 1];
                list[j + 1] = tmp;
            }
        }
    }

    for (i = 0; i < 5; ++i)
    {
        printf("%d\t", list[i]);
    }
    
    putchar('\n');
    return 0;
}
```