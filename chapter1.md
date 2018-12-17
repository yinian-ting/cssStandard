##1. 什么是BEM？
* 即（block）、元素（element）、修饰符（modifier） 
* 具体请参考 https://segmentfault.com/a/1190000000391762
* 优点：
        1.增加代码可读性，通过浏览HTML代码中的class属性，就能够明白模块之间是如何关联的
        2. 增加代码复用，减少代码量

##2. 命名约定模式
* 用 下划线 _ 表示 ***元素的后代***
* 用 中划线 - 表示 ***元素的不同形态或不同版本***
* 例子如下：
```html
.person{}
.person_hand{}
.person_foot{}
.person-female{}
.person-female__hand{}
.person_hand-left{}
```
* 解析：
> * 顶级块是 person (人)
> * 他拥有一些元素，如 hand(手)，foot（脚）。
> * 一个人也会有其他形态，比如 female （女性）
> * female 也有一些元素，如 hand（手），手也有不同的形态，left（左手）

##3. 多单词连接
> 多个单词使用小驼峰式命名，不允许使用中划线或者下划线连接多个单词，以提升名称的识别度,例如 newList

## 命名简写
* 简写类名虽然可以减少代码量，但前提是要让人看懂你的简写
```css
/* 不推荐 */
.atr {
    margin: 0 ;
}
.navigation {
    margin: 0 ;
}
/* 推荐 */
.autor {
    margin: 0 ;
}
.nav {
    margin: 0 ;
}
```




