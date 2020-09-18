# vim_code
vim命令


### 使用vim的过程中想要快速移动光标至行首、行尾、第一行、最后一行或者某一行

##### 快速至当前行的行首

```html
1  Home键
2  数字0
3  符号^
```

##### 快速至当前行的行尾

```html
1  符号 $
2  End键
3  n+符号$ 表示当前行开始的第(n-1)行行尾
```

##### 快速至某行

```html
1  冒号(:)+行号+回车
2  行号+gg
3  行号+G(注意大写)
```

##### 快速至文件最后一行

```html
1  冒号(:)+$+回车
2  大写字母G
3  shift+g(同2)
```

