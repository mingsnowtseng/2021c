# 2021c
這是我在資傳一甲的程式的專案倉庫

# 第02週

```C
#include <stdio.h>

int main()
{
    printf("Hello World" )
}
```
# 第03週  9/30
![week03-1](https://user-images.githubusercontent.com/91250404/135428288-b5cb675b-6c6f-4466-a946-475d07df7c53.PNG)
![week03-2](https://user-images.githubusercontent.com/91250404/135428297-621f9c20-56ee-4997-a6cb-a99e1c1087d8.PNG)
![week03-3](https://user-images.githubusercontent.com/91250404/135428302-5af2fdee-286f-43cf-afcc-86c60f3d1939.PNG)
![week03-4](https://user-images.githubusercontent.com/91250404/135428306-a8943a62-86df-4504-b805-8b24ee43e510.PNG)
![week03-5](https://user-images.githubusercontent.com/91250404/135428312-e706c11e-5437-4bee-8ed5-fb0aaec1022a.PNG)

# 第04週 10/7

```C
\\基本加減, 總格數(%格數d)
#include <stdio.h>
int main()
{
    int a=123,b=10;
    printf("%d\n",a+b);
    printf("%5d\n",a+b);
}

\\浮點數 (%f)
#include <stdio.h>
int main()
{
    ///int a,b;
    float  a=3.14159;
    double b=3.14159;
    printf("%f\n", a);
    printf("%.2f\n", a);
}
 
\\ 成績判斷 (if和else)
#include <stdio.h>
int main()
{
	int n;
	scanf("%d",&n);
	if(n>=90) printf("A+");
	else if(n>=80) printf("A");
	else if(n>=70) printf("B");
	else if(n>=60) printf("C");
	else printf("D");
}

\\ 另類成績判斷 (if 和 &&並且) 
#include <stdio.h>
int main()
{
	int n;
	scanf("%d", &n);
	if (n<=100 && n>=90) printf("A+");
	if (n<=89 && n>=80) printf("A");
	if (n<=79 && n>=70) printf("B");
	if (n<=69 && n>=60) printf("C");
	if (n<=59) printf("D");
}

# 第07週 10/7

#include <stdio.h>
int main()
{
	int a,b,c;
	scanf("%d%d%d",&a,&b,&c);
	if(a<=b && b<=c) printf("%d %d %d",a,b,c);
	else if (a<=c && c<=b) printf("%d %d %d",a,c,b);
	else if (b<=a && a<=c) printf("%d %d %d",b,a,c);
	else if (b<=c && c<=a) printf("%d %d %d",b,c,a);
	else if (c<=a && a<=b) printf("%d %d %d",c,a,b);
	else if (c<=b && b<=a) printf("%d %d %d",c,b,a);
}
