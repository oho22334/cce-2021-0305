# cce-2021-0305

## 讀入整數反序列印
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

## A的B次方函數
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

## 漸增數列相加
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




##  均標與前標計算
```C
#include <stdio.h>
int main()
{
	int N;
	scanf("%d",&N);
	
	int sum=0;
	int a[1000];
	for(int i=0;i<N;i++){
		scanf("%d",&a[i]);
		sum+=a[i];
		}
	float average;
	average=(float)sum/N;
	float r=0;
	float sumTop=0;
	for(int i=0;i<N;i++){
		if(a[i]>=average){
			sumTop+=a[i];
			r++;
			}
		}
	float averageTop;
	averageTop=(float)sumTop/r;
	printf("均標:%.1f\n",average);
	printf("前標:%.1f\n",averageTop);
}
	

```
## 判別正方形

```C
#include <stdio.h>
int main ()
{
	int a,b;
	scanf("%d%d",&a,&b);
	printf("Enter two numbers: ");
	if(a==b)
	printf(" It is a square ");
	else
	printf(" It is not a square ");
}
```

## 2進位轉10進位


```C

#include <stdio.h>
int main ()
{
	int a,b;
	scanf("%d%d",&a,&b);
	printf("Enter two numbers: ");
	if(a==b)
	printf(" It is a square ");
	else
	printf(" It is not a square ");
}
```



