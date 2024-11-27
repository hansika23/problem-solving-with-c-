#include<studio.h>
void main()
{
        int p, n;
        float r, si;
        clrsrc();
        printf("enter value of p:");
        scanf("%d",&p);
        printf("enter the value of n:");
        scanf("%d",&n);
        printf("enter the value of r:");
        scanf("%f",&r);
        si=p*n*r/100;
        printf("\n simple interest %f\n",si);
        getch();
        return 0;
}
