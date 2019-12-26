# Vim实用技巧
---
![1.png](picture_1/1.png)

## 目录
[TOC]
## 前言

### Vim 键盘标记
```
:h key-notation
```
![picture_1](picture_1/p2.png)

## 技巧
### 1.Repeating commands—— . 
```
.
:h .
```
### 2.改变缩进层级—— >、< (p3)(p23)
```
>[Num]G
eg >2G
```
![p3.png](picture_1/p3.png)
```
>> 等价于 [Tab]
```

### 3.^——Home、$——End

### 4.删除
```
db——反向删除单词
dw——正向删除单词
daw——删除整个单词
d2aw——删除2个单词
```

### 5.大小写转换——g
先vision模式
![P23_1.png](picture_1/P23_1.png)
```
gu
```
![P23_1.png](picture_1/P23_2.png)
```
gU
```
![P23_3.png](picture_1/P23_3.png)
```
g~
```
![P23_4.png](picture_1/P23_4.png)

### 6.查看man——K
光标停在单词哪里
![p28_1.png](picture_1/p28_1.png)
```
K
```
![p28_2.png](picture_1/p28_2.png)

### 7.数学运算—— \<C-r>= <表达式> <CR>
光标显示在需要计算的位置
![p31_1.png](picture_1/p31_1.png)
```
<C-r>= 2*9 <CR>
```
![p31_2.png](picture_1/p31_2.png)
![p31_3.png](picture_1/p31_3.png)

### 8.选择块——\<C-v>
visual Module
![p42_1.png](picture_1/p42_1.png)
### 9.替换——r
visual Module
![p42__1.png](picture_1/p42__1.png)
```
r | <CR>
```
![p42__1.png](picture_1/p42__2.png)

### 10.打印——p
ex Module
```vi
2,9p    ;打印2-9行
```
![p51_1.png](picture_1/p51_1.png)
![p51_2.png](picture_1/p51_2.png)
```
:%p ;打印全文
```
![p51_3.png](picture_1/p51_3.png)

### 11.自动补全——set wildmenu

### 12.运行shell
```
:shell  ;进入bash
$> exit ;退出bash到vim
```
![p67_1.png](picture_1/p67_1.png)
![p67_2.png](picture_1/p67_2.png)

### 13.ctags
```
$> sudo pacman -S ctags
```
![p234.png](picture_1/p234.png)