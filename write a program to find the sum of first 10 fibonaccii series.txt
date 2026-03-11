#include <stdio.h>
int main()
{
    int a = 0, b = 1, c, i = 1, sum = 0;
    sum = a + b;
while(i <= 8)
    {
        c = a + b;
        sum = sum + c;
        a = b;
        b = c;
        i++;
    }
printf("Sum of first 10 Fibonacci numbers = %d", sum);
return 0;
}
