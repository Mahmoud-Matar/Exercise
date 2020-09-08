#include <KnapSack.h>
int KnapSack (int W,int wt[],int val[],int n)
{ if (n==0||W==0)
return0;
if(wt[n-1]>W)
return KnapSack (W,wt,val,n-1);
else 
return max(val[n-1]+KnapSack(W-wt[n-1],wt,val,n-1),KnapSack(W,Wt,val,n-t));
