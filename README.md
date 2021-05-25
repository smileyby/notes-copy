

<p align='center'>
    <img src="https://badgen.net/badge/labels/22"/>
    <img src="https://badgen.net/github/issues/smileyby/ghiblog"/>
    <img src="https://badgen.net/badge/last-commit/2021-05-25 09:12:59"/>
    <img src="https://badgen.net/github/forks/smileyby/ghiblog"/>
    <img src="https://badgen.net/github/stars/smileyby/ghiblog"/>
    <img src="https://badgen.net/github/watchers/smileyby/ghiblog"/>
    <img src="https://badgen.net/github/release/smileyby/ghiblog"/>
</p>

<p align='center'>
    <a href="https://github.com/jwenjian/visitor-count-badge">
        <img src="https://visitor-badge.glitch.me/badge?page_id=jwenjian.ghiblog"/>
    </a>
</p>


## 置顶 :thumbsup: 
- [封面图](https://github.com/smileyby/notes-copy/issues/1)  <sup>0 :speech_balloon:</sup>  	 
## 最新 :new: 

#### [小程序：{{}}取值运算符，不能运行indexOf方法的解决办法](https://github.com/smileyby/notes-copy/issues/17) <sup>0 :speech_balloon:</sup> 	 2021-05-25 09:12:22

:label: : [小程序 :cyclone:](https://github.com/smileyby/ghiblog/labels/%E5%B0%8F%E7%A8%8B%E5%BA%8F%20%3Acyclone%3A)

// 创建wxs文件
```js
function indexOf(arr, value){
  if (arr.indexOf(value) < 0) {
    return false;
  } else {
    return true;
  }
}
module.exp

[更多>>>](https://github.com/smileyby/notes-copy/issues/17)

---


#### [小程序：video播放器设置opacity:0在ios设备上不能播放 ](https://github.com/smileyby/notes-copy/issues/16) <sup>0 :speech_balloon:</sup> 	 2021-05-25 09:11:44

:label: : [小程序 :cyclone:](https://github.com/smileyby/ghiblog/labels/%E5%B0%8F%E7%A8%8B%E5%BA%8F%20%3Acyclone%3A)



[更多>>>](https://github.com/smileyby/notes-copy/issues/16)

---


#### [小程序：扫码打开对应界面，接收的参数](https://github.com/smileyby/notes-copy/issues/15) <sup>0 :speech_balloon:</sup> 	 2021-05-25 09:11:15

:label: : [小程序 :cyclone:](https://github.com/smileyby/ghiblog/labels/%E5%B0%8F%E7%A8%8B%E5%BA%8F%20%3Acyclone%3A)

掉小程序接口：https://api.weixin.qq.com/wxa/getwxacodeunlimit?access_token=ACCESS_TOKEN

通过scene传参，格式为 '?scene=xxxxx'

小程序拿到后decodeURIComponent 转码后才可以解析

[更多>>>](https://github.com/smileyby/notes-copy/issues/15)

---


#### [小程序：同一个元素 绑定长按和点击事件，两个事件会同时执行](https://github.com/smileyby/notes-copy/issues/14) <sup>0 :speech_balloon:</sup> 	 2021-05-25 09:10:09

:label: : [小程序 :cyclone:](https://github.com/smileyby/ghiblog/labels/%E5%B0%8F%E7%A8%8B%E5%BA%8F%20%3Acyclone%3A)

解决方法：多绑定 touchstart 和touchend 事件记录点击的时间，如果小于 350ms即为点击否则为长按

touchStart(e) {
   this.startTime = e.timeStamp;
},
touchEnd(e) {
  this.endTime = 

[更多>>>](https://github.com/smileyby/notes-copy/issues/14)

---


#### [小程序：wx.setStorageSync()和wx.setStorage()两个方法接受的参数不一致](https://github.com/smileyby/notes-copy/issues/13) <sup>0 :speech_balloon:</sup> 	 2021-05-25 09:08:44

:label: : [小程序 :cyclone:](https://github.com/smileyby/ghiblog/labels/%E5%B0%8F%E7%A8%8B%E5%BA%8F%20%3Acyclone%3A)

之前没仔细看，今天用的时候发现给setStorageSync传递对象参数会报错

带Sync，接受的参数是字符串以逗号分隔，不带Sync的接受一个对象作为参数，可以写回调函数

[更多>>>](https://github.com/smileyby/notes-copy/issues/13)

---


## 分类  :card_file_box: 

<details open="open">
    <summary>
        <img src="assets/wordcloud.png" title="词云, 点击展开详细分类" alt="词云， 点击展开详细分类">
        <p align="center">:cloud: 词云 :cloud: <sub>点击词云展开详细分类:point_down: </sub></p>
    </summary>


<details>
<summary>:+1:置顶	<sup>1:newspaper:</sup></summary>

- [封面图](https://github.com/smileyby/notes-copy/issues/1)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>:framed_picture:封面	<sup>1:newspaper:</sup></summary>

- [封面图](https://github.com/smileyby/notes-copy/issues/1)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>Bug :beetle:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>CSS :new_moon_with_face:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>Element-UI :mushroom:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>HTML :palm_tree:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>Node.js :turtle:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>React :globe_with_meridians:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>TypeScript :rabbit:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>VUE :milky_way:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>git :monkey_face:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>webpack :leaves:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>兼容 :six_pointed_star:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>小程序 :cyclone:	<sup>7:newspaper:</sup></summary>

- [小程序：{{}}取值运算符，不能运行indexOf方法的解决办法](https://github.com/smileyby/notes-copy/issues/17)  <sup>0 :speech_balloon:</sup>  	 
- [小程序：video播放器设置opacity:0在ios设备上不能播放 ](https://github.com/smileyby/notes-copy/issues/16)  <sup>0 :speech_balloon:</sup>  	 
- [小程序：扫码打开对应界面，接收的参数](https://github.com/smileyby/notes-copy/issues/15)  <sup>0 :speech_balloon:</sup>  	 
- [小程序：同一个元素 绑定长按和点击事件，两个事件会同时执行](https://github.com/smileyby/notes-copy/issues/14)  <sup>0 :speech_balloon:</sup>  	 
- [小程序：wx.setStorageSync()和wx.setStorage()两个方法接受的参数不一致](https://github.com/smileyby/notes-copy/issues/13)  <sup>0 :speech_balloon:</sup>  	 
- [小程序：thirdScriptError Cannot read property 'name' of undefined TypeError: Cannot read property 'name' of undefined](https://github.com/smileyby/notes-copy/issues/12)  <sup>0 :speech_balloon:</sup>  	 
- [小程序：scroll-view 组件 scroll-left 问题](https://github.com/smileyby/notes-copy/issues/10)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>开源	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>插件 :sun_with_face:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>摸鱼 :tropical_fish:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>每日任务 :bell:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>浏览器 :broken_heart:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>网络 :sparkles:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>设计相关:blossom:	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>面试 :umbrella:	<sup>0:newspaper:</sup></summary>



</details>


</details>    
