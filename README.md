#include<stdio.h>
int main()
{
int n,i,j,temp=0;
int arr[3][3]={10,20,30,40,50,60,70,80,90};
for(i=0;i<3;i++)
{
for(j=0;j<3;j++)
{
    if(i%2==0) //even 0%2==0
{

        if(j%2==0)


           printf("*\t",arr[i][j]);
           else
            printf("%d\t",arr[i][j]);
    }
    if(i%2!=0)
    {
        printf("%d\t",arr[i][j]);
    }

}





printf("\n");

}
}
