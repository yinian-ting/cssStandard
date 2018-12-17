
##1. 选择器
* 尽量用class选择器，不要轻易使用id
* 如无必要，不得为id、class选择器添加 类型选择器 进行限定
```css
/* 不推荐 */
p#message {
    font-color: #c00;
}
/* 推荐 */
#message {
    font-color: #c00;
}
```