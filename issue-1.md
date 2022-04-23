https://www.yuque.com/mengzou/vrcz8w/bbuzu4

## "不正经"的文章

### [如何把前端项目写成一座屎山](https://juejin.cn/post/7086735198942920712)

又名『如何成为公司里不可替代的人才』。前端屎山精华教程！按此修炼，你在公司的地位将无可撼动，再也不会被裁员、被毕业！加薪永远第一个考虑你， 亲测无效！
精华教程：拒绝Ts、不做模块抽象和复用、编写长长长长长的组件、...、不要argue需求。
获得收益：公司地位无可撼动，除了你这个项目没人有能力或愿意接住，只能给你加钱，生怕你离职。
评论：我觉得应该换个标题，叫做如何成为公司里不可替代的人才
来自：掘金。作者：阿佛加德奔

## "没什么用"的库

## [vite-plugin-qwer](https://www.npmjs.com/package/vite-plugin-qwer)

> 来自上一篇文章的评论区『这些方法在我写的vite-plugin-qwer插件面前，论不可维护都不值得一提』

**这个插件可以让你编写出只有你自己才能认识的代码（可能也不行）**
为什么叫vite-plugin-qwer？突出一个不可维护性。
可以在代码中写出

```
🍎__ a ___ 🍎🍏 👉 📝🍎'Hello qwer'🍏🍏🍎🍏
```

会被vite-plugin-qwer转换成

```typescript
let a = () => console.log('Hello qwer')
```

并正确执行
**用上这款插件，保护好自己的密码本（codeBook）你就是公司最不可替代的一员**
来自：掘金，作者：[https://github.com/FliPPeDround](https://github.com/FliPPeDround)
点评：居然有100周下载量，离谱的是还有单测。

### [console-next](https://github.com/FliPPeDround/console-next)

This allows you to do some weird and useless in the browser's devtools。

```typescript
console.log('')
console.info(`console-next - This allows you to do some weird and useless in the browser's devtools`)
console.log('')

console.loading('installing npm package')
console.img('https://static.npmjs.com/58a19602036db1daee0d7863c94673a4.png', { width: 40, height: 40 })
console.img('https://lodash.com/assets/img/lodash.svg', { width: 40, height: 40 })
console.dom()
console.color([ { color: 'red', content: 'red', backgrounColor: 'rgb(0, 255, 0)' }, { color: 'rgb(0, 255, 0)', content: 'green' }, { color: '#000FFF', content: 'blue' } ])

console.log('')
```

![image.png](https://cdn.nlark.com/yuque/0/2022/png/730050/1650728181463-0a073752-aaaa-429b-ba1a-d63f6836f834.png#clientId=ue6a656af-d181-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=190&id=u3f4ac55f&margin=%5Bobject%20Object%5D&name=image.png&originHeight=380&originWidth=1268&originalType=binary&ratio=1&rotation=0&showTitle=false&size=76938&status=done&style=shadow&taskId=u7c656d9a-8f1b-4e59-a10f-44ee2facd9e&title=&width=634)

```typescript
{
  let i = 5
  console.progress(i, () => i += 5, 200)
}
```

![image.png](https://cdn.nlark.com/yuque/0/2022/png/730050/1650726962077-f15e8c07-5041-4999-a314-1a364577536d.png#clientId=ue6a656af-d181-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=66&id=u257df8df&margin=%5Bobject%20Object%5D&name=image.png&originHeight=132&originWidth=726&originalType=binary&ratio=1&rotation=0&showTitle=false&size=30056&status=done&style=shadow&taskId=u21a36365-3716-45aa-b012-7ca986301f7&title=&width=363)
![image.png](https://cdn.nlark.com/yuque/0/2022/png/730050/1650728128500-b1c60f09-8209-4bdb-be39-f2aa02140d8e.png#clientId=ue6a656af-d181-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=71&id=ud821d542&margin=%5Bobject%20Object%5D&name=image.png&originHeight=142&originWidth=720&originalType=binary&ratio=1&rotation=0&showTitle=false&size=33001&status=done&style=shadow&taskId=u48285a75-f539-4f4b-b90d-3d54b73ae58&title=&width=360)
安装 npm

```typescript
console.npm('loadsh')
```

播放视频

```typescript
// 请在 baidu.com 下使用
console.video(
  // from https://en.wikipedia.org/wiki/Big_Buck_Bunny
  'https://upload.wikimedia.org/wikipedia/commons/transcoded/c/c0/Big_Buck_Bunny_4K.webm/Big_Buck_Bunny_4K.webm.480p.vp9.webm',
  { width: 400, height: 200 }
)
```

来自：github，作者：[https://github.com/FliPPeDround](https://github.com/FliPPeDround)
点评：用播放视频的方式播放视频，是我万万没想到的👍🏻

```typescript
// https://github.com/FliPPeDround/console-next/blob/master/src/console.video.ts#L38
requestAnimationFrame (() => {
  captureImage(canvas, video)
  drawFame()
})
```

![image.png](https://cdn.nlark.com/yuque/0/2022/png/730050/1650729342705-5e8d6106-08b9-47b9-82e9-cc8e35b4da62.png?x-oss-process=image/format,png#clientId=u66c22c8b-8ce9-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=453&id=u59eab4f5&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1280&originWidth=720&originalType=binary&ratio=1&rotation=0&showTitle=false&size=2769270&status=done&style=shadow&taskId=u04d76285-225e-4a86-b48d-fa7326988ea&title=&width=255)

---

初始日期：2022-04-23
最终修改：TODO
