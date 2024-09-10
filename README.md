#include <stdio.h>
int fact(int b){
    if (b==1 || b==0){
        return 1;
    }
    return fact(b-1)*b;
}
int main() {
    int a;
    printf("enter the value of a = ");
    scanf("%d",&a);
    printf("the factorial of %d is %d",a,fact(a));

    return 0;
}
