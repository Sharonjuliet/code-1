#include<stdio.h>
int main(){
    int n,d,s=0;
    printf("enter the number \n");
    scanf("%d",&n);
    while(n!=0){
        d=n%10;
        s+=d;
        n=n/10;
    }
    printf("sum %d:",s);
    return 0;
}
