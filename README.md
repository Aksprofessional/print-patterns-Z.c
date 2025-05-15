# print-patterns-Z.c
// Online C compiler to print pattern  ZYXWV ZYXW ZYX ZY Z
// Online C compiler to print pattern 

ZYXWV
ZYXW
ZYX
ZY
Z

#include <stdio.h>

int main() {
    int i,j;
    for(i=0;i<5;i++)
    {
        for(j=0;j<=4-i;++j)
        printf("%c",90-j);
        printf("\n");
    }
    return 0;
}
