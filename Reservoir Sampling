#include <stdio.h>
#include <stdlib.h>
#include <time.h>
void reqk(int a[],int n)
{
    for (int i=0;i<n;i++)
        printf("%d\n",a[i]);
    printf("\n");
}
void req(int a[],int n,int k)
{
    int i;
    int res[k];
    for (i = 0; i < k; i++)
        res[i]=a[i];
    srand(time(0));
    for (;i<n;i++)
    {
        int j =rand()%i+1;
        if (j<k)
          res[j] = a[i];
    }

    reqk(res,k);
}
int main()
{
    int a[] = {1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50};
    int n = sizeof(a)/sizeof(a[0]);
    int k;
    scanf("%d",&k);
    req(a,n,k);
    return 0;
}
