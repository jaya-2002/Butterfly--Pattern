#include<stdio.h>
int main()
{
	int i,n,j;
	printf("Enter n:");
	scanf("%d",&n);
    
	for(i=1;i<=n;i++)
	{
		for(j=1;j<=i;j++)
			printf("%d",j);
		for(j=2;j<=2*(n-i);j++)
			printf(" ");
		for(j=i;j>=1;j--)
		 {  if(i==n)
		   {i++;
		       continue;
		   }
		  printf("%d",j);
		  
		 }
			
    		  printf("\n");
		
	}
	 
        
	for(i=n-1;i>=1;i--)
	{
		for(j=1;j<=i;j++)
			printf("%d",j);
		for(j=2;j<=2*(n-i);j++)
			printf(" ");
			
			
			
		for(j=i;j>=1;j--)
			printf("%d",j);
		printf("\n");
		
	}
	return 0;
}


