###1. 尽量用class选择器，不要轻易使用id
* id 是唯一的，class类选择器却可以重复使用

###2. 如无必要，不得为id、class选择器添加 类型选择器 进行限定；
```css
/* 不推荐 */
dialog#error,
p.danger-message {
    font-color: #c00;
}
/* 推荐 */
#error,
.danger-message {
    font-color: #c00;
}
```