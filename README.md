# matrix
#include <stdio.h>

int main() {
 int a[3][3],i,j,k,sum=0;
 int b[3][3],c[3][3];
 //printf("Number %d %d",i,j);
 
 for(i=0;i<3;i++){
     for(j=0;j<3;j++){
         printf("Number(%d,%d): ",i,j);
         scanf("%d",&a[i][j]);
        
     }
 }
 printf("\n\n");
 for(i=0;i<3;i++){
     for(j=0;j<3;j++){
         printf("Number(%d,%d): ",i,j);
         scanf("%d",&b[i][j]);
        
     }
 }
 printf("\n\n");
 printf("matrix 1 :\n");
 for(i=0;i<3;i++){
     for(j=0;j<3;j++){
         printf("%d\t",a[i][j]);
        
     }
     printf("\n");
   
     }
     printf("matrix 2 :\n");
 for(i=0;i<3;i++){
     for(j=0;j<3;j++){
         printf("%d\t",b[i][j]);
     }
     printf("\n");
     }
     
 for(i=0;i<3;i++){
     for(j=0;j<3;j++){
         c[i][j]=a[i][j]+b[i][j];
         
     }}
     printf("matrix 3:\n");
         for(i=0;i<3;i++){
     for(j=0;j<3;j++){ 
     
      printf("%d\t",c[i][j]);
     
     }
     printf("\n");
     }
     
     
     printf("matrix 4 :\n");
     
      for(i=0;i<3;i++){
     
     for(j=0;j<3;j++){ 
         sum=0;
     for(k=0;k<3;k++){
     sum=sum+a[i][k]*b[k][j];
     }
     printf("%d\t",sum);
     }
          printf("\n");
      }
 
     
 
     

 
 }
