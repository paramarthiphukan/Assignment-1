#include<stdio.h>

int main()
{
    char input[1000];
    scanf("%s",input);
    int i=0;
    int check=0;
    int count=0;
    int idx1=-1,idx2=-1;
    while(input[i]!='\0')
    {
        if((input[i]>='A' && input[i]<='Z') || (input[i]>='a' && input[i]<='z') || (input[i]>='0' && input[i]<='9'))
            check=1;
        else if((input[i]=='.' || input[i]=='-'  || input[i]=='_' || input[i]=='@') && (i!=0 && input[i+1]!='\0'))
            check=1;
        else
        {
            check=-1;
            break;
        }
        if(input[i]=='@')
        {
            count++;
            idx1=i;
        }
        if(count>1)
        {
            check=-1;
            break;
        }
        if(input[i]=='.')
        {
            idx2=i;
        }
        i++;
    }
    if(idx2-idx1<2)
        check=-1;
    if(check==1)
        printf("Valid Email address\n");
    else
        printf("Invalid Email address\n");
} 
