# M-N
owner MINIMIMO

#：）呵 

#include <stdio.h>

main()
{
	int cnt;
	long long a;
	
	scanf("%d",&cnt);
	if (cnt>=1 && cnt<=500){
		for (;cnt>0;cnt--)
		{
			scanf("%lld",&a);
			printf("%ld\n",(a+1)/2);
		} 
	}	
}
