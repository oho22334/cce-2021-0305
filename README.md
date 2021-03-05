# cce-2021-0305

##讀入整數反序列印
```C
#include <stdio.h>
int main ()
{
	int a[11]; int n=0;
	for(int i=0;i<10;i++){
	scanf("%d",&a[i]);
	if(a[i]==0)
	break;
	n++;

}
	for(int i=n-1; i>=0 ;i--){
	
	printf("%d ",a[i]);
}
	printf("\n",n);
}
```

##A的B次方函數
```C
#include <stdio.h>
int main ()
{
	int a[11]; int n=0;
	for(int i=0;i<10;i++){
	scanf("%d",&a[i]);
	if(a[i]==0)
	break;
	n++;

}
	for(int i=n-1; i>=0 ;i--){
	
	printf("%d ",a[i]);
}
	printf("\n",n);
}
```

##漸增數列相加
```C
#include <stdio.h>
int main ()
{
	int n, ans=0;
	scanf("%d",&n);
	for(int i=1;i<n;i++){
		ans+=i*(i+1);
	}
	printf("%d\n",ans);
}
```
