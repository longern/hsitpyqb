将正整数n转换为对应的k进制字符串表示。

```py
n = int(input())  # 输入一个正整数n
k = int(input())  # 输入转换的进制k，不大于36
# 将正整数n转换为对应的k进制字符串表示
# 超过10进制的用小写字母表示
res = ""
while n != 0:
    t = n % k
    ___1___
    if t < 10:
        res = str(t) + res
    else:
        ___2___
print(res)
```

例如n和k分别为
```input
31
16
```
时，输出为
```output
1f
```

<!-- testcases
235
2

11101011

52641
16

cda1
--!>
