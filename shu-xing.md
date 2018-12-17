##1. 属性书写顺序
1. **布局方式**，包括 : 定位，浮动，flex
>`position / top / right / bottom / left `
> `display:flex /flex-flow ...`
> `float / left / right`

2. **盒模型+大小**，包括：宽，高，内外边距，边框
>`width / height `
> `padding / margin / border`

3. **文本排版** ，包括：文字，行高，对齐方式，word
>`font / font-size / font-family / font-weight / font-style `
> `line-height`
> `text-align / word-wrap / ...`

4. **视觉外观**，包括：颜色，背景等
> color / background / list-style

5. **其他**，包括：动画，过渡等
> transform / animation / transition / ...

##2. 属性简写
以下属性，如果只需定义其中的一两个属性，而不是全部，尽量分开来写。
* padding
* margin
* font
* background
* border
* border-radius
```css
/* 不推荐 */
.selector {
    margin: 0 0 10px;
    background: red;
    background: url(image.jpg);
    border-radius: 3px 3px 0 0;
}
/* 推荐 */
.selector {
    margin-bottom: 10px;
    background-color: red;
    background-image: url(image.jpg);
    border-top-left-radius: 3px;
    border-top-right-radius: 3px;
}
```





