# Diamond-pattern-with-stars
#include<stdio.h>

int main (){
   int n = 5;
//uper part 
   for(int i= 1;i <= 5; i++){
       for(int l = 1; l <= n-i; l++){
        printf(" ");
       }
       for(int j = 1;j <= 2*i-1; j++){
        printf("*");
       }
       printf("\n");
     }
    // down part 
     
    for (int i = n-1; i >= 1;i--){
        for(int l = 1; l <= n-i; l++){
            printf(" ");
        }
        for(int j = 1; j <= 2*i-1;j++){
            printf("*");
        }
        printf("\n");
    }


    return 0;
}
