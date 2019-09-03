# sample
sample
 #include<stdio.h>
 {       int a[10],i,N,K;
   printf("enter k");
   scanf("%d",&K);
   printf("enter N");
   scanf("%d",&N);
  for(i=0:i<N;i++)
  {
   scanf("%d",&a[i]);
  }
 printf("array elements are");
 for(i=0;i<N;i++)
 printf("%d",a[i]);
 if(a[i]>=K)
  {
   i=0;
  while(i<N)
  {
   a[i]=a[i]+1;
  i++;
  }
  }
 else
 {
printf("array is");
 for(i=0;i<N;i++)
printf("%d",a[i]);
 }
 }
