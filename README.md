include<stdio.h>
int main(){
int n, i, j, isprime;
printf("25331a05d7\n");
 printf("the prime numbers from 1 to 100:");

for(i = 2; i <= 100; i++){
   isprime = 1;
   for(j = 2;j <= i/2; j++){
    if(i % j == 0){
   isprime = 0;
   }
}  
  if(isprime == 1){
   printf(" %d ", i);
}
}
return 0;
}
