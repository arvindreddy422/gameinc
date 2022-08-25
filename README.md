# gameinc
#include"stdio.h" 
#include"stdlib.h" 
#include"time.h" 
int main() 
{     
     int num,guess,noofattempts=1;     
     srand(time(0));     
     num=rand()%100+1;     
     printf("please guess a number in my memory(1-100)\n");     
     do{         
          printf("enter a number you guess : ");         
          scanf("%d",&amp;guess);         
          if(guess&lt;num)           
              printf("enter higher number please\n");         
          else if(guess>num)           
              printf("enter lower number please\n");         
          else            
              printf("\twelldone\nyou guess %d correct number ,in %d times",guess,noofattempts);       
          noofattempts++;      
        }while(num!=guess);     
    return 0;
}
aravind
yrsuraj
