## 这是一个标题
不知道该写什么
- [ ] 努力成为一名合格的coder！
- [ ] 这是我要做的第二件事
> 这是一句引用

代码块使用方法：
```java
public class Fibonacci {
    public static void main(String[] args) {
        int n = 10;
        int result = fibonacciRecursive(n);
        System.out.println("斐波那契数列第 " + n + " 项的值为：" + result);
    }
    public static int fibonacciRecursive(int n) {
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return 1;
        }
        return fibonacciRecursive(n - 1) + fibonacciRecursive(n - 2);
    }
}
```

有序列表
1. 首先
1. 然后
1. 其次

无序列表
- 可以是横杠
- 喏
* 可以是星号
* 诺

数学公式
$$
\frac{\partial f}{\partial x} = 2\sqrt{a}x
$$

数学公式好像无法显示，没关系反正我也不会

表格
|语言|优势|劣势|
|--:|:--|:--:|
|java|good|bad|
|c++|good|bad|

脚注：
我是帅哥[^帅哥]
[^帅哥]:指身材伟岸，玉树临风

请注意，本人不是诈骗犯
文章分割符：
---
好，这是文章的第二个部分
怎么生成链接
[超多人爱用的学习网站](doubao.com "是正经网站哦")

![我的女神](https://u1.iqiyipic.com/image/20240821/5c/d1/pv_4851198236936800_d_601_480_270.jpg "嘿嘿嘿")

*斜体* **粗体**   <u>这一句话下面有下划线，没有就是实现不了</u>

`printf`

:smile:
$\theta=x^2$
H~2~O
x^2^
==高亮显示==

<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=113631782051054&bvid=BV1FPq1YbEpx&cid=27281788564&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
