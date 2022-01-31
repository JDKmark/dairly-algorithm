# 来源：牛客网
# 计算A+B
输入描述:  
`输入包括两个正整数a,b(1 <= a, b <= 1000),输入数据包括多组。`  
输出描述:  
`输出a+b的结果`
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
输入描述:  
`输入第一行包括一个数据组数t(1 <= t <= 100)
接下来每行包括两个正整数a,b(1 <= a, b <= 1000)`  
输出描述:  
`输出a+b的结果`  
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
