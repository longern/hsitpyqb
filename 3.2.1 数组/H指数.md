H指数是一种衡量论文作者影响力的指标：若作者发表的$n$篇论文中有$h$篇每篇至少被引$h$次，而其余论文每篇被引均小于或等于$h$次，则称$h$为该作者的H指数。现要求根据作者各篇论文的被引次数计算H指数。\
（1）若作者的被引次数依次为“0, 4, 12, 1, 5, 9, 3, 9”，则H指数为______。\
（2）按照上述要求，编写Python函数。请在划线处填入合适的代码。
```py
def calc_group_score(quoted):
    # 列表 quoted 中存储了被引次数
    n = len(quoted)
    c = [0] * (n + 1)
    for score in quoted:
        ___1___

    acc = 0
    for index in range(1, n + 1):
        ___2___
        acc += c[ci]
        if ___3___:
            return ci

quoted = [int(q) for q in input().split()]
print(calc_group_score(quoted))
```

<!-- testcases
5 2 7 11 8 6 5 1

5

0 4 12 1 5 9 3 9

4
-->
