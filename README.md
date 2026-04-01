# 25331a05d8-matadd
#include<stdio.h>
int main(){
int a[10][10],b[10][10],c[10][10];
int i,j,rows,cols;
printf("enter no of rows and cols:");
scanf("%d%d",&rows,&cols);
printf("enter first matrix:");
for(i=0;i<rows;i++){
for(j=0;j<cols;j++){
scanf("%d",&a[i][j]);
}
}
printf("enter second matrix:");
for(i=0;i<rows;i++){
for(j=0;j<cols;j++){
scanf("%d",&b[i][j]);
}
}
for(i=0;i<rows;i++){
for(j=0;j<cols;j++){
c[i][j]=a[i][j]+b[i][j];
}
}
printf("sum of matrices:\n");
for(i=0;i<rows;i++){
for(j=0;j<cols;j++){
printf("%d",c[i][j]);
}
printf("\n");
}
return 0;
}
