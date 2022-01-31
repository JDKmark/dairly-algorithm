# 来源：牛客网
# 计算A+B
①输入描述:  
`输入包括两个正整数a,b(1 <= a, b <= 1000),输入数据包括多组。`  
```c
#include <stdio.h>
int main()
{
    int a,b;
    //while(~scanf("%d %d",&a,&b)){code}
    while (scanf("%d %d",&a,&b) !=EOF)
    {
        printf("%d\n",a+b);
    };
}
```
②输入描述:  
`输入第一行包括一个数据组数t(1 <= t <= 100)
接下来每行包括两个正整数a,b(1 <= a, b <= 1000)`  
```c
#include <stdio.h>
int main(void)
{
    int n, a, b;
    while(scanf("%d", &n) != EOF)
    {
        //while(n--0){code}
        for(int i=0; i<n; i++)
        {
            scanf("%d %d", &a, &b);
            printf("%d\n", a+b);
        }
    }
    return 0;
}
```

③输入描述:  
`输入包括两个正整数a,b(1 <= a, b <= 10^9),输入数据有多组, 如果输入为0 0则结束输入`
```c
#include "stdio.h"
int main(){
    int a,b;
    //while(~scanf("%d %d",&a,&b)){code}
    while (scanf("%d %d",&a,&b) !=EOF){
        if(a==0&&b==0) break;
        else{
            printf("%d\n",a+b);
        }
    }
    return 0;
}
```
④输入描述:
`输入数据有多组, 每行表示一组输入数据。
每行不定有n个整数，空格隔开。(1 <= n <= 100)。`
```c
#include<stdio.h>
int main()
{
    int n,num,sum=0;
    while(scanf("%d",&n)!=EOF)
    {
        sum=n;
        while(getchar()!='\n')
        {
           scanf("%d",&num);
           sum+=num;
        }
        printf("%d\n",sum);
    }
    return 0;/
}
```
