# function
#include <stdio.h>
int goru(int a[],int n){   // using the random name for as a function name 
int h = a[0],i,f = a[0];

    for(i=0;i<n;i++){
        if(a[i]<h){
            h = a[i];
        }
    }
    for(i=0;i<n;i++){
        if(a[i]>f){
            f = a[i];
        }
    }
    printf("%d\n",f); // learn how retunrn and function call work
    return h;
}


int main(){
int a[] = {1,2,3,4,5,30},n=6;
int b[] = {10,2,43,4,5,56,21,6},k=8;
printf("%d\n",goru(a,n));
printf("%d",goru(b,k));
return 0;
}
