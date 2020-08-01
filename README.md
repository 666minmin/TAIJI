# TAIJI
自适应的太极八卦动图

知识点：
1、box-sizing
box-sizing:content-box，默认值
width = 内容的宽度
height = 内容的高度
宽度和高度的计算值都不包含内容的边框（border）和内边距（padding）

box-sizing:border-box
width = border + padding + 内容的宽度
height = border + padding + 内容的高度

2、 border-radius
如果width==height，border-radius的值>=1/2的width，那么就是一个员
通常设置border-raduis:50%

3、overflow
/* 默认值。内容不会被修剪，会呈现在元素框之外 */
overflow: visible;

/* 内容会被修剪，并且其余内容不可见 */
overflow: hidden

/* 内容会被修剪，浏览器会显示滚动条以便查看其余内容 */
overflow: scroll;

/* 由浏览器定夺，如果内容被修剪，就会显示滚动条 */
overflow: auto;

/* 规定从父元素继承overflow属性的值 */
overflow: inherit;

4、EM

5、height:100vh
当元素没有内容时候，设置height:100%，该元素不会被撑开，此时高度为0，
设置height:100vh，该元素会被撑开屏幕高度一致。

6、垂直居中布局
    display: flex;
    flex-direction: column;
    justify-content: center;/* 水平居中 */
    align-items: center;/* 垂直居中 */

7、动画旋转
   @keyframes myanimation {
        from {
            transform: rotate(0deg);
        }
        to {
            transform: rotate(360deg);
        }
    }
    animation: 10s myanimation linear infinite;

8、兼容移动端
 @media screen and (max-width: 500px) {}

 
