#include<stdio.h>

void main(){
    int num,count;
    printf("Enter the number:");
    scanf("%d",&num);
    while(num>0){
        if(num&1){
            count++;
        }
        num=num>>1;
    }
    printf("The number of 1's in given number is %d",count);
}
