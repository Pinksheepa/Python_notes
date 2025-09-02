[toc]

# 前言

想要系统性地整理Python的知识:watermelon:
[跟着廖雪峰学](https://liaoxuefeng.com/books/python/history/index.html)

---

# Python基础

## 数据类型
| 数据类型 |                                    说明                                    |
| :------: | :------------------------------------------------------------------------: |
|   整数   |                           -1，0xffff，1_000_000                            |
|  浮点数  |                              0.1，2e-1（0.2）                              |
|  字符串  | 'xy'(表示x，y)，转义符号\ <br> Python允许用r''表示''内部的字符串默认不转义 |
|  布尔值  |                     True、False，可and \ or \ not运算                      |
|   空值   |                                    None                                    |
| **变量** |                             **用“=”动态赋值**                              |
|   常量   |                          通常大写表示，本质为变量                          |

## 字符串

- 字符串部分，从python3.6开始，可以用f-string格式化
  此外介绍.format格式化
    ```
    person = 'kk'
    
    classic: 
    print("Hello, my %s" % person)
    
    f-string:
    print(f"Hello, my {person}")
    
    .format:
    "{0} be nimble, {0} be quick, {0} jump over the {1}".format("Jack", "candle stick")
    # => "Jack be nimble, Jack be quick, Jack jump over the candle stick"
    # 如果不想数参数，可以用关键字
    "{name} wants to eat {food}".format(name="Bob", food="lasagna") 
    # => "Bob wants to eat lasagna"
    ```


---


