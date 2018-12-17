##1. 文本
>  文本内容必须用双引号包围
```css
.main {
  font-family: "Microsoft YaHei", sans-serif;
  content: "";
}
```

##2. 数值
>  当数值为 0 - 1 之间的小数时，省略整数部分的 0
```css
.main {
  opacity: .8;
}
```

##3. 长度
>  长度为 0 时须省略单位 (也只有长度单位可省)
```css
.main {
  margin: 0 5px;
}
```

##4. url()
> url () 中的路径不加引号
```css
.main {
  background: url(bg.png);
}
```

##5. 颜色
> * RGB颜色值 **必须使用十六进制记号形式 #rrggbb，不允许使用 rgb()**
> * 带有 alpha 的颜色信息可以使用 rgba()。
> * 颜色值中的英文字符采用大写
> * 颜色值不允许使用命名色值
```css
/* 不推荐 */
.selector {
    box-shadow: 0 0 2px rgba(0,128,0,.3);
    border-color: rgb(0, 128, 0);
    color: red;
}
/* 推荐 */
.selector {
    box-shadow: 0 0 2px rgba(0, 128, 0, .3);
    border-color: #008000;
    color: #F00;
}
```
