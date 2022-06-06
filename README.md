# heart_pattern
#include<stdio.h>

int main()

{

    int n=10,i,j,k,l;

    for(i=0;i<n/2;i++){

        for(l=n/2-i;l>1;l--){

        printf(" ");

        }

        for(j=0;j<=i;j++){

        printf("*");

        }

        for(j=0;j<=i-1;j++){

        printf("*");

        }

        int space=n-2*i;

        for(k=1;k<space;k++){

        printf(" ");

        } 

        for(j=0;j<=i;j++){

        printf("*");

        }

        for(j=0;j<=i-1;j++){

        printf("*");

        }

        printf("\n");

        

    }

    for(i=0;i<n;i++){

        for(j=0;j<i;j++){

        printf(" ");

        }

        for(k=n-i;k>=1;k--){

        printf("*");

        }

        for(l=n-i;l>=1;l--){

        printf("*");

        }

    printf("\n");

    }

    

    return 0;

}
