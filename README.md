# pull-request

#include <stdio.h>

int main()
{
    int i, age;
    for ( i = 0; i < 10; i++)
    {
        printf("%d\nEnter your age\n", i);
        scanf("%d", &age);
        if (age>10)
        {
            break;
        }
        /*if (age>10)
        {
            continue;
            printf("GJH\n");
        }*/
        if (age>10)
        {
            continue;  
        }
        printf("Try to print\n");
        }
    return 0;
}

#include <stdio.h>

int main()
{
    int num, index = 0;
    printf("Enter a number\n");
    scanf("%d", &num);
    do
    {
        printf("%d\n", index + 1);
        index = index + 1;
    } while (index < num);
    return 0;
}

# include <stdio.h>

int main(){
    printf("Hello I am learning C\n");
    return 0;
}

#include<stdio.h>

int main()
{
    int i=0;
    for ( i = 0; i < 10; i++)
    {
        printf("%d\n", i);
    }
    return 0;
}
