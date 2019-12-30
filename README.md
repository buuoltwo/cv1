# cv1
学习用

1.github
2.git bash: <code命令>
3.html
4.css/index.css
5.figma布局规划
6.测试link功能
7.声明盒模型
8.检查元素，虚拟表格
9.使用grid-area把元素如header塞进去
10.接下来就是页面细节。

~2019年12月28日11点52分/buuoltwo

1.修改html，添加头像姓名以及一段文字，有一定margin
2.为新添加的元素增加样式。
3.修改了grid布局是图方便的行高100px为auto
4.修改了tab-size:2
5.img 64*64 圆边
6.具体的居中是怎么实现的，我为什么注释掉header的margin:0 auto。
7.header的padding对应是什么涵义。
8.修改具体的margin使格局好看
9.博文挖坑：你绝不知道的水平垂直居中的方法*9。
10.给具体的板块做布局。

~2019年12月28日14点55分/buuoltwo

1.给main塞好位置
2.给main做两栏的grid布局：一行两列
3.给section:basics做grid布局：两行两列
4.写出来的代码没有很好的移植性，不好复制啊。一堆大于号：
```
.left > section {
	display: grid;
	grid: auto auto/ auto auto;
}
.left > sections > span.user {
	grid-area: 1/1/3/2;
}
.left > section > h2 {
	grid-area: 1/2/2/3;
}
.left > section > ul {
	grid-area: 2/2/3/3;
}
```
今天一天在莽，发现自己做完PC端都还没存档。
完成左边栏和右边栏。
那么预告一下copy4.0吧，只剩下移动端适配了，今晚搞定。

~2019年12月29日22点08分/buuoltwo

1.github真是个好东西，你可以在每一次提交中看到变动，实在是太赞了。都有点想不管成没成都提交一下ehhehe~

2.移动端改好了，pc端怎么也在变？