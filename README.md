## 由来

我考A类操作证之前, 看了一下CRAC的题库, 其实就是一个TXT文件。背起来很枯燥, 看完一遍后只知道自己有很多不懂的, 但具体是哪些, 我并没有记下来。 所以我就快速写了一个简单的背题程序, 这样一来背题的效率就高了好多。

后来通过考试后, 也就把这个程序忘记了。

直到有一天听到BH4DEG和其他人通联时, 说道考试, 他这么说:"你做的模拟题不能保证覆盖了题库, 可能正好考了你没做到的模拟题呢, 所以还是得看题库。"

我才意识到原来很多人都不是背整个题库, 而是用其他HAM做的模拟考试程序。这个程序每次随机出30道题, 那及时做10次,也不能保证把370道题都覆盖。另外这个模拟程序只有安卓版的, 没有苹果版的。所以, 我就把我之前写的程序重写了一下(原来只管实现, 是典型的Quick and Dirty), 于是就有了这么一个程序。

希望能让更多的黑腿/香肠们能更容易的背题。

## 题库

题库按照 [CRAC 2015/06/12的题库文件](http://www.crac.org.cn/?page_id=1862)做成, 目前支持A、B、C三类操作证的题库。

## 支持的浏览器

除了老古董的IE6、IE7、IE8, 其他浏览器(电脑、手机、平板)应该都能正常使用。

## 网络

使用浏览器访问时, 只有第一次开启练习时需要下载题库, 之后就无需下载了。上班的朋友, 可以在进地铁前打开, 即使地铁上没信号也能正常答题并保存进度。

## 用法

在浏览器中打开 [http://www.bh4dks.com/aroe](http://www.bh4dks.com/aroe) 即可。

在第一个界面里可以从A类、B类、C类中选择需要练习的题库。一旦进入题库, 就会自动下载该题库里所有的题目, 除非切换到其他题库, 否则就不会再通过网络下载任何内容了。

![选择级别](https://raw.githubusercontent.com/bh4dks/aroe/master/assets/img/readme-class-level-select.png)

进入题库后, 屏幕左侧是练习方式的选择, 可以从: 随机做题、顺序做题、错题中选择。默认为随机做题, 这也是我推荐的做题方式。

![选择练习方式](https://raw.githubusercontent.com/bh4dks/aroe/master/assets/img/readme-exercise-type-select.png)

屏幕右侧是题目, 点击答案会看到选择是否正确。如果正确则进入下一题。如果错误, 则被选择的答案会以红色显示, 同时该题会被加入错题列表中。

![如果选错答案](https://raw.githubusercontent.com/bh4dks/aroe/master/assets/img/readme-answer-select-wrong.png)

屏幕上方是工具栏, 可以在上面进行题目跳转。如果你觉得错题都记住了, 可以点击"更多"按钮, 再点击"清除错题"按钮, 就会把当前类别中的错题清除。

![工具栏](https://raw.githubusercontent.com/bh4dks/aroe/master/assets/img/readme-toolbar.png)

程序可以随时关闭, 下次打开时还会继续从上次关闭时看到的题目开始。

## 更好的用法

在iPhone的浏览器中, 可以点击分享按钮, 将该网页"添加到主屏", 以便可以随时使用。

![添加到主屏1](https://raw.githubusercontent.com/bh4dks/aroe/master/assets/img/readme-share-to-home-screen-1.png)

![添加到主屏2](https://raw.githubusercontent.com/bh4dks/aroe/master/assets/img/readme-share-to-home-screen-2.png)
