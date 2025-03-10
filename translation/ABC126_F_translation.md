## 题意

给定 $M,K$ 构造一个长为 $2^{M+1}$ 的序列 $a$ 满足：
- $0$ 至 $2^{M}-1$ 的所有整数每个都在 $a$ 中出现且恰好出现 $2$ 次。
- 若 $a_i=a_j$，那么 $\displaystyle\bigoplus_{x=i}^j a_x=K$。

$\bigoplus$ 表示按位异或。

若无法构造，输出 `-1`。

## 数据范围

- $0\le M\le 17$。
- $0\le K\le 10^9$

## 输入格式

一行两个整数 $M,K$。

## 输出格式

一行 $2^{M+1}$ 个整数，答案。

## 样例输入 1

```
1 0
```

## 样例输出 1

```
0 0 1 1
```


## 样例输入 2

```
1 1
```

## 样例输出 2

```
-1
```

## 样例输入 3

```
5 58
```

## 样例输出 3

```
-1
```
