#include<stdio.h>

int main()
{
    char input[1000];
    printf("Enter the value\n");
    scanf("%s",input);
    int i=0;
    int check1=0,check2=0;
    while(input[i]!='\0')
    {
        if(input[i]=='.')
        {
            check1++;
            if(input[i+1]!='\0')
            check2=1;
        }
        i++;
    }
    if(check1==1 && check2==1)
    printf("Valid\n");
    else
    printf("Invalid\n");
}
