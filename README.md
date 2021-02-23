# structure
#include<stdio.h>
struct emp
{
   char name[10];
   int empno;
   char department_name[10];
   int salary;
}entry[20];
int main()
{
   int i;
   for(i=0;i<20;i++)
   {
      printf("enter %d\n",i+1);
      printf("name\t\t:");
      scanf("%s",&entry[i].name);
      printf("empno.:\t\t");
      scanf("%d",&entry[i].empno);
      printf("department_name:\t);
      scanf("%s",&entry[i].department_name);
      printf("salary\t\t:");
      scanf("%d",&entry[i].salary);
   }
   printf("\n___________________________________________________________\n");
   printf("\tname\t\tempno.\t\tdepartment_name\tsalary\n");
   for(i=0;i<n;i++)
   {
      printf("%d\t%s\t\t%d\t\t%s\t\t\t%d\t\t\n",i+1,
              entry[i].name,
              entry[i].empno.,
              entry[i].department_name,
              entry[i].salary);
   }
   printf("\n____________________________________________________________\n");
   return 0;
}   
   
