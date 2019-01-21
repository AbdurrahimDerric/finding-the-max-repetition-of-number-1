#include <stdio.h>
#include <time.h>
int main ()
{
     int i =0,j,n =15;
     int key=0, numkey=0, indis ,bitis;
     //key = repetition, numkey = max repetition, indis = index , bitis = ending index of this sequence of ones
     int dizi[n];
     srand(time(NULL));
     for (i=0;i<n;i++)
       {
           dizi[i]=rand() % 2;
           printf(" %d", dizi[i]);
       }
       printf("\n\n");
       
     for (i=0;i<n;i++)
       {
           if (dizi[i]==1)
             {
                key++;
            }
           else
            {
               key = 0;

            }
            if (key> numkey)
                {
                     numkey=key;
                     indis =i-key;
                     bitis = i;
               }
       }
       
       printf (" indis : %d, uzunluk %d , bitis %d", indis,numkey,bitis);
}
