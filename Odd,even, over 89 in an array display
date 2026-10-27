#include <stdio.h>
void readArray(int arr[], int size);
void oddNumbers(int arr[], int size);
int checkPositive(int arr[], int size, int index);
void evenNum(int arr[], int size);
void bigNum(int arr[], int size);

int main(){
 int size=10;
 int arr[size];
 readArray(arr,size);
 oddNumbers(arr,size);
return 0;

}
void readArray(int arr[], int size){
 for(int i=0; i<size; i++){
  printf("enter num %d\n", i+1);
  scanf("%d", &arr[i]);
 }
  }

void oddNumbers(int arr[], int size){
 printf("oddNumbers : ");
 for(int i=0; i<size; i++){
  if (checkPositive(arr,size,i)==0){
  continue;
  }
  else {
  if(arr[i]%2!=0){
   printf("%d ", arr[i]);
  }
  else {
  continue;
  }
}
   }
   printf("\n");
   evenNum(arr,size);
}
void evenNum(int arr[], int size){
 printf("even numbers :");
 for(int i=0; i<size; i++){
  
  if(checkPositive(arr,size,i)==0){
  continue;
  }
  else {
  if(arr[i]%2==0){
  printf("%d ", arr[i]);
  }
  else {
  continue;
  }
   }
    }
    printf("\n");
    bigNum(arr,size);
     }
void bigNum(int arr[], int size){
printf("number over 89 :");
 for(int i=0; i<size; i++){
  if(checkPositive(arr,size,i)==0){
  continue;
  }
  else {
  if(arr[i]>89){
  printf("%d ", arr[i]);
  }
  else {
  continue;
  }
      }
     }
     printf("\n");
    }
       
int checkPositive(int arr[], int size, int index){
  if(arr[index]<0){
  return 0;
  }
  else {
  return 1;
  }
}

    
