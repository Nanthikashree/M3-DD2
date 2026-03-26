# M3-DD2
AIM:
Create a C program  to generate the Fibonacci series for the given input.
PROGRAM:
```
#include <stdio.h>
int main()
{
    int n,a=0,b=1,temp,i;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        printf("%d ",a);
        temp=a+b;
        a=b;
        b=temp;
    }
}
```
OUTPUT:
<img width="776" height="331" alt="image" src="https://github.com/user-attachments/assets/6bce7e1c-6fa1-4931-bcc0-eb11262c7234" />
RESULT:
Thus the code run successfully!

