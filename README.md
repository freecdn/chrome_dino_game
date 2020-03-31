# 恐龙快跑!

更容易嵌入的"恐龙快跑!"游戏.

恐龙快跑!(T-Rex Runner) 是 Chrome 浏览器在离线时出现的小游戏彩蛋.你可以断开网络后,在 Chrome 进入任意链接看到这个游戏.

虽然已经有人将这个游戏抽离出来了(见 https://github.com/wayou/t-rex-runner ),但为了更方便的将游戏嵌入第三方网站,于是我创建了这个项目.

另外,我对游戏源码做了一些修改,让它也能运行在非 Chrome 浏览器( safari,微信 )里.

 > 当前版本的"恐龙快跑!"是从 Chrome 50.0.2661.86 (64-bit) 内抽离出来的.

## 如何使用

That's all:

```html
<div id="container"></div>
<script src="runner.js"></script>
<script>
 initRunner('#container');
</script>
```

## 说明

更更更容易嵌入的恐龙快跑游戏，前作者的文件目录还是很复杂，还不够简洁，现在直接引入runner文件一步到位！
runner.js可以处于任意位置，例如OSS云储存，Github，等。
