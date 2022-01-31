# 来源：牛客网
# 计算A+B

## ①输入多组A+B

输入描述:
输入包括两个正整数a,b(1 <= a, b <= 1000),输入数据包括多组。
输出描述:
输出a+b的结果
```c
#include <stdio.h>
int main()
{
    int a,b;
    while (scanf("%d %d",&a,&b) !=EOF)
    {
        printf("%d\n",a+b);
    };
}
```
